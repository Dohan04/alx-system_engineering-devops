su betty - to change the user id to betty 
whoami -to print the user id as name
groups - to print all group ids 
chown betty hello - to change the ownership of the file to betty
touch hello  -to create new file called hello
chmod u+x hello - to add excute permition to the owner of the file hello
chmod ug+x,o+r hello - to addexecute  permition to the owner to the group and read permition to other users
chmod ugo+x hello - to give execute permition to all
chmod 007 hello - to set the owner and groupowner permition to none
chmod 753 hello - to set the mode to 753 
chmod --reference=olleh hello - to copy permission from hello
chmod -R a+x ./*/ - to add permition to subdirectorys ot he current directory 
mkdir -m 751 dir_holberton - to create adirectory with permission 751
chgrp holberton hello -  to change the group of the hello file
chown betty:holberton hello - to to change the owner to betty and the group owner to holberon
chown betty:holberton _hello - to change owner and the group owner to -hello to bety and holberton respectively
chown--from=guillaume betty hello - change the owner of file hello to only betty if it is owned by guillaume
 
