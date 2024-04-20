* Thread is like a flow of execution.
* MultiThreading Is the process of concurrently running more than one process.
* It is mostly used when the program has many I/O-bound processes.
* There is a Goldilocks Zone when it comes to selecting the Number of threads for a program and it is proportional to the number of cores in the CPU.
   *  _Too Few_  - Some cores remain unused Hence the system is Underutilized.
   * _Too Many_  - The Processor Spends a lot of time in Context Switching between threads resulting in a significant overhead.


 ### So We conduct an experiment where we Multiply 200 random 5000x5000 Matrices with a constant Matrix of 1000x1000 and check for what value of threads the program is most Efficient.

 We use the threading Library of the python.

Results:


| Number of Threads | Time taken(in Seconds) |
|---|---|
| 1 | 151.6999 |
| 2 | 144.8455 |
| 3 | 140.5331 |
| 4 | 143.6248 |
| 5 | 144.9216 |
| 6 | 143.2939 |
| 7 | 139.4404 |
| 8 | 142.7990 |
| 9 | 142.5757 |
| 10 | 141.6849 |
| 11 | 142.7475 |
| 12 | 138.4285 |
| 13 | 137.3216 |
| 14 | 139.1120 |
| 15 | 139.7402 |
| 16 | 138.3548 |
| 17 | 134.2259 |
| 18 | 141.0589 |
| 19 | 136.1073 |
| 20 | 141.3644 |




![image](https://github.com/Pratham20ag/Multi-Threading-Using-Python/assets/124654924/2f0679c3-d905-4bef-8a48-4d997579ea20)


 

 

 
