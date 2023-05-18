0-iam_betty - this script switches the current user to the user betty.

1-who_am_i - this script prints the effective username of the  current user.

2-groups - this script prints all the groups the current user is part of.

3-new_owner - this script changes the owner of the file hello to the user betty.

4-empty - this script that creates an empty file called hello.

5-execute - this script adds execute permission to the owner of the file hello.

6-multiple_permissions - this script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.


7-everybody - this script adds execution permission to the owner, the group owner and the other users, to the file hello.

8-James_Bond - sets the permission to the file hello as follows:

* Owner: no permission at all
* Group: no permission at all
* Other users: all the permissions

 9-John_Doe - a script that sets the mode of the file hello to this:-rwxr-x-wx

 10-mirror_permissions - this script  sets the mode of the file hello the same as olleh’s mode.
* The file hello will be in the working directory
* The file olleh will be in the working directory

11-directories_permissions - this script  that  execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

Regular files should not be changed.

12-directory_permissions - that creates a directory called my_dir with permissions 751 in the working directory.

 13-change_group - this script changes the group owner to school for the file hello

The file hello will be in the working directory

 100-change_owner_and_group - this script changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

   101-symbolic_link_permissions- this script changes the owner and the group owner of _hello to vincent and staff respectively.

The file _hello is in the working directory
The file _hello is a symbolic link.

 102-if_only - this script changes the owner of the file hello to betty only if it is owned by the user guillaume.

* The file hello will be in the working directory