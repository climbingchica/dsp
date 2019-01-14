# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > 
ls:    Lists files and folders in the current directory
pwd:   Print working directory - outputs name of directory that you are currently working in
cd {folder name}:       Change directory - takes directory name as argument
   cd ..:               navigates up folder
   cd ../{folder name}  change directory (same level as opposed to using just cd)
mkdir {folder name}:    makes a new directory named /folder name
touch filename.txt      Creates new file named filename.txt in current directory

echo "Hello Command Line" >> hello_cli.txt  creates new file with Hello Command Line text
cat hello_cli.txt                           prints contexts of hello_cli.txt

Copying a file from one directory to another
cp:   Copies files or directories
      Copy files to another file - name of file to another name of file
      Copy files to directory - name of file(s) as first arguments (can be multiple files), directory as last argument
cp * directory_name/
      Copy all files into directory
cp m*.txt diectory_name/  Copies all files in working directory that start with 'm' and ending in '.txt' into directory 

Moving files
mv filename.txt directory_name/

Renaming a file
mv filename1.txt filename2.txt   old file as first argument, next file name as second argument

Deleting files and directories
rm filename.txt
rm directory_name/
rm -r directory_name/  -r modifies behavior of rm command, "recursive" removes directory and child directories
rm -rf 

Redirection
cat oceans.txt > continents.txt  takes output to left of '>', redirects it to the file on the right
               >>                appends the data instead of replacing it
sort lakes.txt    orders in alphabetical order
uniq deserts.txt  filters out duplicate lines


---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > 
ls:    Lists files and folders in the current directory
ls -a: Lists files and directories starting with '.' - these files are hidden
ls -l: Lists in long format
ls -t: Orders files and directories by time they were last modified


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 
ls -alt:  lists all contents, including hidden files and directories, in long format, ordered by the date and time they were last modified.
---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > REPLACE THIS TEXT WITH YOUR RESPONSE

 

