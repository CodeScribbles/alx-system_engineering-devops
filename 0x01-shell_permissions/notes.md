# 0x01. Shell, permissions

## About Bash projects

## Resources

### Read or watch:

Permissions

* permissions refer to the access rights assigned to files and directories. These permissions determine who can read, write, or execute a particular file or directory.

* In Unix-like systems, permissions are represented by a set of three characters for each of the following categories: user, group, and others. The three characters typically used are "r" for read, "w" for write, and "x" for execute.

 ### Here's a breakdown of the permission categories:

**User (Owner)** The permissions assigned to the user who owns the file or directory.
**Group** The permissions assigned to a group of users who share certain access rights.
**Others** The permissions assigned to all other users who are not the owner or part of the group.
Each category has its own set of permissions, and they can be combined to represent the overall permission set for a file or directory. 

### The possible permissions are:

**Read (r)** Allows reading the content of a file or viewing the names of files in a directory.
Write (w): Allows modifying the content of a file or creating, deleting, or renaming files in a directory.
**Execute (x)** Allows executing a file as a program or accessing files within a directory.

* The permissions are represented using a 10-character string. The first character indicates the file type (e.g., "-" for a regular file, "d" for a directory), and the next three characters represent the *owner's permissions*, followed by the *group's permissions*, and finally, *the permissions for others*.

* For example, the permission string "rw-r--r--" means that the owner has read and write permissions, while the group and others have only read permissions.

### man or help:

# chmod
**chmod** The chmod command is used to change the permissions of files and directories in Unix-like operating systems. It allows you to specify who can read, write, and execute a file. The command uses a numeric or symbolic notation to specify the permissions.

# sudo
**sudo** The sudo command stands for "superuser do." It allows a user with the necessary permissions to execute a command as another user, typically the root user (superuser) who has administrative privileges. By using sudo, regular users can perform tasks that require elevated privileges, such as system administration tasks or installing software.

# su
**su** The su command stands for "switch user" or "substitute user." It allows you to switch to another user account without logging out. By default, if you don't specify a username, it will attempt to switch to the root user. You'll be prompted to enter the password of the user you're switching to. su is often used to gain administrative privileges temporarily.

# chown
**chown** The chown command is used to change the ownership of files and directories. It allows you to assign ownership to a specific user or group. Only the root user or the file's current owner can use chown to change ownership. This command is often used when transferring files or when multiple users need access to specific files.

1. chgrp
**chgrp** The chgrp command is used to change the group ownership of files and directories. It allows you to assign ownership to a specific group. Similar to chown, only the root user or the file's current owner can use chgrp to change the group ownership. Changing the group ownership allows a specific group of users to access files collectively.

# id
**id** The id command displays information about the current user, such as the user ID (UID) and the group ID (GID). It also shows the groups the user belongs to.
 
# groups
**groups** The groups command shows the groups a user belongs to. It lists all the groups associated with the user's account.

# whoami
**whoami** The whoami command displays the username of the currently logged-in user. It is a quick way to determine the current user's identity.

# adduser
**adduser** The adduser command is used to create a new user account in Unix-like systems. It prompts for various details about the user, such as username, password, full name, and more. It also creates a home directory and sets up the initial user environment.

# useradd
**useradd** The useradd command is used to create a new user account from the command line in Unix-like systems. It creates the user's account without any prompts and with default settings. It does not create a home directory or set up the initial user environment.

# addgroup
**addgroup** The addgroup command is used to create a new group in Unix-like systems. It allows you to create a new group and specify its name and GID. Groups are used to collectively manage access to files and resources.


## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, *without the help of Google*

### Permissions


# What do the commands chmod, sudo, su, chown, chgrp do

**chmod** The chmod command is used to change the permissions of files and directories in Linux. It allows you to specify who can read, write, and execute a file. The permissions can be modified for the owner of the file, the group associated with the file, and others (everyone else). The command uses a numeric or symbolic notation to specify the permissions.
Linux file permissions
How to represent each of the three sets of permissions (owner, group, and other) as a single digit
How to change permissions, owner and group of a file
Why can’t a normal user chown a file
How to run a command with root privileges
How to change user ID or become superuser

sudo: The sudo command stands for "superuser do." It allows a user with the necessary permissions to execute a command as another user, typically the root user (superuser) who has administrative privileges. By using sudo, regular users can perform tasks that require elevated privileges, such as system administration tasks or installing software.

su: The su command stands for "switch user" or "substitute user." It allows you to switch to another user account without logging out. By default, if you don't specify a username, it will attempt to switch to the root user. You'll be prompted to enter the password of the user you're switching to. su is often used to gain administrative privileges temporarily.

chown: The chown command is used to change the ownership of files and directories in Linux. It allows you to assign ownership to a specific user or group. Only the root user or the file's current owner can use chown to change ownership. This command is often used when transferring files or when multiple users need access to specific files.

chgrp: The chgrp command is used to change the group ownership of files and directories in Linux. It allows you to assign ownership to a specific group. Similar to chown, only the root user or the file's current owner can use chgrp to change the group ownership. Changing the group ownership allows a specific group of users to access files collectively.

# Linux file permissions
# How to represent each of the three sets of permissions (owner, group, and other) as a single digit
# How to change permissions, owner and group of a file
# Why can’t a normal user chown a file
# How to run a command with root privileges
# How to change user ID or become superuser