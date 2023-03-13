# SHELL I/O REDIRECTIONS
0. echo 'Hello, World'  to print it
1. echo '"(Ôo)'' to print confused smiley
2. cat filename1 filename 2 displays content of both files at once
3. cat /etc/passwd to display the content of /etc/passwd file
4. tail -n 10 etc/passwod prints the last 10 lines in a file
5. head -n 10 /etc/passwd prints the first 10 lines in a file
6. head -n 3 filename | tail -n 1 filename displays the second line without using sed
7. echo "Best school" special characterfile to create a file
8. ls -la > filename redirect the conent of the directory on the file
9. tail -n 1 filename  >> filenameme duplicates the last line of filename into filename
10. find . -type f name "*.js" -delete to  deletes all the regular files with .js extention which are present in the current directory and its subfolders(-typef is for normal file .
11. find . -type d -not -name "." |wc-l to count the number od directories and sub directories(-type d specifies directories ,-not -name negates the request, "." requeast to be negated, wc-1 word count
12. 
