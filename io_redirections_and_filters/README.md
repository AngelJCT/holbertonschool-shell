# Shell, I/O Redirection and filters.

### The Linux operating system has the ability to change standard utput and standar input when executing a command. Standar input refers to the keyboard and standar output to the display (screen).

### Filters take standard input and perform an operation upon it and send the results to standard output.

### Table of contents:
***0-hello_world***

<sub>Write a script that prints “Hello, World”, followed by a new line to the standard output.</sub>

***1-confused_smiley***

<sub>Write a script that displays a confused smiley "(Ôo)'.</sub>

***2-hellofile***

<sub>Display the content of the /etc/passwd file.</sub>

***3-twofiles***

<sub>Display the content of /etc/passwd and /etc/hosts</sub>

***4-lastlines***

<sub>Display the last 10 lines of /etc/passwd<sub>

***5-firstlines***

<sub>Display the first 10 lines of /etc/passwd</sub>

***6-third_line***

<sub>Write a script that displays the third line of the file iacta.</sub>

***7-file***

<sub>Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.</sub>

***8-cwd_state***

<sub>Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.</sub>

***9-duplicate_last_line***

<sub>Write a script that duplicates the last line of the file iacta</sub>

***10-no_more_js***

<sub>Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.</sub>

***11-directories***

<sub>Write a script that counts the number of directories and sub-directories in the current directory. The current and parent directories should not be taken into account. Hidden directories should be counted</sub>

***12-newest_files***

<sub>Create a script that displays the 10 newest files in the current directory. Requirements: One file per line. Sorted from the newest to the oldest.</sub>

***13-unique***

<sub>Create a script that takes a list of words as input and prints only words that appear exactly once. Input format: One line, one word. Output format: One line, one word. Words should be sorted.</sub>

***14-findthatword***

<sub>Display lines containing the pattern “root” from the file /etc/passwd</sub>

***15-countthatword***

<sub>Display the number of lines that contain the pattern “bin” in the file /etc/passwd</sub>

***16-whatsnext***

<sub>Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd</sub>

***17-hidethiswword***

<sub>Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.</sub>

***18-letteronly***

<sub>Display all lines of the file /etc/ssh/sshd_config starting with a letter. Include capital letters as well.</sub>

***19-AZ***

<sub>Replace all characters A and c from input to Z and e respectively.</sub>

***20-hiago***

<sub>Create a script that removes all letters c and C from input.</sub>

***21-reverse***

<sub>Write a script that reverse its input.</sub>

***22-users_and_homes***

<sub>Write a script that displays all users and their home directories, sorted by users.</sub>

***23-empty_casks***

<sub>Write a command that finds all empty files and directories in the current directory and all sub-directories. Only the names of the files and directories should be displayed (not the entire path). Hidden files should be listed. One file name per line. The listing should end with a new line. ou are not allowed to use basename, grep, egrep, fgrep or rgrep.</sub>

***24-gifs***

<sub>Write a script that lists all the files with a .gif extension in the current directory and all its sub-directories. Hidden files should be listed. Only regular files (not directories) should be listed. The names of the files should be displayed without their extensions. The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay). One file name per line. The listing should end with a new line. You are not allowed to use basename, grep, egrep, fgrep or rgrep.</sub>

***25-acrostic***

<sub>Create a script that decodes acrostics that use the first letter of each line. The ‘decoded’ message has to end with a new line.</sub>

***26-the_biggest_fan***

<sub>Write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests. Order by number of requests, most active host or IP at the top.</sub>
