0 - su betty: Switches the current user to the user betty
1 – whoami: Prints the effective username of the current user.
2 – groups: Prints all the groups the current user is part of.
3 - sudo chown betty hello: Changes the owner of the file hello to the user betty.
4 - touch hello: Creates an empty file called hello.
5 - chmod u+x hello: Adds execute permission to the owner of the file hello.
6 - chmod u+x,g+x,o+r hello: Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7 - chmod ogu+x hello: Adds execution permission to the owner, the group owner and the other users, to the file hello
8 - chmod 007 hello: Sets the permission to the file hello as follows:
	                   Owner: no permission at all
                     Group: no permission at all
                     Other users: all the permissions
9 - chmod 753 hello: Sets the mode of the file hello to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
10 - chmod --reference=olleh hello: Sets the mode of the file hello the same as olleh’s mode.
11 - chmod -R a+X .: Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users, without making changes to                      regular files.
12 - mkdir -m 751 my_dir: Creates a directory called my_dir with permissions 751 in the working directory.
13 - chgrp school hello: Changes the group owner to school for the file hello
