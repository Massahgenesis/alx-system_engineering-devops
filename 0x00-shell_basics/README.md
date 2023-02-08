     . #!/bin/bash
 A script  #!/bin/bash on the first line,  means that the script should always be run with bash, rather than another shell.
     . pwd
 A script that prints the absolute path name of the current working directory.
    . ls
Is the command use to display the content of directory.
    . cd
Is the command use to change the working directory to our home.
    . ls -l
Is the command use to display curent directory in long format.
    . ls -la
Is use to display current directory including hidden file.
    . ls -na
The command use to display current directory with long format,with user, group IDs display numerically and hidden dot files.
    . mkdir /tmp/my_first_directory 
I use the mkdir command to create a diretcory in the tmp directory.
    . mv /tmp/betty /tmp/my_first_directory
This is the script to moov a file from tmp to a new directory in tmp.
    . rm /tmp/my_first_directory/betty
The script to delete betty file in the directory.
    . rmdir /tmp/my_first_directory
The script to delete the first directory in tmp directory.
    . cd -
The command to change the working directory to the previous.
    . ls -la . .. /boot
The command to list the directory boot content.
    . file /tmp/aimafile
The script to print the type of the file named aimafile.
    . ln -s /bin/ls __ls__
The script create a symbolic link to /bin/ls, named __ls__.This symbolic link is created in the current working directory.
    . cp -u *html ..
The script to copy all files with extension html.
    . mv [A-Z]* /tmp/u
The script to create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
    . rm *~
The script to create a script that deletes all files in the current working directory that end with the character ~.
    .mkdir -p welcome/to/school
 The script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
