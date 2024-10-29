# Weenix
A full operating system kernel, based on Unix, built as a semester-long project in CSCI 402 (Operating Systems) at USC.

## Content
### Kernel Threads (PROCS)
Threads, processes, and synchronization primitives.

### Virtual File System (VFS)
A polymorphic interface between the operating system kernel and the various file systems (such as S5FS and device drivers).

### Virtual Memory (VM)
Userspace address space management, running user-level code, servicing system calls, and basically everything else needed to combine all of the previous componenets into a fully functioning operating system. This includes virtual memory maps, handling page faults, memory management via anonymous objects and shadow objects, and system calls (in particular, the fork syscall).
  
## Important Notes
This repository serves as a placeholder in adherence to USC's Academic Code. If you are a potential employer interested in reviewing the code, please feel free to [reach out via email](mailto:amylee.lyq@gmail.com).

Please also be noted that this is an ongoing project. As of Oct 26, 2024, phase 1 (PROCS) is complete, with VFS and VM expected to finish in the next two months.
