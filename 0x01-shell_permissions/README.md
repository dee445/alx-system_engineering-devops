0-iam_betty switches the current user to the user betty.
1-who_am_i script prints the effective username of the current user.
chmod u+x (filename) script prints all the groups the current user is part of.
Chown betty hello script changes the owner of the file hello to the user betty.
touch hello script creates an empty file called hello.
chmod u+x hello script adds execute permission to the owner of the file hello.
chmod ug+x,o+r hello script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod a+x hello script adds execution permission to the owner, the group owner and the other users, to the file hello.
chmod 007 hello script sets the permission to the file hello as follows; Owner: no permission at all, Group: no permission at all.
chmod 753 hello script sets the mode of the file hello to this:i
chod --reference=olleh hello scriptsets the mode of the file hello the same as olleh’s mode.
chmod -R a+X . script adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
mkdir -m 751 my_dir script creates a directory called my_dir with permissions 751 in the working directory.
chgrp school hello script changes the group owner to school for the file hello.
chown vincent:staff * script changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
chown -h vincent:staff _hello script changes the owner and the group owner of _hello to vincent and staff respectively.
chown --from=guililaume betty hello script changes the owner of the file hello to betty only if it is owned by the user guillaume.
telnet towel.blinkenlights.nl script will play the StarWars IV episode in the terminal.
