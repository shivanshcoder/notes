**In Linux term Process is refereed as task **

## swapping
Sometimes it is advantageous to remove a process form memory(usually not in use and reducing #degree_of_multiprogramming). Later when needed the program is brought back into memory for usage, where it left earlier.
Swapping is only necessary when memory has been over committed and must be free up.


## Context Switch
When an interrupt occurs, the system needs to save the current context of the process running on the CPU so that later on it can be restored for properly resuming the process.
**Context Switch** is essentially a state save of the current process and state restore of a different process. Time required for this is highly dependent on the hardware.

**Context switch is pure overhead because CPU does no useful work**

#TODO include image for context switch

Context includes:
* Values of CPU registers
* Process State
* Memory management Information 


