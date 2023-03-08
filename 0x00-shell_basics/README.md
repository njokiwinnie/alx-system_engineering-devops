#!/bin/bash
pwd -print absolute path name of the current directory
ls -display the contents list of your current directory
cd ~  change working directory to user's home directory
ls -l display current directory in long format
ls -la display content of current directory including hidden files in long format
ls -na display current directory content in long format with userand group IDs numerically displayed including all the hidden files
mkdir /tmp/my_first_directory create directory inside another directory
mv /tmp/tmp /tmp/my_first_directory move file betty
rm /tmp/my_first_directory/betty to delete the file betty
rmdir /tmp/my_first_directory to delete directory
cd - to change the working directory to the previous one
ls -la. .. /boot lists files in current directory, parent and /boot in that order and in long format
file /tmp/iamafile print iamafile type of file in /tmp 
ln -s /bin/ls__ls__ to create a symbolic to /bin/ls named __ls__ which is created in the current directory
cp -u *.html ../  to Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working director considering the html extensions
