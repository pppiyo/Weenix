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
This is a placeholder repo with no code to respect USC's Academic Code. If you are a potential employer and would like to look at the code, please send me an [email](amylee.lyq@gmail.com).

 Please also be noted that this is an ongoing project. As of Oct 27 of 2024, phase 1 - PROCS has been finished. VFS and VM will be finished in the coming 2 months.

## Related
Read more about the [course](https://merlot.usc.edu/cs402-f24/) and the [kernel projects](https://merlot.usc.edu/cs402-f24/projects/kernel/) here (username and password may apply since this is internal teaching material at USC).
