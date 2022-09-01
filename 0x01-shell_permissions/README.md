0-iam_betty switches the current user to the user betty.
1-who_am_i script prints the effective username of the current user.
chmod u+x (filename) script prints all the groups the current user is part of.
Chown betty hello script changes the owner of the file hello to the user betty.
touch hello script creates an empty file called hello.
chmod u+x hello script adds execute permission to the owner of the file hello.
chmod ug+x,o+r hello script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod a+x hello script adds execution permission to the owner, the group owner and the other users, to the file hello.
chmod 007 hello script sets the permission to the file hello as follows; Owner: no permission at all, Group: no permission at all.
chmod 753 hello script sets the mode of the file hello to this: 
