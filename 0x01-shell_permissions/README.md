This script switches the current user to the user betty: su betty
Script to prints the effective username of the current user: id -un
This script prints all the groups the current user is part of: id -Gn
This script changes the owner of the file hello to the user betty: chown betty hello 
This script creates an empty file called hello: touch hello
This script adds execute permission to the owner of the file hello: chmod u+x hello
This script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello: chmod ug+x,o+r hello
This script adds execution permission to the owner, the group owner and the other users, to the file hello: chmod ugo+x hello
This script sets the permission to the file hello as follows:
Owner: no permission at all, Group: no permission at all, Other users: all the permissions; chmod 007 hello
This script sets the mode of the file hello to ...: chmod 753 hello
This script sets the mode of the file hello the same as olleh’s mode: chmod --reference=olleh hello
This script adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users: chmod -R +X .
This script creates a directory called my_dir with permissions 751 in the working directory: mkdir -m 751 my_dir

This script changes the group owner to school for the file hello: chgrp school hello

This script changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.: chown vincent:staff *

This script changes the owner and the group owner of _hello to vincent and staff respectively: chown -h vincent:staff _hello


