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
        . chmod ug+x o+r
The script that adds execute permission to the owner and group owner and read permission to the other users.
        . chmod a+x hello
The script Write a script that adds execution permission to the owner, the group owner and the other users, to the file.
        . chmod ug-rwx o+rwx hello
The script that gives all permissions to the other uses only.
