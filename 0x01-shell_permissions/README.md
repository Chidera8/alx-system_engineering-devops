Q0: This script switches the current user to the user betty: su betty

Q1:This script to prints the effective username of the current user: id -un

Q2: This script prints all the groups the current user is part of: id -Gn

Q3: This script changes the owner of the file hello to the user betty: chown betty hello 

Q4: This script creates an empty file called hello: touch hello

Q5: This script adds execute permission to the owner of the file hello: chmod u+x hello

Q6: This script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello: chmod ug+x,o+r hello

Q7: This script adds execution permission to the owner, the group owner and the other users, to the file hello: chmod ugo+x hello

Q8: This script sets the permission to the file hello as follows:
Owner: no permission at all, Group: no permission at all, Other users: all the permissions; chmod 007 hello

Q9: This script sets the mode of the file hello to ...: chmod 753 hello

Q10: This script sets the mode of the file hello the same as olleh’s mode: chmod --reference=olleh hello

Q11: This script adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users: chmod -R +X .

Q12: This script creates a directory called my_dir with permissions 751 in the working directory: mkdir -m 751 my_dir

Q13: This script changes the group owner to school for the file hello: chgrp school hello

Q14: This script changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.: chown vincent:staff *

Q15: This script changes the owner and the group owner of _hello to vincent and staff respectively: chown -h vincent:staff _hello

Q16: This script changes the owner of the file hello to betty only if it is owned by the user guillaume: chown --from=guillaume betty hello

Q17: This script will play the StarWars IV episode in the terminal: telnet towel.blinkenlights.nl

