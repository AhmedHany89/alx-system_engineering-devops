pwd: print working directory

ls: list what are inside current directory

cd: change directory to home

ls -l: list what are inside current directory in long format

ls -la: list what are inside current directory in long format including hidden files

ls -lna: list what are inside current directory in long format including hidden files with user and group IDs

mkdir: make directory

mv: move file

rm: remove file

rm -r: remove recursive folder

cd - : change directory to previous one

ls -la ./ ../ /boot :lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format

file /tmp/iamafile: list type of iamafile

ln -s /bin/ls __ls__ : make symbolic link __ls__ for ls file

cp -u *.html ../: copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

mv [[:upper:]]* /tmp/u: moves all files beginning with an uppercase letter to the directory /tmp/u.

