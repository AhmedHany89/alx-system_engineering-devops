Shell Permission Tasks
0- su betty : change current user to betty
1- whomai : display current username
2- id -nG : print name only for all groups user is within
3- sudo chown betty hello : changes the owner of the file hello to the user betty using superuser privilege
4- touch hello : create empty file hello
5- chmod u+x hello : adds execute permission to the owner of the file hello.
6- chmod u+x,g+x,o+r hello : adds execute permission to the owner and the group owner, and read permission to other users, to the file hello

7- chmod a+x hello : adds execution permission to the owner, the group owner and the other users, to the file hello
8- chmod 007 hello :
    Owner: no permission at all
    Group: no permission at all
    Other users: all the permissions
9- chmod 753 hello: -rwxr-x-wx
10-chmod --reference=olleh hello : mirror olleh permission to hello
11-chmod -R a+X . : reate a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users .Regular files should not be changed
12-mkdir -m 751 my_dir :creates a directory called my_dir with permissions 751 in the working directory
13-chgrp school hello: changes the group owner to school for the file hello
