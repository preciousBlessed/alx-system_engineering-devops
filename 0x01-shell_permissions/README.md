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
