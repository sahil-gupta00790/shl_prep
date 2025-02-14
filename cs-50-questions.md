# 50 Essential CS Questions for 3rd Year Students

## Operating Systems (13 questions)

1. Q: What is a kernel in an operating system?
   A: The kernel is the core component of an OS that manages system resources and acts as a bridge between applications and hardware.

2. Q: Explain the difference between multiprogramming and multiprocessing.
   A: Multiprogramming allows multiple programs to share CPU time, while multiprocessing uses multiple CPUs to execute multiple processes simultaneously.

3. Q: What is context switching?
   A: Context switching is the process of saving and restoring the state of a process or thread so that execution can be resumed from the same point at a later time.

4. Q: Describe the banker's algorithm.
   A: The banker's algorithm is a resource allocation and deadlock avoidance algorithm that tests for safety by simulating allocation of maximum possible amounts of all resources.

5. Q: What is thrashing in OS?
   A: Thrashing occurs when a computer's virtual memory subsystem is in a constant state of paging, causing high memory utilization and low CPU utilization.

6. Q: Explain the readers-writers problem.
   A: The readers-writers problem is a synchronization problem where multiple readers can access shared data simultaneously, but writers need exclusive access.

7. Q: What is a race condition?
   A: A race condition occurs when multiple processes access and manipulate shared data concurrently, and the outcome depends on the order of execution.

8. Q: Describe the working of the Round Robin scheduling algorithm.
   A: Round Robin is a CPU scheduling algorithm where each process is assigned a fixed time slot in a cyclic way, ensuring fairness.

9. Q: What is a page table?
   A: A page table is a data structure used by the virtual memory system to store the mapping between virtual addresses and physical addresses.

10. Q: Explain the concept of demand paging.
    A: Demand paging is a method of virtual memory management where a page is brought into memory only when it is needed, reducing memory usage and start-up time.

11. Q: What is the purpose of swapping in OS?
    A: Swapping is used to temporarily remove inactive programs from memory to free up space for active programs, improving system performance.

12. Q: Describe the working of the producer-consumer problem.
    A: The producer-consumer problem is a classic synchronization issue where producers add data to a shared buffer and consumers remove it, requiring coordination to prevent conflicts.

13. Q: What is a real-time operating system (RTOS)?
    A: An RTOS is designed to serve real-time applications that process data as it comes in, typically with minimal delay and a deterministic nature.

## Computer Architecture (12 questions)

14. Q: What is the purpose of a register in CPU?
    A: Registers are small, fast storage locations within the CPU used for quick data access and manipulation during instruction execution.

15. Q: Explain the concept of data hazards in pipelining.
    A: Data hazards occur in pipelining when an instruction depends on the result of a previous instruction that hasn't completed execution.

16. Q: What is the difference between hardwired and microprogrammed control units?
    A: Hardwired control units use fixed logic circuits for control signals, while microprogrammed units use a microprogram stored in memory to generate control signals.

17. Q: Describe the concept of locality of reference.
    A: Locality of reference is the tendency of a processor to access the same set of memory locations repetitively over a short period of time.

18. Q: What is the purpose of a Translation Lookaside Buffer (TLB)?
    A: TLB is a cache used by the Memory Management Unit to speed up virtual-to-physical address translation.

19. Q: Explain the difference between SIMD and MIMD architectures.
    A: SIMD (Single Instruction, Multiple Data) executes the same instruction on multiple data points simultaneously, while MIMD (Multiple Instruction, Multiple Data) allows different instructions on different data.

20. Q: What is cache coherence in multiprocessor systems?
    A: Cache coherence ensures that multiple caches in a multiprocessor system maintain consistent views of the same memory locations.

21. Q: Describe the concept of branch target buffer.
    A: A branch target buffer is a cache used to predict the target of a branch instruction before the branch instruction is decoded.

22. Q: What is the purpose of memory interleaving?
    A: Memory interleaving is a technique to increase memory bandwidth by dividing memory into banks that can be accessed simultaneously.

23. Q: Explain the concept of precise exceptions in pipelining.
    A: Precise exceptions in pipelining ensure that when an exception occurs, the machine state is saved as if all instructions up to the exception have executed and none after have started.

24. Q: What is the difference between CISC and RISC architectures?
    A: CISC (Complex Instruction Set Computing) uses a large number of complex instructions, while RISC (Reduced Instruction Set Computing) uses a smaller number of simpler instructions.

25. Q: Describe the working of a floating-point unit (FPU).
    A: An FPU is a part of a CPU designed to carry out operations on floating point numbers, handling tasks like addition, subtraction, multiplication, division, and square roots.

## Computer Networks (13 questions)

26. Q: What is the purpose of the TCP sliding window?
    A: The TCP sliding window is used for flow control, allowing the sender to transmit multiple packets before requiring an acknowledgment.

27. Q: Explain the difference between a hub, a switch, and a router.
    A: A hub broadcasts data to all ports, a switch forwards data to a specific device, and a router forwards data between different networks.

28. Q: What is the purpose of the ARP protocol?
    A: ARP (Address Resolution Protocol) is used to map an IP address to a physical machine address (MAC address) in a local network.

29. Q: Describe the functioning of CSMA/CD.
    A: CSMA/CD (Carrier Sense Multiple Access with Collision Detection) is a network access method used in Ethernet to handle collisions in shared media.

30. Q: What is the difference between TCP and UDP?
    A: TCP (Transmission Control Protocol) is connection-oriented and ensures reliable, ordered delivery. UDP (User Datagram Protocol) is connectionless and doesn't guarantee delivery or order.

31. Q: Explain the concept of subnetting.
    A: Subnetting is the practice of dividing a network into two or more networks to improve network performance and security.

32. Q: What is a VPN and how does it work?
    A: A VPN (Virtual Private Network) creates a secure, encrypted connection over a less secure network, allowing safe transmission of sensitive data.

33. Q: Describe the purpose of ICMP protocol.
    A: ICMP (Internet Control Message Protocol) is used for error reporting and network diagnostics, such as in the ping utility.

34. Q: What is the difference between symmetric and asymmetric encryption?
    A: Symmetric encryption uses the same key for encryption and decryption, while asymmetric encryption uses a public key for encryption and a private key for decryption.

35. Q: Explain the concept of DNS and its hierarchy.
    A: DNS (Domain Name System) translates domain names to IP addresses. It uses a hierarchical structure with root, TLD, and authoritative name servers.

36. Q: What is the purpose of the OSI model?
    A: The OSI (Open Systems Interconnection) model is a conceptual framework used to describe network communication in seven layers.

37. Q: Describe the working of the DHCP protocol.
    A: DHCP (Dynamic Host Configuration Protocol) automatically assigns IP addresses and other network configuration parameters to devices on a network.

38. Q: What is network congestion and how is it controlled?
    A: Network congestion occurs when a network node or link carries more data than it can handle. It's controlled through techniques like traffic shaping, congestion avoidance algorithms, and quality of service prioritization.

## Database Concepts (12 questions)

39. Q: What is the difference between a primary key and a unique key?
    A: Both ensure uniqueness, but a primary key cannot accept null values and is the main identifier for a record, while a unique key can accept one null value.

40. Q: Explain the concept of database normalization.
    A: Normalization is the process of organizing data to minimize redundancy and dependency by dividing larger tables into smaller ones and defining relationships between them.

41. Q: What is a deadlock in database systems?
    A: A deadlock occurs when two or more transactions are waiting for one another to give up locks, resulting in none of them proceeding.

42. Q: Describe the ACID properties in database transactions.
    A: ACID stands for Atomicity (all-or-nothing execution), Consistency (database remains in a valid state), Isolation (concurrent transactions don't interfere), and Durability (committed changes are permanent).

43. Q: What is the difference between clustered and non-clustered indexes?
    A: A clustered index determines the physical order of data in a table, while a non-clustered index creates a separate structure for faster lookups without changing the table's structure.

44. Q: Explain the concept of a data warehouse.
    A: A data warehouse is a system used for reporting and data analysis, integrating data from multiple sources to support business intelligence activities.

45. Q: What is a trigger in databases?
    A: A trigger is a special type of stored procedure that automatically executes when a specified event occurs in the database server.

46. Q: Describe the concept of database sharding.
    A: Sharding is a database scaling technique where data is horizontally partitioned across multiple databases to distribute load and improve performance.

47. Q: What is the purpose of the HAVING clause in SQL?
    A: The HAVING clause is used in combination with the GROUP BY clause to filter group results based on a specified condition.

48. Q: Explain the difference between optimistic and pessimistic locking.
    A: Optimistic locking allows multiple transactions to proceed without locking resources, checking for conflicts at commit time. Pessimistic locking locks resources as soon as a transaction begins.

49. Q: What is a materialized view?
    A: A materialized view is a database object that contains the results of a query, stored as a concrete table that can be updated from the original base tables.

50. Q: Describe the concept of eventual consistency in distributed databases.
    A: Eventual consistency is a consistency model used in distributed systems that allows for temporary inconsistencies but ensures that all replicas will eventually converge to the same state.

These 50 questions cover a wide range of topics in Operating Systems, Computer Architecture, Computer Networks, and Database Concepts, suitable for a 3rd year CS student. Remember to understand these concepts deeply and be prepared to discuss their practical applications in real-world scenarios.
