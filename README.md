# Operating System

This repository contains various codes and assignments related to Operating Systems. The implementations cover key OS concepts such as system calls, process management, synchronization methods, and more. It also includes practical examples to help understand OS functionalities in depth.

## 🛠️ Requirements 
To run and understand these OS operations, a Virtual Machine is required since some system calls and functionalities are not supported natively on Windows. The recommended setup is:
1. VirtualBox (or any other virtualization software)
2. A Linux-based OS (e.g., Ubuntu) as the virtual machine

To compile any program that involves the creation of thread(s), use the pthread library _(-lpthread)._

Suppose the program is named "Thread.cpp", then to compile, use the following command:

```$ g++ Thread.cpp -lpthread```

To run the program, use:

```$ ./a.out```

## 📂 Contents
The repository is organized into the following folders:

 ⚙️ System Calls

      write()
      read()
      open()
      lseek()
      dup()
      

 🏭 Process

      Process duplication using fork()
      Making parent process wait for the child to finish using wait()
      Orphan process creation
      Process duplication, avoiding orphan process
      Zombie process creation
    
      
 🔄 Synchronization

      Race Condition
      Synchronization using Mutex Locks
      Synchronization using Semaphores
      Dining Philosopher Problem

 
 🧵 Thread

     Thread creation
     Thread printing
     Thread gets multiple inputs
     
 🚫 Deadlock

     Deadlock simulation using Mutex Lock & Thread
 
 💾 Disk Scheduling Algorithms

     FCFS Disk Scheduling Algorithm

 
 
 
## 🎯 Purpose 
The aim of this repository is to serve as a resource for students, educators, and enthusiasts interested in learning about Operating Systems. Each implementation is designed to demonstrate key OS concepts with structured code and explanatory comments. This repository is ideal for those studying OS fundamentals, preparing for technical interviews, or working on academic projects.
## 🚀 Usage
1. Clone the repository:
   
   git clone https://github.com/RaianRashidRimon/Operating-System.git
2. Since OS operations require a Virtual Machine or a Linux-based OS, ensure you have VirtualBox set up with a Linux distribution. Then, navigate to the folder inside your virtual machine and run the desired code using a terminal and a compatible compiler (e.g., GCC for C programs):

## 🤝 Contribution
Contributions are highly encouraged! If you identify any issues, have suggestions for improvement, or want to add new algorithms, feel free to:
1. Open an issue describing the problem or suggestions.
2. Fork the repository, implement your changes, and create a pull request. 
