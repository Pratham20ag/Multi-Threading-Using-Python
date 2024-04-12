* Thread is like a flow of execution.
* MultiThreading Is the process of concurrently running more than one process.
* It is mostly used where there are many I/O bound processes in the file.
* There is a Goldilocks Zone when it comes to selecting the Number of threads for a program and is proportional to the number of cores in the CPU
   *  _Too Few_  - Some cores remain unused Hence System is Underutilized
   * _Too Many_  - The Processor Spends a lot of time in Context Switching between threads resulting in a significant overhead.

 ### So We conduct an experiment where we Multiply 100 random 1000x1000 Matrices with a constant Matrix of 1000x1000 and check for what value of threads the program is most Efficient.

Results are in the python notebook.

 

 

 
