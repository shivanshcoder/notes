# Process Scheduling
In [[Multiprogramming]], we have some process running all the time, in order to maximize CPU utilization.
[[Time Sharing]], we switch process so quickly that users can interact with each program while it is running.
For achieving above tasks, we have **Process Scheduler**

> #degree_of_multiprogramming 
> The number of processes currently in memory is known as the degree of multiprogramming



## Scheduling Queues
Various Queues where processes are placed when they are not using CPU time

#TODO Place the diagram here | Queuing Diagram representation of process scheduling

* Ready Queue: When process is waiting for CPU time
* I/O wait Queue
* Child termination Queue
* Interrupt Wait Queue


## CPU Scheduling
Selects the process from the #READY_QUEUE and allocate a CPU core. CPU keeps switching processes, in order to be more productive

Some OS's have an intermediate form of scheduling known as #swapping.



