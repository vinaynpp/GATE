* Basics
    * Introduction of Operating System
        * Functions of Operating system – Operating system performs three functions: 
            * Convenience: An OS makes a computer more convenient to use.
            * Efficiency: An OS allows the computer system resources to be used efficiently.
            * Ability to Evolve: An OS should be constructed in such a way as to permit the effective development, testing, and introduction of new system functions at the same time without interfering with service.
            * Throughput: An OS should be constructed so that It can give maximum throughput(Number of tasks per unit time).
        * Major Functionalities of Operating System: 
            * Resource Management: When parallel accessing happens in the OS means when multiple users are accessing the system the OS works as Resource Manager, Its responsibility is to provide hardware to the user. It decreases the load in the system.
            * Process Management: It includes various tasks like scheduling, termination of the process. OS manages various tasks at a time. Here CPU Scheduling happens means all the tasks would be done by the many algorithms that use for scheduling.
            * Storage Management: The file system mechanism used for the management of the storage. NIFS, CFS, CIFS, NFS, etc. are some file systems. All the data stores in various tracks of Hard disks that all managed by the storage manager. It included Hard Disk.
            * Memory Management: Refers to the management of primary memory. The operating system has to keep track, how much memory has been used and by whom. It has to decide which process needs memory space and how much. OS also has to allocate and deallocate the memory space.
            * Security/Privacy Management: Privacy is also provided by the Operating system by means of passwords so that unauthorized applications can’t access programs or data. For example, Windows uses Kerberos authentication to prevent unauthorized access to data.
        * OS is designed to serve two basic purposes: 
            * It controls the allocation and use of the computing System’s resources among the various user and tasks.
            * It provides an interface between the computer hardware and the programmer that simplifies and makes it feasible for coding, creation, debugging of application programs.
        * The Operating system must support the following tasks. The tasks are:  
            * Provides the facilities to create, modification of programs and data files using an editor.
            * Access to the compiler for translating the user program from high-level language to machine language.
            * Provide a loader program to move the compiled program code to the computer’s memory for execution.
            * Provide routines that handle the details of I/O programming.
        * I/O System Management – 
            * The module that keeps track of the status of devices is called the I/O traffic controller. Each I/O device has a device handler that resides in a separate process associated with that device. 
            * The I/O subsystem consists of 
                * A memory Management component that includes buffering caching and spooling.
                * A general device driver interface.
                * Drivers for specific hardware devices.
        * Assembler – 
            * The input to an assembler is an assembly language program
            * The output is an object program plus information that enables the loader to prepare the object program for execution
            * At one time, the computer programmer had at his disposal a basic machine that interpreted, through hardware, certain fundamental instructions. He would program this computer by writing a series of ones and Zeros (Machine language), place them into the memory of the machine. 
        * Compiler – 
            * The High-level languages- examples are FORTRAN, COBOL, ALGOL, and PL/I are processed by compilers and interpreters
            * A compiler is a program that accepts a source program in a “high-level language “and produces a corresponding object program
        * Interpreter – 
            * An interpreter is a program that appears to execute a source program as if it was machine language. The same name (FORTRAN, COBOL, etc.) is often used to designate both a compiler and its associated language. 
        * Loader – 
            * A Loader is a routine that loads an object program and prepares it for execution
            * There are various loading schemes
                * Absolute
                * Relocating
                * Direct-linking
            * In general, the loader must load, relocate and link the object program
            * The loader is a program that places programs into memory and prepares them for execution
            * In a simple loading scheme, the assembler outputs the machine language translation of a program on a secondary device and a loader places it in the core
            * The loader places into memory the machine language version of the user’s program and transfers control to it
            * Since the loader program is much smaller than the assembler, those make more core available to the user’s program. 
    * Types of Operating System 
        * Batch Operating System
          * ![](https://media.geeksforgeeks.org/wp-content/uploads/BatchOS.jpeg)
          * Sequence of jobs in a program on a computer without manual interventions.
          * This type of operating system does not interact with the computer directly. There is an operator which takes similar jobs having the same requirement and group them into batches. It is the responsibility of the operator to sort jobs with similar needs. 
          * Examples of Batch based Operating System: Payroll System, Bank Statements, etc.
        
        * Time-sharing operating System
          * ![](https://media.geeksforgeeks.org/wp-content/uploads/Time-Share.jpeg)
          * allows many users to share the computer resources. (Max utilization of the resources).
          * Each task is given some time to execute so that all the tasks work smoothly. Each user gets the time of CPU as they use a single system. These systems are also known as Multitasking Systems. The task can be from a single user or different users also. The time that each task gets to execute is called quantum. After this time interval is over OS switches over to the next task.
          * Examples of Time-Sharing OSs are: Multics, Unix, etc. 
          
        * Distributed operating System
          * ![](https://media.geeksforgeeks.org/wp-content/uploads/Distributed.jpeg)
          * Manages a group of different computers and makes appear to be a single computer.
          * These types of the operating system is a recent advancement in the world of computer technology and are being widely accepted all over the world and, that too, with a great pace. Various autonomous interconnected computers communicate with each other using a shared communication network. Independent systems possess their own memory unit and CPU. These are referred to as loosely coupled systems or distributed systems. These system’s processors differ in size and function. The major benefit of working with these types of the operating system is that it is always possible that one user can access the files or software which are not actually present on his system but some other system connected within this network i.e., remote access is enabled within the devices connected in that network. 
          * Examples of Distributed Operating System are- LOCUS, etc.

        * Network operating system- computers running in different operating systems can participate in a common network (It is used for security purposes).
        * Real-time operating system – meant applications to fix the deadlines.
    * Functions of Operating System
    * Real time systems
    * Tasks in Real Time systems
    * Difference between multitasking, multithreading and multiprocessing
    * Types of computer memory (RAM and ROM)
    * Difference between 32-bit and 64-bit operating systems
    * What happens when we turn on computer?
    * Boot Block
    * UEFI(Unified Extensible Firmware Interface) and how is it different from BIOS