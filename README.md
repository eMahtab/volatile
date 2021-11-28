# volatile
In a multithreaded application where the threads operate on non-volatile variables, each thread may copy variables from main memory into a CPU cache while working on them, for performance reasons. If your computer contains more than one CPU, each thread may run on a different CPU. That means, that each thread may copy the variables into the CPU cache of different CPUs.

The Java volatile keyword guarantees visibility of changes to variables across threads.







# References :
http://tutorials.jenkov.com/java-concurrency/volatile.html
