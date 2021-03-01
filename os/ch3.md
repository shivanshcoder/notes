# Processes

> Process is a program running in execution

---
### Sections of a process
* Text Section
  * The Executable Code
* Data Section
  * Global Variables
* Heap Section
  * Dynamically allocated memory during program execution
* Stack Section
  * Temporary Data storage such as function parameteres, return addresses and local variables

---


**Process is an active entity**

**Program is a passive entity**


# Process Control Block (PCB)

> Each process is represented by **Process Control Block** or **Task Control Block**

### Parts of PCB
* Process State
  * State of the process(running, waiting, ready, etc)
* Program Counter
  * Counter indicating the address of the next instruction to be executed
* CPU Registers
  * Includes the data of the registers if the process is halted because of interrupt, inorder to revive the processor state later on
* CPU-scheduling Information
  * 