0 - echo Hello, World: Prints “Hello, World”
1 - echo "(Ôo)': Displays a confused smiley "(Ôo)'.
2 - cat /etc/passwd: Display the content of the /etc/passwd file.
3 - cat /etc/passwd /etc/hosts: Display the content of /etc/passwd and /etc/hosts
4 - tail /etc/passwd: Display the last 10 lines of /etc/passwd
5 - head /etc/passwd: Display the first 10 lines of /etc/passwd
6 - head -n 3 iacta | tail -1: Displays the third line of the file iacta.
7 - echo -e "Best School" >> "\\*\\\\"Best School"\\\\\*$\\?\\*\\*\\*\\*\\*:)": Creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
8 - ls -la > ls_cwd_content: Writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
9 - tail -1 iacta >> iacta: Duplicates the last line of the file iacta
10 - find . -name "*.js" -type f -delete: Deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
11 - find -mindepth 1 -type d | wc -l: Counts the number of directories and sub-directories in the current directory.
•	The current and parent directories should not be taken into account
•	Hidden directories should be counted
12 - ls -t . | head: Displays the 10 newest files in the current directory, one per line and sorted from newest to oldest.
13 - sort | uniq -u: Takes a list of words as input and prints only words that appear exactly once, one word per line and sorted.
14 - egrep root /etc/passwd: Display lines containing the pattern “root” from the file /etc/passwd
15 - egrep -c bin /etc/passwd: Display the number of lines that contain the pattern “bin” in the file /etc/passwd
16 - egrep -A 3 root /etc/passwd: Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
17 - egrep -v bin etc/passwd: Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
18 - egrep ^[[:alpha:]] /etc/ssh/sshd_config: Display all lines of the file /etc/ssh/sshd_config starting with a letter.
19 - tr Ac Ze: Replace all characters A and c from input to Z and e respectively.
20 - tr -d Cc: Create a script that removes all letters c and C from input.
21 – rev: Write a script that reverse its input.
22 - cut -f 1,6 -d : /etc/passwd | sort: Write a script that displays all users and their home directories, sorted by users.
