#!bin/bash
su betty to change user to betty
whoami prints th eeffective username of the current user
id -g -n to print all the groups of current user
sudo chown betty hello to change ownership of file hello to user betty
touch hello create empty file
chmod 744 hello to add execute permission to owner
chmod 754 hello to add execute permission to the owner and the group owner and read permission to other users 
chmod 751 hello to add execute permission to the owner and the group owner and read permission toother users
