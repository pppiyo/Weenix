# Weenix
A full operating system kernel based on Unix.

## Content
### Kernel Threads (PROCS)
Threads, processes, and synchronization primitives.

### Virtual File System (VFS)
A polymorphic interface between the operating system kernel and the various file systems (such as S5FS and device drivers).

### Virtual Memory (VM)
User space address space management, running user-level code, servicing system calls, and basically everything else needed to combine all of the previous componenets into a fully functioning operating system. This includes virtual memory maps, handling page faults, memory management via anonymous objects and shadow objects, and system calls (in particular, the fork syscall).
  
## Important Notes
This repository serves as a placeholder in adherence to USC's Academic Code. If you are a potential employer interested in discussing the code, please feel free to reach out via email provided in my resume.<br><br>
Please also be noted that due to the same requirement, I could not provide the whole codebase but would be happy to share my knowledge and insights gained from the implementations.
