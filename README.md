# **Linux Shell Scripting** ![Shell Scripting](https://img.shields.io/badge/Shell-Scripting-blue)
-----

**Introduction to Linux Shell and Shell Scripting** 

  Linux shell scripting is a powerful way to automate tasks and manage systems effectively. 
  
  If we are using any major operating system, we are indirectly interacting with the shell. While running Ubuntu, or any other Linux distribution, we are interacting with the shell by using the terminal.

 **What is Kernel?**
 
  The kernel is a computer program that is the core of a computer’s operating system, with complete control over everything in the system. It manages the following resources of the Linux system –

  1. File management
  2. Process management
  3. I/O management
  4. Memory management
  5. Device management etc.

It is often mistaken that Linus Torvalds has developed Linux OS, but actually, he is only responsible for the development of the Linux kernel.
Complete Linux system = Kernel + GNU system utilities and libraries + other management scripts + installation scripts.

**What is Shell?**

A shell is a special user program that provides an interface for the user to use operating system services. Shell accepts human-readable commands from users and converts them into something which the kernel can understand. It is a command language interpreter that executes commands read from input devices such as keyboards or from files. The shell gets started when the user logs in or starts the terminal.
Linux Shell
hell is broadly classified into two categories –
* Command Line Shell
*  Graphical shell

   
   ![](https://media.geeksforgeeks.org/wp-content/uploads/18834419_1198504446945937_35839918_n-300x291.png)

**Command Line Shell**

Shell can be accessed by users using a command line interface. A special program called Terminal in Linux/macOS, or Command Prompt in Windows OS is provided to type in the human-readable commands such as “cat”, “ls” etc. and then it is being executed. The result is then displayed on the terminal to the user. A terminal in Ubuntu 16.4 system looks like this-

 ![image](https://github.com/user-attachments/assets/38bcf44d-93ab-4f2a-8299-d120f46176d7)



In the above screenshot “ls” command with “-l” option is executed. It will list all the files in the current working directory in a long listing format.
Working with a command line shell is a bit difficult for beginners because it’s hard to memorize so many commands. It is very powerful; it allows users to store commands in a file and execute them together. This way any repetitive task can be easily automated. These files are usually called batch files in Windows and Shell Scripts in Linux/macOS systems.

**Graphical Shells**

Graphical shells provide means for manipulating programs based on the graphical user interface (GUI), by allowing for operations such as opening, closing, moving, and resizing windows, as well as switching focus between windows. Window OS or Ubuntu OS can be considered as a good example which provides GUI to the user for interacting with the program. Users do not need to type in commands for every action. A typical GUI in the Ubuntu system –

![](https://media.geeksforgeeks.org/wp-content/uploads/GUI-shell.png)

There are several shells are available for Linux systems like –

  * BASH (Bourne Again SHell) – It is the most widely used shell in Linux systems. It is used as default login shell in Linux systems and in macOS. It can also be installed on Windows OS.
  * CSH (C SHell) – The C shell’s syntax and its usage are very similar to the C programming language.
  * KSH (Korn SHell) – The Korn Shell was also the base for the POSIX Shell standard specifications etc.

Each shell does the same job but understands different commands and provides different built-in functions.

**What is a terminal?**

A program which is responsible for providing an interface to a user so that he/she can access the shell. It basically allows users to enter commands and see the output of those commands in a text-based interface. Large scripts that are written to automate and perform complex tasks are executed in the terminal.


To access the terminal, simply search in search box “terminal” and double-click it.

![image](https://github.com/user-attachments/assets/176262a0-346f-4a68-bfa2-0fc78b80edae)

  
   
   
## **Shell Scripting**

Usually, shells are interactive, which means they accept commands as input from users and execute them. However, sometimes we want to execute a bunch of commands routinely, so we have to type in all commands each time in the terminal.

As a shell can also take commands as input from file, we can write these commands in a file and can execute them in shell to avoid this repetitive work. These files are called Shell Scripts or Shell Programs. Shell scripts are similar to the batch file in MS-DOS. Each shell script is saved with `.sh` file extension e.g., myscript.sh.

A shell script has syntax just like any other programming language. If you have any prior experience with any programming language like Python, C/C++ etc. It would be very easy to get started with it.

A shell script comprises the following elements –

* Shell Keywords – if, else, break etc.
* Shell commands – cd, ls, echo, pwd, touch etc.
* Functions
* Control flow – if..then..else, case and shell loops etc.

**why do we need shell scripts?**

There are many reasons to write shell scripts:

* To avoid repetitive work and automation
* System admins use shell scripting for routine backups.
* System monitoring
* Adding new functionality to the shell etc.


   
   
    


    
    


