# Process Creation
Every Process is created by some other parent process, so in #Linux the root process(First process to be created) is either #init or #systemd.


## Child Process Resource allocation
* May directly obtain resources from #OS 
*  Constrained to a subset of the resources of the parent process(Parent Process may partition resources among the children). This prevents any process from overloading the system from creating too many children.

## Address Space possibilities of the Child Process
* The child is a duplicate of the parent (`fork` function in #Linux)
* The child process has a new program loaded into it.


# Process Termination
A Process terminates when it finishes executing final statement, All the resources of the process:
>* Physical Memory
>* Virtual Memory
>* Open Files
>* I/O Buffers

are all deallocated.

**Some Systems don't allow child process to exist after parent terminates**
