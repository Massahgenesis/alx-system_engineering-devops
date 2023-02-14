. alias ls="rm *" :The script that that creates an alias.
. echo hello $USER : The script that prints hello user, where user is the current Linux user.
. PATH=$PATH:/action : The script that add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
. ls -lR | grep ^d | wc -l :the script that counts the number of directories in the PATH.
