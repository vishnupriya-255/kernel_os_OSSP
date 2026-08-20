1.	Develop a C program that demonstrates how a Linux operating system executes a command entered by a user that 1. Accept a Linux command as input. 2. Create a child process using fork(). 3. Execute the command in the child process using an appropriate exec() system call. 4. Allow the parent process to wait for the child using wait (). 5. Display the Process ID (PID) of both parent and child processes.

2.	Using Linux terminal commands (uname, lscpu, lsblk, ps, top), investigate the relationship between hardware resources and operating system services. Prepare a report explaining how the OS abstracts CPU, memory, storage, and I/O devices.

   
-->1.The Operating System (OS) acts as a bridge between the user and the computer hardware.

2.It manages the **CPU** by deciding which program should run and for how long.

3.It manages **memory** by giving programs the required space and keeping them from interfering with each other.

4.For **storage**, it organizes data into files and folders and handles reading and writing data.

5.It also controls **I/O devices** like keyboards, mice, and printers through device drivers.

6.In this way, the OS makes hardware easier and safer for programs and users to use.

