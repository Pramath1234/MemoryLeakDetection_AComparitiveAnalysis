# MemoryLeakDetection_AComparitiveAnalysis

A research project, which is a comparitive study based on advanced methodologies used to detect memory leaks in software programs. 
We have gone through research papers, and since we were not able to procure a large number of research on this topic, we've decided to come up with an extensive study on the same 
---------------------------------------------------
We have currently looked into the following tools: 
1. Valgrind
2. GDB Debugger
3. sar
4. abrt
5. Electric Fence
6. mtrace
7. Memleax
8. Leak Sanitizer
----------------------------------------------------

We also have a simple code implementation for detecting memory leaks: 
The concept used: When a user calls the library function "malloc or calloc " for allocating dynamic memory, we need to call our own functions, such as:
'MyCalloc' function in place of 'calloc' and MyMalloc function in place of 'malloc'.
So we have to define these functions according to our needs, and not deallocate the actual functions, malloc and calloc 
We will do the same for Library function "free" to deallocating memory( In our source file "MyFree" is used in place of free function).

------------------------------------------------------
The report, poster and the code files have been given the same repository. 


