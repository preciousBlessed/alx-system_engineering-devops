#Shell Permissions
#su betty 
changes betty to another user account

#whoami
to print current user.`

#groups
to print out all the groups the current user belongs to.

#sudo chown betty hello
This command will change the ownership of a file hello to betty.

#touch hello
It creates an empty text file named hello

#chmod u+x hello
It attaches an executable permission to the owner of the file hello.

#chmod u+x,g+x,o+r hello
It adds executable permission to the owner and group owner, and attaches read permission to all other users.

#chmod +x hello
Will add the executable permission to user, group owner and all others.

#chmod 007 hello
removes all permission from owner, and group owner, while it grants all permission to ther users.

#sudo chmod --reference=olleh hello
copies the file permission of olleh to hello

#chmod +x */ or chmod +x . */
Will attach execution rights to all directories in a folder

#mkdir -m 751 my_dir
makes a directory my_dir and gives it permission 751

#chrgp school hello
Changes the ownership on the hello file to the group school

#ADVANCED TASKS

#chown vincent:staff * */
change the owner to vincent and the group to staff for all files and directories.

#chown vincent:staff _hello
Changes the owner to vincent and the group to staff for a file _hello.
