# 50 Operating Systems Questions for 3rd Year CS Students

1. Q: What is an operating system?
   A: An OS is software that manages computer hardware and software resources, providing common services for computer programs.

2. Q: Explain the difference between a process and a thread.
   A: A process is an independent program with its own memory space, while a thread is a lightweight unit of execution within a process, sharing the same memory space.

3. Q: What is multiprogramming?
   A: Multiprogramming is the ability of an OS to execute multiple programs concurrently by switching between them.

4. Q: Describe the function of a scheduler in an OS.
   A: A scheduler allocates CPU time to different processes or threads, determining which one to execute next.

5. Q: What is virtual memory?
   A: Virtual memory is a memory management technique that provides an idealized abstraction of the storage resources actually available on a given machine.

6. Q: Explain the concept of deadlock.
   A: Deadlock is a situation where two or more processes are unable to proceed because each is waiting for the other to release a resource.

7. Q: What is a semaphore?
   A: A semaphore is a variable used to control access to a common resource by multiple processes in a concurrent system.

8. Q: Describe the purpose of paging in memory management.
   A: Paging is a memory management scheme that eliminates the need for contiguous allocation of physical memory, reducing fragmentation.

9. Q: What is the difference between preemptive and non-preemptive scheduling?
   A: In preemptive scheduling, the CPU can be taken away from a process before it finishes execution. In non-preemptive scheduling, once a process starts, it continues until it terminates or blocks.

10. Q: Explain the concept of thrashing.
    A: Thrashing occurs when a computer's virtual memory subsystem is in a constant state of paging, severely degrading system performance.

11. Q: What is a device driver?
    A: A device driver is a software component that allows the OS to interact with a hardware device.

12. Q: Describe the working of the Round Robin scheduling algorithm.
    A: Round Robin assigns a fixed time unit per process, and cycles through them. If a process is not finished in its time slot, it's moved to the back of the queue.

13. Q: What is a critical section in concurrent programming?
    A: A critical section is a part of a program where a shared resource is accessed, and which must not be concurrently executed by more than one process.

14. Q: Explain the concept of memory fragmentation.
    A: Memory fragmentation occurs when memory is allocated and deallocated in small chunks, leaving small gaps of unused memory that are difficult to allocate.

15. Q: What is the purpose of the Translation Lookaside Buffer (TLB)?
    A: The TLB is a cache used by the Memory Management Unit to improve virtual address translation speed.

16. Q: Describe the differences between internal and external fragmentation.
    A: Internal fragmentation occurs when more memory is allocated than necessary, while external fragmentation occurs when free memory is available in small, non-contiguous blocks.

17. Q: What is the role of the file system in an OS?
    A: The file system manages how data is stored and retrieved. It organizes data into files and directories and tracks where these are located on the storage device.

18. Q: Explain the concept of a race condition.
    A: A race condition occurs when multiple processes access and manipulate shared data concurrently, and the outcome depends on the order of execution.

19. Q: What is context switching?
    A: Context switching is the process of saving and restoring the state of a process or thread so that execution can be resumed from the same point at a later time.

20. Q: Describe the working of the banker's algorithm.
    A: The banker's algorithm is a resource allocation and deadlock avoidance algorithm that tests for safety by simulating allocation of maximum possible amounts of all resources.

21. Q: What is the purpose of swapping in memory management?
    A: Swapping is used to temporarily remove inactive programs from memory to free up space for active programs, improving system performance.

22. Q: Explain the differences between user mode and kernel mode.
    A: User mode is a restricted mode where programs have limited access to system resources, while kernel mode has unrestricted access to system resources.

23. Q: What is a page fault?
    A: A page fault occurs when a program tries to access a memory page that is mapped in the virtual address space, but not loaded in physical memory.

24. Q: Describe the concept of demand paging.
    A: Demand paging is a method of virtual memory management where a page is brought into memory only when it is needed, reducing memory usage and start-up time.

25. Q: What is the purpose of the fork() system call?
    A: fork() creates a new process by duplicating the calling process. The new process is called the child process, and the original process is the parent.

26. Q: Explain the concept of priority inversion.
    A: Priority inversion occurs when a high-priority task is indirectly preempted by a medium-priority task effectively "inverting" the relative priorities of the two tasks.

27. Q: What is a zombie process?
    A: A zombie process is a process that has completed execution but still has an entry in the process table to report to its parent process.

28. Q: Describe the working of the producer-consumer problem.
    A: The producer-consumer problem is a classic synchronization issue where producers add data to a shared buffer and consumers remove it, requiring coordination to prevent conflicts.

29. Q: What is the difference between a monolithic kernel and a microkernel?
    A: A monolithic kernel is a large kernel where all OS services run in kernel space. A microkernel runs only essential services in kernel space and other services in user space.

30. Q: Explain the concept of a mutex.
    A: A mutex (mutual exclusion) is a program object that allows multiple program threads to share the same resource, but not simultaneously.

31. Q: What is the purpose of the wait() system call?
    A: The wait() system call is used by a parent process to wait for the termination of a child process.

32. Q: Describe the working of the Least Recently Used (LRU) page replacement algorithm.
    A: LRU replaces the page that has not been used for the longest period of time when a page fault occurs.

33. Q: What is a real-time operating system (RTOS)?
    A: An RTOS is designed to serve real-time applications that process data as it comes in, typically with minimal delay and a deterministic nature.

34. Q: Explain the concept of a device controller.
    A: A device controller is a hardware component that interfaces between the OS and a specific type of device, managing the device's operation.

35. Q: What is the purpose of the exec() system call?
    A: The exec() system call is used to execute a new program, replacing the current process image with a new process image.

36. Q: Describe the working of the First-Come, First-Served (FCFS) scheduling algorithm.
    A: FCFS is a simple scheduling algorithm that allocates the CPU to processes in the order they arrive in the ready queue.

37. Q: What is the difference between hard and soft real-time systems?
    A: Hard real-time systems must complete critical tasks within a guaranteed amount of time, while soft real-time systems where a critical task gets priority over other tasks but without the guarantee.

38. Q: Explain the concept of a file descriptor.
    A: A file descriptor is a unique identifier that the OS assigns to a file when it is opened. It's used to access the file in subsequent operations.

39. Q: What is the purpose of the nice value in process scheduling?
    A: The nice value is used to adjust the priority of a process, allowing users to influence the scheduler's decisions.

40. Q: Describe the working of the elevator algorithm (SCAN) for disk scheduling.
    A: The elevator algorithm moves the disk arm back and forth across the disk, servicing requests in each direction, similar to how an elevator operates.

41. Q: What is the difference between cooperative and preemptive multitasking?
    A: In cooperative multitasking, processes voluntarily yield control periodically. In preemptive multitasking, the OS can forcibly suspend a process to run another.

42. Q: Explain the concept of a spinlock.
    A: A spinlock is a lock which causes a thread trying to acquire it to simply wait in a loop ("spin") while repeatedly checking if the lock is available.

43. Q: What is the purpose of the sync() system call?
    A: The sync() system call is used to flush all in-memory modified ("dirty") buffers to disk.

44. Q: Describe the working of the copy-on-write (COW) mechanism.
    A: COW is an optimization strategy used in forking where the parent and child processes initially share the same memory pages, and pages are copied only when they are modified.

45. Q: What is the role of the Completely Fair Scheduler (CFS) in Linux?
    A: CFS is the default Linux scheduler that aims to maximize CPU utilization while also maximizing interactive performance.

46. Q: Explain the concept of a system call.
    A: A system call is the programmatic way in which a computer program requests a service from the kernel of the OS.

47. Q: What is the purpose of the /proc filesystem in Unix-like systems?
    A: The /proc filesystem is a pseudo-filesystem that provides an interface to kernel data structures, allowing processes to be manipulated as files.

48. Q: Describe the working of the shortest job first (SJF) scheduling algorithm.
    A: SJF selects the process with the smallest execution time to execute next, potentially leading to minimal average waiting time.

49. Q: What is the difference between a pipe and a socket for inter-process communication?
    A: A pipe is used for communication between related processes (typically parent-child), while a socket can be used for communication between unrelated processes, even across different machines.

50. Q: Explain the concept of a race condition and how it can be prevented.
    A: A race condition occurs when multiple processes access shared data concurrently. It can be prevented using synchronization mechanisms like mutexes, semaphores, or atomic operations.
