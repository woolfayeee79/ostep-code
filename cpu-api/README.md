<<<<<<< HEAD
# ostep-code
Code from various chapters in OSTEP (http://www.ostep.org)

* [Introduction](intro)

## Virtualization

CPU Virtualization Chapters:
* Processes
* [Process API](cpu-api)
* Direct Execution
* CPU Scheduling
* Multi-level Feedback
* [Lottery Scheduling](cpu-sched-lottery)
* Multi-CPU Scheduling

Memory Virtualization Chapters:
* [Address Spaces](vm-intro)
* Memory API
* Address Translation
* Segmentation
* Free Space Management
* Introduction to Paging
* Translation Lookaside Buffers
* Advanced Page Tables
* Swapping: Mechanisms
* Swapping: Policies
* Complete VM Systems

## Concurrency

Concurrency Chapters:
* [Concurrency and Threads](threads-intro)
* [Threads API](threads-api)
* [Locks](threads-locks)
* Locked Data Structures
* [Condition Variables](threads-cv)
* [Semaphores](threads-sema)
* Concurrency Bugs
* Event-based Concurrency

## Persistence

Persistence Chapters:
* I/O Devices
* Hard Disk Drives
* Redundant Disk Arrays (RAID)
* Files and Directories
* File System Implementation
* Fast File System (FFS)
* FSCK and Journaling
* Log-structured File System (LFS)
* Flash-based SSDs
* Data Integrity and Protection
* Distributed Systems
* Network File System (NFS)
* Andrew File System (AFS)
=======
## CPU API

Code from OSTEP chapter [Interlude: Process API](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-api.pdf).

To compile, just type:
```
prompt> make
```

See the highly primitive `Makefile` for details.

Then run `p1`, `p2`, `p3`, or `p4`, as need be. Examples:

```
prompt> ./p1
```

```
prompt> ./p2
```

```
prompt> ./p3
```

```
prompt> ./p4
```



>>>>>>> First commit

