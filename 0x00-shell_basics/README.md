0-current_working_directory - pwd
* Write a script that prints the absolute path name of the current working directory
1-listit - ls
* Display the contents list of your current directory
2-bring_me_home - cd
* Write a script that changes the working directory to the user’s home directory
3-listfiles - ls -l
* Display current directory contents in a long format
4-listmorefiles - ls -la 
* Display current directory contents, including hidden files (starting with .). Use the long format
5-listfilesdigitonly - ls -la
* Display current directory contents.

Long format
with user and group IDs displayed numerically
And hidden files (starting with .) 
6-firstdirectory - mkdir /tmp/my_first_directory
* Create a script that creates a directory named my_first_directory in the /tmp/ directory
7-movethatfile - mv /tmp/ betty /tmp/my_first_directory
* Move the file betty from /tmp/ to /tmp/my_first_directory
8-firstdelete - rm /tmp/my_first_directory
* Delete the file betty.

The file betty is in /tmp/my_first_directory
9-firstdirdeletion - rm -r /tmp/my_first_directory
* Delete the directory my_first_directory that is in the /tmp directory
10-back - cd -
* Write a script that changes the working directory to the previous one
11-lists -ls -la . .. /boot
* Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format
