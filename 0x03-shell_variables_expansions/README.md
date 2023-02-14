. alias ls="rm *" :The script that that creates an alias.
. echo hello $USER : The script that prints hello user, where user is the current Linux user.
. PATH=$PATH:/action : The script that add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
. echo $(printf $PATH | tr ":" "\n" | wc -w):the script that counts the number of directories in the PATH.
. printenv : The script that lists environment variables.
. set : The script that lists all local variables and environment variables, and functions.
. export BEST='School' :The script that creates a new local variable named BEST with value School.
. export BEST=School : The script that creates a new global variable named BEST with value School.

