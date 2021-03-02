# #Process
Program in Execution is called a process.
**Program is an Passive entity, whereas Process is an Active entity**

---

## Sections of a Process
* Text Section: 
	* the executable code
	* Fixed size
* Data Section:
	*  Global variables
	*  Fixed Size
* Heap Section:
	*  Dynamically allocated memory during program runtime
	* Grows upwards to the stack section
	* Grows and shrinks, as and when the memory is allocated by the user
* Stack Section: 
	* Temporary data storage when invoking functions
	* Grows downward to the Heap Section
	* Example: Each function call, Activation record(return addr, function arguments, local vars) are pushed into the stack memory and after returning, the memory shrinks back

[Process Memory Structure](https://www2.cs.uic.edu/~jbell/CourseNotes/OperatingSystems/images/Chapter3/3_01_Process_Memory.jpg)


---

## #Process_State
Defined by the current activity of that process

### States of a Process
* New: process being created
* Running: Instructions being executed
* Waiting: Waiting for some event(I/O, signal) to occur
* Ready: Waiting to be assigned to a processor
* Terminated: Finished Execution

[Process State Diagram](https://www.researchgate.net/profile/Ibrahim-Abdullahi-7/publication/260973132/figure/fig1/AS:614330252918789@1523479154482/Process-State-Diagram.png)

---

## Process Control Block( #PCB )
Each Process is represented by #PCB in an Operating System

### Components of a PCB
* [[os/Processes/Process#Process State|Process State]]
* Program Counter: 
	* Counter indicating address of the next instruction to be executed
* CPU Registers:
	* Stores the Registers data when process gets into Halt stage(waiting state)
* CPU-Scheduling Information:
	* [[Process priotity]], [[Scheduling Queues]], other Scheduling parameters
* Memory management information
	* Value of base, limit registers, page tables, segment tables [[Memory]]
* Accounting Information
	* Amount of CPU
	* Real time used
	* Time limits
	* Account numbers
	* Job or process numbers
* I/O status information
	* List of I/O devices allocated to the process

---

**Operating Systems identify #Process process using Process Identifier ( #PID ) **

### Child and Parent Process
* Child Process can directly 






