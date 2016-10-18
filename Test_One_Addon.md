# Test Add-On

### Multi*
1. Multitasking
  * A mode of operation that provides for the concurrent performance or interleaved execution of two or 
  more computer tasks. The same as multiprogramming, using different terminology.
  * Ex: Windowns and UNIX OS
2. Multiprogramming
  * A mode of operation that provides for the interleaved execution of two or more computer programs 
  by a single processor. The same as multitasking, using different terminology.  
  * Ex: Windows and UNIX OS
3. Multiprocessing
  *  A mode of operation that provides for parallel processing by two or more processors of a multiprocessor.
  * Ex: Windows OS
4. Mutlithreaded
  * A technique by which a single set of code can be used by several processors at different stages of execution.
  * Certain Java OS
  
### Review Questions from Chapter 3
1. A sequence of instructions that execute for that process.
2. Common events that lead to the creation of a process include:
  * new batch job
  * interactive log-on
  * created by OS to provide a service
  * spawned by existing process
3. To preempt a process means to interrupt a process without requiring its cooperation, and with intent to resume it later.
4. Swapping is to move part or all of a process from main memory to disk, and vice versa
5. There is the blocked state where the process is in main memory and waiting for an event, and there is the blocked/suspended
state, where the process is in the secondary memory and waiting for an event.
6. Characteristics for a suspended process:
  * The process is not immediately available for execution.
  * The process may or may not be waiting for an event.
  *The process was placed in a suspended state by an agent: either itself, a parent process, or the operating system, 
  for the purpose of preventing its execution.
  *The process may not be removed from this state until the agent explicitly orders the removal.
7. Catagories of information in PCB:
  * Process identification
  * Processor state information
  * Process control information
8. Two modes are used to protect the OS and key operating system tables, such as process control blocks, 
from interference by user programs
9. An interrupt is external and independent from current running process, while a trap is an error or exception 
condition generated within the currently running process
10. Interrupt Examples:
  * clock interrupt
  * I/O interrupt
  * Memory fault
11. A mode switch may occur without changing the state of the process that is currently in the Running state. Whereas a 
process switch involves a state change - much more expensive.
