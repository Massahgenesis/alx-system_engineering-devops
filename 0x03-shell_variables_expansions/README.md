. alias ls="rm *" :The script that that creates an alias.
. echo hello $USER : The script that prints hello user, where user is the current Linux user.
. PATH=$PATH:/action : The script that add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
. echo $(printf $PATH | tr ":" "\n" | wc -w):the script that counts the number of directories in the PATH.
. printenv : The script that lists environment variables.
. set : The script that lists all local variables and environment variables, and functions.
. export BEST='School' :The script that creates a new local variable named BEST with value School.
. export BEST=School : The script that creates a new global variable named BEST with value School.
. echo $(($TRUEKNOWLEDGE+128)) :The script that that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
. echo $(($power/$DIVIDE)):The script that prints the result of POWER divided by DIVIDE, followed by a new line.
. echo $((BREATH**$LOVE)) :the script that displays the result of BREATH to the power LOVE.
. $((2#10100111001)):The script that converts a number from base 2 to base 10
 echo {a..z}{a..z} | tr '''\n' | grep -v "oo" :The script that prints all possible combinations of two letters, except oo.
