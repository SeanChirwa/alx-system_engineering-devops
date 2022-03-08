well this is a README.md file for shell redirections

Below are explanations for each script



Script 0 : a script that prints “Hello, World”, followed by a new line to the standard output

Script 1 :  a script that displays a confused smiley "(Ôo)'

Script 2 : Display the content of the /etc/passwd file.

Script 3 : Display the content of /etc/passwd and /etc/hosts

Script 4 : Display the last 10 lines of /etc/passwd

Script 5 : Display the first 10 lines of /etc/passwd

Script 6 : Write a script that displays the third line of the file iacta.

The file iacta will be in the working directory

You’re not allowed to use sed

Script 7 : shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line

Script 8 : a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

Script 9 : Write a script that duplicates the last line of the file iacta

The file iacta will be in the working directory

Script 10 :  a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

Script 11 : Write a script that counts the number of directories and sub-directories in the current directory.

The current and parent directories should not be taken into account
Hidden directories should be counted

Script 12 : Create a script that displays the 10 newest files in the current directory.

Requirements:

One file per line
Sorted from the newest to the oldest

Script 13 : Create a script that takes a list of words as input and prints only words that appear exactly once.

Input format: One line, one word
Output format: One line, one word
Words should be sorted

Script 14 : Display lines containing the pattern “root” from the file /etc/passwd

Script 15 : Display the number of lines that contain the pattern “bin” in the file /etc/passwd

Script 16 : Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

Script 17 : Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.

Script 18 : Display all lines of the file /etc/ssh/sshd_config starting with a letter.

Script 19 : Replace all characters A and c from input to Z and e respectively

Script 20 : a script that removes all letters c and C from input.

Script 21 :  a script that reverse its input.

Script 22 : a script that displays all users and their home directories, sorted by users.

Based on the the /etc/passwd file

Script 23 : a command that finds all empty files and directories in the current directory and all sub-directories

Script 24 : a script that lists all the files with a .gif extension in the current directory and all its sub-directories.

Script 25 : a script that decodes acrostics that use the first letter of each lin

Script 26 :  a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.

Order by number of requests, most active host or IP at the top
You are not allowed to use grep, egrep, fgrep or rgrep
Format:

host    When possible, the hostname making the request. Uses the IP address if the hostname was unavailable.
logname Unused, always -
time    In seconds, since 1970
method  HTTP method: GET, HEAD, or POST
url Requested path
response    HTTP response code
bytes   Number of bytes in the reply


