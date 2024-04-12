* Thread is like a flow of execution.
* MultiThreading Is the process of concurrently running more than one process.
* It is mostly used when the program has many I/O-bound processes.
* There is a Goldilocks Zone when it comes to selecting the Number of threads for a program and it is proportional to the number of cores in the CPU.
   *  _Too Few_  - Some cores remain unused Hence the system is Underutilized.
   * _Too Many_  - The Processor Spends a lot of time in Context Switching between threads resulting in a significant overhead.


 ### So We conduct an experiment where we Multiply 100 random 1000x1000 Matrices with a constant Matrix of 1000x1000 and check for what value of threads the program is most Efficient.

 We use the threading Library of the python.

Results:


| Threads | Time Taken (seconds) |                          
|---|---|
| 1 | 1.4182 |
| 2 | 1.2698 |
| 3 | 1.2649 |
| 4 | 1.2811 |
| 5 | 1.2874 |
| 6 | 1.2236 |
| 7 | 1.2646 |
| 8 | 1.2343 |
| 9 | 1.2684 |
| 10 | 1.2854 |
| 11 | 1.2743 |
| 12 | 1.2339 |
| 13 | 1.1690 |
| 14 | 1.2624 |
| 15 | 1.1531 |
| 16 | 1.2281 |
| 17 | 1.0830 |
| 18 | 1.1492 |
| 19 | 1.2110 |
| 20 | 1.2819 |




![image](https://github.com/Pratham20ag/Multi-Threading-Using-Python/assets/124654924/e6718cd8-71c4-4073-b88c-3b4c36a95e35)

 

 

 
