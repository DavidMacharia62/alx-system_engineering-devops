# PROCESSES & SIGNALS

## PID

A PID (Process Identifier) is a unique numerical identifier assigned to a process running on a computer system. It is used by the operating system to track and manage processes.

## PROCESS

A process, in the context of computer science, refers to a program or task that is currently being executed by the computer's operating system. It represents an instance of a computer program that is running and includes the program's code, data, and resources.

To find a process's PID, you can use various system utilities and commands depending on the operating system you are using:

On Unix-like systems (e.g., Linux, macOS), you can use the ps command in the terminal along with options such as aux or ef to display a list of processes along with their PIDs.
On Windows, you can use the Task Manager utility by pressing Ctrl+Shift+Esc or right-clicking the taskbar and selecting Task Manager. The PID of each process is listed in the "PID" column.
To kill (terminate) a process, you can use the appropriate command or utility based on the operating system:

On Unix-like systems, the kill command is commonly used to send a termination signal to a process. For example, you can use kill <PID> or kill -9 <PID> to forcefully terminate a process with the specified PID.
On Windows, you can use the Task Manager utility mentioned earlier. Right-click on the process you want to terminate and select "End Task."
In the context of process termination, a signal is a software interrupt delivered to a process to notify it of a particular event or request it to perform a certain action. Signals can be used to communicate with processes, control their behavior, and handle various events.

The two signals that cannot be ignored by a process are:

### SIGKILL (signal number 9): 

This signal is used to forcefully terminate a process. When a process receives this signal, it is immediately terminated without any chance to clean up or perform any actions.

### SIGSTOP (signal number 19 or 17): 

This signal is used to pause or stop a process temporarily. When a process receives this signal, it is suspended and put into a stopped state. The process can be resumed later by sending the SIGCONT signal.
