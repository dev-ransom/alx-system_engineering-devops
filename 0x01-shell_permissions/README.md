shell permissions
0-iam_betty - su betty
* Create a script that switches the current user to the user betty.

You should use exactly 8 characters for your command (+1 character for the new line)
You can assume that the user betty will exist when we will run your script
1-who_am_i - whoami
* Write a script that prints the effective username of the current user.
2-groups - groups
* Write a script that prints all the groups the current user is part of.
3-new_owner - chown
* Write a script that changes the owner of the file hello to the user betty
4-empty - touch hello
* Write a script that creates an empty file called hello.
5-execute - chmod u+x hello 
* Write a script that adds execute permission to the owner of the file hello.

The file hello will be in the working directory
6-multiple_permissions - chmod ug+x
* Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

The file hello will be in the working directory
7-everybody - chmod ugo+x hello
* Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello
The file hello will be in the working directory
You are not allowed to use commas for this script
8-James_Bond - chmod 007 hello
* Write a script that sets the permission to the file hello as follows:

Owner: no permission at all
Group: no permission at all
Other users: all the permissions
The file hello will be in the working directory You are not allowed to use commas for this script

9-John_Doe - chmod 753 hello
* Write a script that sets the mode of the file hello to this:

-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
The file hello will be in the working directory
You are not allowed to use commas for this script
10-mirror_permissions
* Write a script that sets the mode of the file hello the same as olleh’s mode.

The file hello will be in the working directory
The file olleh will be in the working directory
11-directories_permissions
* Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

Regular files should not be changed.
12-directory_permissions - mkdir -m 751 my_dir
* Create a script that creates a directory called my_dir with permissions 751 in the working directory.
13-change_group - chgrp school hello
* Write a script that changes the group owner to school for the file hello

The file hello will be in the working directory
100-change_owner_and_group - chown vincent:staff

