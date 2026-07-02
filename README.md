## Training-Day-2
# Introduction to BASH and Linux Command
1. Shell and Bash
   # Shell
   A shell in Linux is a command-line interpreter that acts as a bridge between the user and the Linux kernel.
It takes commands entered by the user, interprets them, and instructs the operating system to perform the requested tasks.

# Key Functions of a Shell
Command Execution – Runs user commands and programs.
Scripting – Allows automation of tasks using shell scripts.
Input/Output Redirection – Redirects data between files, devices, and commands.
Environment Management – Manages variables, paths, and configurations.
Job Control – Starts, stops, and manages background/foreground processes.
# Types of Shells in Linux
Different shells offer different features and syntax. Common ones include:

Shell Name	Executable	Description
Bourne Shell	sh	Original Unix shell, simple and fast.
Bash (Bourne Again Shell)	bash	Most common shell in Linux, supports scripting and advanced features.
Korn Shell	ksh	Combines features of Bourne and C shells.
C Shell	csh	Syntax similar to C programming language.
Z Shell	zsh	Highly customizable, with advanced completion and scripting features.
# How the Shell Works
User Input – You type a command in the terminal.
Parsing – The shell interprets the command.
Execution – The shell calls the appropriate program or system call.
Output – The result is displayed back to the user.
Interactive vs. Non-Interactive Shell
Interactive Shell – Used when you type commands directly in a terminal.
Non-Interactive Shell – Runs scripts without direct user interaction.
# BASH
Bash (short for Bourne Again Shell) is the default and most widely used command-line interpreter in many Linux distributions. It was developed in 1989 by Brian Fox for the GNU Project as a free replacement for the original Unix sh shell. Bash allows users to interact with the operating system by typing commands, running programs, and automating tasks through scripts.

It serves two main purposes:
Interactive shell – Execute commands directly and get immediate results.
Scripting language – Write .sh files containing sequences of commands to automate repetitive tasks.
2.File system structure
The Linux file system is organized in a tree-like structure. The top-most directory is called the root directory (/). All other directories and files are stored under it.

# 1. Root Directory (/)
It is the top-level directory in Linux.
It contains all other directories and files.
Every file and folder starts from the root directory.
It is represented by a forward slash (/).
# 2. Home Directory (/home)
It contains the personal directories of all users.
Each user has a separate folder inside /home.
Users store their documents, pictures, videos, and other personal files here.
Normal users have permission to modify files in their own home directory.
# 3. Configuration Directory (/etc)
It stores system configuration files.
These files control the settings of the operating system and installed applications.
Only the administrator (root user) usually modifies these files.
It does not contain user data.
# 4. Variable Directory (/var)
It stores files whose contents change frequently.
It contains log files, cache files, mail files, and temporary data created by programs.
Many applications write their logs here.
3.File and Directory permissions(chmod,chown)
# chmod Command
Full Form: Change Mode
The chmod command is used to change the permissions of files and directories.
# chown Command
Full Form: Change Owner
The chown command is used to change the owner of a file or directory.
4.Basic file permission
# 1. ls Command (List Files and Directories)
Definition: The ls command is used to display the files and directories in the current directory.
Syntax:
ls [options] [directory]
# 2. cp Command (Copy Files or Directories)
Definition: The cp command is used to copy files or directories from one location to another.
Syntax:
cp source_file destination
For copying a directory:
cp -r source_directory destination
# 3. mv Command (Move or Rename Files and Directories)
Definition: The mv command is used to move files/directories from one location to another or to rename them.
Syntax:
mv source destination
# 4. rm Command (Remove Files or Directories)
Definition: The rm command is used to delete files or directories.
Syntax:
rm file_name
For deleting a directory:
rm -r directory_name
# 5. mkdir Command (Make Directory)
Definition: The mkdir command is used to create a new directory.
Syntax:
mkdir directory_name
