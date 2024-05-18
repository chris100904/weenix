# weenix
A full operating system kernel, based on Unix, built as a semester-long project in CS2670 (Operating Systems) at Brown University. Information about the course and the individual projects can be found [here](https://github.com/brown-cs1690/handout/wiki).

Weenix is split up into 5 sub-projects. In order of completion:
  - **Procs** - Threads, processes, and synchronization primitives
  - **Drivers** - Device drivers for terminals, disks, and memory devices `/dev/zero` and `/dev/null`
  - **VFS** (Virtual File System) - The common interface between the operating system kernal and the various file systems
  - **S5FS** (System V File System) - A file system based on the original Unix file system with an emphasis on implementing an on-disk system
  - **VM** (Virtual Memory) - Management of user address spaces, running user-level code, and servicing system calls. Essentially is everything else that is required to integrate all previous components into a fully functional operating system, which includes virtual memory maps, pagefault handlers, memory management via map objects, and system calls (in particular, `fork` and `brk` syscalls)

**NOTE**: Due to Brown's Academic Code, this is a placeholder repo. If you are a potential employer and would like to look at the code, please reach out to me. 
