        . #!/bin/bash
Means use the bash executable found in /bin.
        . whoami
The command that prints the effective username of the current user.
        . groups
The command that prints all the groups the current user is part of.
        . chown betty hello
The script to change the owner file.
        . touch betty
The command to create an empty file called betty.
        . chmod u+x hello
The script that adds execute permission to the owner of the file hello.
        . chmod ug+x,o+r hello
The script that adds execute permission to the owner and group owner and read permission to the other users.
        . chmod a+x hello
The script Write a script that adds execution permission to the owner, the group owner and the other users, to the file.
        . chmod 007 hello
The script that gives all permissions to the other uses only.
        . chmod 753 hello
The script to give access to the hello file.
        . chmod --reference=olleh hello
The script to give the same permission to the same file.
        . chmod +x */
The script to adds execute permission to all subdirectories of the current directory for the owner,the group owner and all other users.
        . mkdir -m 751 my_dir
The script to create a directory with a specific permission.
        . chgrp school hello
The script to change the group owner to school for the file hello.
        . chown vincent:staff *
The script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
        . chown -h vincent:staff _hello
The script that changes the owner and the group owner of _hello to vincent and staff respectively.
        . chown --from=guillaume betty hello
The script that changes the owner of the file hello to betty only if it is owned by the user guillaume.
        . telnet towel.blinkenlights.nl
The script that that will play the StarWars IV episode in the terminal.
