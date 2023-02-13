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
. grep -B 4 "games" /etc/passwd : The script that displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
