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

> 1. `ls` - show current directory files
> 2. `cd` - change directory
> 3. `pwd` - show current working directory path
> 4. `mkdir` - create directory
> 5. `rm` - delete directory or file
> 6. `touch` - create new file
> 7. `cp` - copy file
> 8. `mv` - move file from one path to another, or rename file
> 9. `chmod` - change permissions granted to a file
> 10. `ls -a` - list all files under current directory, including hidden ones

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

> - `ls`  - list files under current directory
> - `ls -a`  - list files under current directory, including hidden files
> - `ls -l`  - list files under current directory in long format
> - `ls -lh` - list files under current directory in long format using unit suffixes to reduce number of digits to three or less
> - `ls -lah` - list files (including hidden ones) under current directory in long format using unit suffixes to reduce number of digits to three or less
> - `ls -t` - list files under current directory sort by time modified first then by lexicographical order 
> - `ls -Glp`  - list files under current directory with colorized output, in long format, and with slash after file name if file is a directory
 

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> 1.`ls -a`  
> 2. `ls -lh`  
> 3. `ls -t`  
> 4. `ls -p`  
> 5. `ls -Sl`  

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> Xargs allow one to build an execution pipeline from a standard input. 
> For example: 
> `find /docs -name *.tmp | xargs rm`
> The xample deletes all files with tmp extension under the docs directory

 

