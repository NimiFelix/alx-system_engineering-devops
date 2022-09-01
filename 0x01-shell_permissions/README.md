su betty  -switches the current user to betty
id -u -n  -prints the username of the current user
groups  -prints all the groups the current user is part of
chown betty hello  -changes the owner of the file hello to betty
touch hello  -creates an empty file hello
chmod u+x hello  -adds execute permission to the owner of the file hello
chmod u+x,g+x,o+r hello  -adds execute permission to the owner and group owner and read permission to other users, to the file hello 
chmod ugo+x hello  -adds execute permission to the owner,group owner and other users to hello
chmod 007 hello  -gives other users all the permissions and none to the owner and group owner of the file hello
chmod 753 hello  -sets the mode of the file hello to -rwxr-x-wx
chmod --reference=olleh hello  -sets the mode of the file hello the same as olleh
chmod -R ugo+x  - adds execute permission to all subdirectories of the current directory for the owner,group owner and all other users
mkdir -m 751 my_dir  -creates a directory with permissions 751 in the working directory
chgrp school hello  -changes the group owner to school of the file hello
