> **Degree of Multiprogramming** : The number of processes currently in memory 

> **I/O Bound Process**: Spends more time doing I/O

> **CPU Bound Process**: Spends more time doing computations

> **Process Identifier**: Used to uniquely identify a process in most OS's

> **Cascading Termination**: Some systems don't allow child process to exist after parent process terminates(normally or abnormally), so all the children are also terminated after parent terminates. This is termination done by Operating System


> **Zombie Process**: Process that has terminated, but its parent has not yet called `wait()`.

> **Orphan Process**: Process whose parent terminates without calling `wait()`.

> **Independent Process**: The process that does not share data with any other process executing in the system.

> **Cooperating Process**: The process that can affect or get affected by another process running in the system.

>**** 