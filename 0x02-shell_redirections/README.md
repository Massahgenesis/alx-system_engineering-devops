#!/bin/bash
is a shebang line used in script files to set bash
. echo Hello, World :The script to print Hello world.
. echo "\"(Ôo)'" :The script to print confused smiley.
. cat /etc/passwd : The script to display the content of a file.
. cat /etc/passwd /etc/hosts :The script to display two files contents.
. tail /etc/passwd : The script to display the ten last line of the file passwwd.
. head /etc/passwd : The script to display the ten first line of the file passwd.
. head -n 3 iacta | tail -1 : The script to display the 3rd line of iacta file.
. echo "Best School" > "\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)" :The script to create a file named with caracters containing text.
. ls -la > ls_cwd_content : The script that writes into the file ls_cwd_content the result of the command ls -la.
. tail -1 iacta >> iacta : The script to duplicate the last line of file.
. find -name "*.js" -type f -delete :The script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
. find -mindepth 1 -type d | wc -l : The script that counts the number of directories and sub-directories in the current directory.
. ls -lt | head : The script that displays the 10 newest files in the current directory.
. sort | uniq -u :The script that takes a list of words as input and prints only words that appear exactly once.
. grep root /etc/passwd :The script that displays  lines containing the pattern “root” from the file /etc/passwd.
. grep -c bin /etc/passwd :The script that displays the number of lines that contain the pattern “bin” in the file /etc/passwd.
. grep root /etc/passwd --after-context=3 : The script that displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
. grep -v bin /etc/passwd :The script that displays all the lines in the file /etc/passwd that do not contain the pattern “bin”.
. grep '^[[:alpha:]]' /etc/ssh/sshd_config :The script that displays all lines of the file /etc/ssh/sshd_config starting with a letter.
. tr Ac Ze : The sccrit that replace all characters A and c from input to Z and e respectively.
. tr -d cC : The script that create a script that removes all letters c and C from input.
. rev : The script that write a script that reverse its input.
. cut -d":" -f 1,6 /etc/passwd | sort : The script that displays all users and their home directories, sorted by users.
. find ./ -type fd -empty :The script that contain a command that finds all empty files and directories in the current directory.
. find . -type f -name "*.gif" -printf "%f\n"| rev | cut -d '.' -f2- | rev | LC_ALL=C sort -f : The script that lists all the files with a .gif extension in the current directory and all its sub-directories.
. tail -n +2 | cut -f1 | sort | uniq -c | sort -nr -k 1,1 | cut -c 9- | head -11 :The script parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
