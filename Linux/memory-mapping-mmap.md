# Linux Memory Mapping (mmap)

- `mmap()` maps files or device memory into a process's virtual address space.
- It allows processes to access file contents through memory instead of traditional read and write operations.
- Memory mapping can support efficient file I/O and shared memory between processes.
- The mapping can be removed using `munmap()` when it is no longer needed.