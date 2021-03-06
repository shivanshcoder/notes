# Interprocess Communication ( #IPC )
Cooperating Processes require that different processes may try to contact each other or try to change each other's data in some manner. This communication is achieved by Interprocess Communication.
	
---

## Reason for Process Cooperation
* **Information Sharing**: Several application interested in same information.
* **Computational Speedup**: Breaking task into for execution in parallel.
* **Modularity**: System in Modular fashion dividing the system functions into separate processes and threads.

---

### Message Passing #IPC


### Shared Memory #IPC
Shared Memory Region resides in the address space of the the process creating the segment.
This requires that two or more processes agree to remove the restriction and allow exchange of information by reading and writing data in shared areas.

> **Unbounded Buffer** : No practical limit on size of buffer.
>  **Bounded Buffer** : Fixed size Buffer


## Examples of #IPC
* Shared Memory IPC