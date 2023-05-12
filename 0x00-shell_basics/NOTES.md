
## My readme file on 0x00-shell_basics directory
#  Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
# General
## What does RTFM mean?
Read The Fucking Manual
## What is a Shebang
A shebang, also known as a hashbang or a pound bang, is a special character sequence at the beginning of a script file in Unix-like operating systems that specifies the interpreter to be used for executing the script. The shebang is represented by the characters #! followed by the path to the interpreter that will be used to execute the script.
## What is the Shell
Simply put, the shell is a program that takes commands from the keyboard and gives them to the operating system to perform.
## What is a terminal
It's a program called a terminal emulator. This is a program that opens a window and lets you interact with the shell.
## What is the difference between a terminal and a shell
the terminal is the user interface program that allows users to interact with the operating system, while the shell is the program that interprets and executes commands entered by the user. The terminal and the shell work together to provide a powerful and flexible environment for users to work in.
## What is the shell prompt
The shell prompt is the text displayed in the command-line interface of a shell, indicating that the shell is ready to receive input from the user. The prompt typically consists of a short string of characters, such as a dollar sign ($), a hash symbol (#), or the name of the user or host machine, followed by a space. The prompt may also contain other information, such as the current working directory, time, or date.
## How to use the history (the basics)
the up-arrow key to view command history
# Navigation
What do the commands or built-ins cd, pwd, ls do
How to navigate the filesystem
What are the . and .. directories
What is the working directory, how to print it and how to change it
What is the root directory
What is the home directory, and how to go there
What is the difference between the root directory and the home directory of the user root
What are the characteristics of hidden files and how to list them
What does the command cd - do
# man or help:
1. *ls*: This command is used to list the contents of a directory. When you enter ls in the terminal, it will show you the files and folders in the current directory.
2. *pwd*: This command stands for "print working directory". It is used to display the current directory you are working in.
3. *less*: This command is used to view the contents of a file one page at a time. It is similar to the more command, but with more advanced features such as searching and navigation.
4. *file*: This command is used to determine the type of a file. When you enter file followed by the name of a file, it will display information about the file, such as its type and format.
5. *ln*: This command is used to create links between files or directories. There are two types of links: hard links and symbolic links. Hard links create a second reference to the same file on the file system, while symbolic links create a shortcut to another file or directory.
6. *cp*: This command is used to copy files or directories from one location to another. When you enter cp followed by the name of a file and the destination path, it will create a copy of the file in the specified location.
7. *mv*: This command is used to move files or directories from one location to another. When you enter mv followed by the name of a file and the destination path, it will move the file to the specified location.
8. *rm*: This command is used to remove files or directories from the file system. When you enter rm followed by the name of a file, it will permanently delete the file from the file system.
9. *mkdir*: This command is used to create a new directory. When you enter mkdir followed by the name of the new directory, it will create a new directory in the current working directory.
10. *type*: This command is used to display information about a command. When you enter type followed by the name of a command, it will display information about the command, such as its type and location on the file system.
11. *which*: This command is used to display the location of a command on the file system. When you enter which followed by the name of a command, it will display the full path to the command.
12. *help*: This command is used to display help information for a command. When you enter help followed by the name of a command, it will display a brief summary of the command and its options.
man: This command is used to display the manual pages for a command. When you enter man followed by the name of a command, it will display a detailed description of the command, its options, and usage examples.
# Looking Around
What do the commands ls, less, file do
How do you use options and arguments with commands
Understand the ls long format and how to display it
A Guided Tour \*link
What does the ln command do
What do you find in the most common/important directories
What is a symbolic link
What is a hard link
What is the difference between a hard link and a symbolic link
# Manipulating Files \*
What do the commands cp, mv, rm, mkdir do
What are wildcards and how do they work
How to use wildcards
# Working with Commands
What do type, which, help, man commands do
What are the different kinds of commands
What is an alias
When do you use the command help instead of man
# Reading Man Pages
How to read a man page
What are man page sections
What are the section numbers for User commands, System calls and Library functions
# Keyboard Shortcuts for Bash
Common shortcuts for Bash
# LTS
What does LTS mean?
# Copyright - Plagiarism
You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
You are not allowed to publish any content of this project.
Any form of plagiarism is strictly forbidden and will result in removal from the program.
# Requirements
## General
Allowed editors: vi, vim, emacs
All your scripts will be tested on Ubuntu 20.04 LTS
All your scripts should be exactly two lines long ($ wc -l file should print 2)
All your files should end with a new line (why?)
The first line of all your files should be exactly #!/bin/bash
A README.md file at the root of the repo, containing a description of the repository
A README.md file, at the root of the folder of this project, describing what each script is doing
You are not allowed to use backticks, &&, || or ;
All your scripts must be executable. To make your file executable, use the chmod command: chmod u+x file. Later, we’ll learn more about how to utilize this command.


