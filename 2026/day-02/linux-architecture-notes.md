Linux Achitecture:
The architecture of Linux is based on 'ASK'
A Stands for Application
S Stands for Shell
K Stands for Kernel

At the core of Linux is Hardware, which communicates with the Kernel of the linux using device drivers. Shell is used as a middleware between kernel and user to communicate with the kernl using system calls primarily in the forms of shell commands.

Systemd or init is the first process of the system having PID 1 started by the kernel.
All the other process are started after the the systemd or init process. 
Linux Process State:
1. Running or Runnable State (R) - A process executing its code and logic and taking up resources is running process.
                                   A process waiting in the run queue to execute its code and logic is runnable process.
2. Uninterruptable Sleep State (D) - A process waiting for resources to be available before moving to runnable state is Uninterruptable sleep state. This state doesn't react to signals.
3. Interruptable Sleep State (S) - A process waiting for resources to be available and inputs from the outside is Interruptable sleep state. This stae reacts to signals.
4. Stopped State (T) - State in which the process is moved from running or runnable to halt. Can be done using SIGTSTP or SIGSTOP.
5. Zombie State (Z) - When a process is completed or terminated but the parent process has not cleared the process from its process table.

Five Daily Use Commands:
1. ls - to list out content in the current directory.
2. cd - to change the directory from the current directory.
3. touch - to create an new file.
4. mkdir - to create an new directory.
5. rm - to remove a file or a directory.
