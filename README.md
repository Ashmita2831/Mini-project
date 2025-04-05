PROJECT TITLE:Round Robin scheduling
This is a C program which implements Round Robin(RR) Scheduling Algorithm, which is one of the simplest and most commonly used CPU scheduling algorithms. 
It works by allocating a fixed time slice (quantum) for each process, and the CPU switches between processes in a circular manner.

#How It Works
~Input: User enters the number of processes, burst times, and time quantum.

~Scheduling: The CPU allocates time quantum to each process in a circular manner. If a process doesn’t finish, it goes back to the queue with the remaining burst time.

~Output: Displays completion, waiting, and turnaround times, along with average metrics.

#Applications
~Time-sharing systems (e.g., multi-user OS)

~Multi-tasking OS (e.g., Linux, Windows)

~Real-time and interactive systems
