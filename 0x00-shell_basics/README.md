script-0 pwd: display my current working directory.
script-1 ls: Display the contents list of your current directory.
scipt-2 cd: changes the working directory to the user’s home directory.
script-3 ls -l: Display current directory contents in a long format.
script-4 ls -al: Display current directory contents, including hidden files (starting with .). Use the long format.
script-5 ls -na: Display current directory contents.
Long format
with user and group IDs displayed numerically
And hidden files (starting with .).
script-6 mkdir /tmp/my_first_directory/ : Create a script that creates a directory named my_first_directory in the /tmp/ directory.
script-7 mv : Move the file betty from /tmp/ to /tmp/my_first_directory.
script-8 rm : The file betty is in /tmp/my_first_directory
script-9 rm -r : Delete the directory my_first_directory that is in the /tmp directory. 
script-10 cd - : Write a script that changes the working directory to the previous one.
script-11 ls -al .. : Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
script-12 file : Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
script-13 ln -s : Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
script-14 cp -ur *.html : Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
script-15 mv [[:upper:]]* : Create a script that moves all files beginning with an uppercase letter.
script-16 rm -r *~ : Create a script that deletes all files in the current working directory that end with the character ~.
script-17 mkdir -p : Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
script-18 ls -xamp : Write a command that lists all the files and directories of the current directory, separated by commas (,).
script-19 !:mime : Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
