# echo "Hello, World"
* prints out hello world, followed by a newline to the standard output

# echo "\"(Ôo)'"
* prints the confused smiley "(Ôo)'

# cat /etc/passwd
* displays the content of the file passwd

# cat /etc/passwd /etc/hosts
* displays the contents of the two files passwd and hosts.

# tail /etc/passwd
* displays the last 10 lines of the passwd file.

# head /etc/passwd
* displays the first 10 lines of the passed file.

# head -3 iacta | tail +3
* To display the 3rd line of a file
* head -n file | tail +n will display the n-th line of a file named file

#File creation

# ls -la > ls_cwd_content
* will save the current state of tbe directorry in the file named ls_cwd_content

# tail -1 iacta >> iacta
* this will ducplicate the last line of the file called iacta.


# find . -type f -name "*.js" -exec  rm {} +
* to remove all the javaScript files in the current and subdirectorie...

# find . -mindepth 1 -type d -print | wc -l
* will count all the directory and subdirectories excluding the current directry in the current directory.

# ls -t | head
* displays the first 10 newest files in a directory.

# sort list | uniq -u
* displays a list of unrepeatd lines

# grep "root" /etc/passwd
* to find all the lines where the expression "root" occurs.

# grep -c "bin" /etc/passwd
* will count the number of lines that have the pattern "bin"

# grep -A 3 "root" /etc/passwd
* Will display the matched line and 3 lines after (-B) for before.

# grep -v "bin" /etc/passwd
* Will show all lines without the pattern "bin"

# grep -i "^[:alpha:]" /etc/ssh/sshd_config
* displays line starting with a letter including capital letters.

# tr "A,c" "Z,e"
* will replace all "A" with "Z" and "c" with "e".

# tr -d "C,c"
* will remove "C" and "c" occurences from input.

# rev
* to reverse the string from standard input.

# sort /etc/passwd
* to sort all the items in etc/passwd by users (character precedence).

# find . -empty
* to find all empty files and sub-directories in the current directory.

# find . -type f -name "*.gif" | rev | cut -d"/" -f1 | cut -d"." -f2 | rev | sort
* to extract only the file  names for all gif files.
