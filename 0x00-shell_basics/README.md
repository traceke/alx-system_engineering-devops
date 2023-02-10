This folder shall list each script in this directory and their function

0. Current working directory --> prints the absolute path name of the current working directory.

1. List it --> displays the contents list of your current directory.

2. Bring me home -->  a script that changes the working directory to the user’s home directory.

3. List files --> displays current directory contents in a long format

4. List more files --> displays current directory contents, including hidden files (starting with .). Use the long format.

5. List files digit only --> displays current directory contents with long format, user and group IDs displayed numerically and hidden files (starting with .)

6. First directory -->  a script that creates a directory named my-first-directory in the /tmp/ directory.

7. Move that file --> a script that moves  the file betty from /tmp/ to /tmp/my-first-directory.

8. First Delete --> a script that deletes the file betty

9. First Dir Deletion --> a script that deletes the directory my-first-directory that is in the /tmp directory.

10. Back --> a script that changes the working directory to the previous one.

11. Lists --> a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

12. File type --> a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

13. Symbolic Link --> creates a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

14. Copy HTML --> a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

15. Let's move --> a script that moves all files beginning with an uppercase letter to the directory /tmp/u.

16. Clean Emacs --> a script that deletes all files in the current working directory that end with the character ~.

17. Tree --> Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

18. Commas --> a command that lists all the files and directories of the current directory, separated by commas (,).

19. School magic file --> a script that creates a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.

	--> to complete (19) create a regular school file that contains the command		0 string SCHOOL school data
	     !:mime School data
	--> 0 stands for the offset, string indicates what type of variable the file should contain, SCHOOL is the string that must be contained in the any files detected and School data is the message that should be printed when a school file is detected.
	--> after creating this file, run a magic (compilation) command to creeate the magic file
	--> file -C -m school.mgc -- to compile it and;
	--> file -m school.mgc -- to use it

