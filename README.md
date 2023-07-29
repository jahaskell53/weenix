# weenix
A stub repo for a Unix-based operating systems kernel built as a semester-long project in CS1690 (Operating Systems with Lab). 

The following is a list of subprojects of Weenix:
- Processes and Threads: Infrastructure such as a scheduler and various synchronization primitives that allow the kernel to have multiple threads and processes and that they run concurrently in kernel mode.
- Drivers: Device drivers for terminals, disks, and memory devices.
- Virtual File System: A polymorphic interface between the operating system kernel and the various file systems (such as S5FS and device drivers).
- System V File System: A file system implementation based on the original Unix file system.
- Virtual Memory: Userspace address space management, running user-level code, servicing system calls, and basically everything else needed to combine all of the previous components into a fully functioning operating system. This includes virtual memory maps, handling page faults, memory management via anonymous objects and shadow objects, and system calls (in particular, the fork syscall).

Inspiration for this repo and project descriptions are from [Nathan Benavides-Luu's repo](https://github.com/nthnluu/weenix). 
A more detailed overview of this project is available [here](https://github.com/brown-cs1690/handout/wiki).  
