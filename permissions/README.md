# Shell Permissions

### File permissions are use to control the access level that the system processes. Each file and directories is assigned access rights for the owner of the file, the members of a group. besides being able to change permissions of a file or a directory and the ownership of it, controlingthe access is important to avoid unnecessary changes and errors in its content.

### In this project we will be working with permissions and how each different command works.
### Table of content:

***0) 0-iam_betty***

<sub>Create a script that switches the current user to the user betty.</sub>

***1) 1-who_am_i***

<sub>Write a script that prints the effective username of the current user.</sub>

***2) 2-groups***

<sub>Write a script that prints all the groups the current user is part of.</sub>

***3) 3-new_owner***

<sub>Write a script that changes the owner of the file hello to the user betty.</sub>

***4) 4-empty***

<sub>Write a script that creates an empty file called hello.</sub>

***5) 5-execute***

<sub>Write a script that adds execute permission to the owner of the file hello.</sub>

***6) 6-multiple_permissions***

<sub>Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.</sub>

***7) 7-everybody***

<sub>Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello</sub>

***8) 8-James_Bond***

<sub>Write a script that sets the permission to the file hello as follows: Owner: no permission at all, Group: no permission at all, Other users: all the permissions.</sub>

***9) 9-John_Doe***

<sub>Write a script that sets the mode of the file hello to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello</sub>

***10) 10-mirror_permissions***

<sub>Write a script that sets the mode of the file hello the same as olleh’s mode.</sub>

**11) 11-directories_permissions***

<sub>Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.</sub>

***12) 12-directory_permissions***

<sub>Create a script that creates a directory called my_dir with permissions 751 in the working directory.</sub>

***13) 13-change_group***

<sub>Write a script that changes the group owner to school for the file hello</sub>

***14) 14-change_owner_and_group***

<sub>Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.</sub>

***15) 15-symbolic_link_permissions***

<sub>rite a script that changes the owner and the group owner of _hello to vincent and staff respectively.</sub>

***16) 16-if_only***

<sub>Write a script that changes the owner of the file hello to vincent only if it is owned by the user guillaume.</sub>
