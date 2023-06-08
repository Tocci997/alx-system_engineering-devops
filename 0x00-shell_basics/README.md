pwd     --  prints the absolute path name of the current working directory.

ls      --  display the contents list of your current directory

cd~     --  changes the working directory to the user’s home directory

ls -l   --  display current directory contents in a long format

ls -al  --  display current directory contents, including hidden files (starting with .)

ls -al  --  Display current directory contents in long format, with hidden files and with user and group IDs displayed numerically

mkdir /tmp/my_first_directory/  --   script that creates a directory named my_first_directory in the /tmp/ directory

mv /tmp/betty /tmp/my_first_directory/betty  --  move the file betty from /tmp/ to /tmp/my_first_directory

rm /tmp/my_first_directory/betty  --  Delete the file betty from /tmp/my_first_directory_

rm -rf /tmp/my_first_directory  --  delete the directory my_first_directory that is in the /tmp directory

cd -  --   script that changes the working directory to the previous one

ls -la . .. /boot  --   script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working                                 directory and the /boot directory (in this order), in long format

file /tmp/iamafile  --   script that prints the type of the file named iamafile

ln -s /bin/ls __ls__  --  create a symbolic link to /bin/ls, named __ls__

cp -u *.htm ..  --  Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of                      the working directory or were newer than the versions in the parent of the working directory
