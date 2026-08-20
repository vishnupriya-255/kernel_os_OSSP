To Analyze process abstraction, execute fork(), analyze parent-child relationships, inspect process tree, practice system call tracing


The Linux OS represents a running program as a **process** and manages it using process-related system calls.
The `fork()` system call creates a new **child process** from the parent process.
The `exec()` family replaces the child process with a new program.
We can use `ps` or `pstree` to observe the **parent-child relationship** and process tree.
Using `strace`, we can trace system calls such as `fork()`, `execve()`, and `wait()`.
This experiment helps us understand how Linux creates, manages, and executes processes.
