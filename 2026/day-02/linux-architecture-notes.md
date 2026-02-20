# Day 2 Task

- Linux Process State
  1) Running: When a new process starts it is placed in R state
  2) Interruptible Sleeping: During a process execution there might be a point where the process needs to request external resources like I/O or network request.
     In such cases it goes to sleeping state, it gives up its CPU cycles to othe rtask which is ready to run, and can react to signals and availability of resources
  3) uninterrutible Sleeping State: During a process execution there might be a point where the process needs to request external resources like I/O or network request.
     In such cases it goes to sleeping state, it gives up its CPU cycles to othe rtask which is ready to run, but here the process does not react to any signals
  4) Stopped State: A process is suspended from further execution
  5) Zombie State: A child process which is terminated lies here.

- 5 commands used daily
  1) ls
  2) cd
  3) pwd
  4) clear
  5) ssh

- Core Components of Linux
  1) Hardware Layer
  2) Linux Kernal
  3) Shell
  4) Application/User

- systemmd
  It is the first process with PID 1, which is basically starting the OS.
