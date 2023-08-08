0- Print Hello world using echo
1- echo "\"(Ôo)'": print special
2- cat /etc/passwd : open file
3- cat /etc/passwd /etc/hosts : two files open
4- tail /etc/passwd : last 10 lines
5- head /etc/passwd : first 10 lines
6- head -3 iacta |tail +3 : the third line of the file iacta.
7- echo 'Best School' > "\*\\\'\"Best School\"\'\\\*\$\?\*\*\*\*\*:)" : naming with special character
8- la -la > ls_cwd_content : overwrite file 
9- tail -1 iacta >> iacta : duplicate last line 
10-find -type f -name "*.js" -delete: delete specific type file with .js
11-find -mindepth 1 -type d |wc -l : count directories and sub except my current and parent
12-ls -1t |head : newest file
13- sort | uniq -u print what is unique
14- grep "root" /etc/passwd : search for pattern root iside the file
15- grep -c "bin" /etc/passwd : count files with pattern bin
16- grep -A 3 "root" /etc/passwd : search for pattern root iside the file and print 3 lines after
17- grep -v "bin" /etc/passwd : get all except bin
18- grep '^[[:alpha:]]' /etc/ssh/sshd_config : get what start with letter 
19-tr 'A' 'Z'|tr 'c' 'e': replace letters
20-tr -d c | tr -d C : delete letters
21-rev : reverse input
22-cut -d ":" -f 1,6 /etc/passwd |sort : select specific field with delimiter : got from man 5 passwd() and diplay sorted user name and home folder

