##  recap 

1. Basics of Unix, 
EC2 instance , 
ssh to our instance 

What is UNIX ?

OS : 1970s


Kernel  ?


types of editors in unix 
1. Vim 
2. Emacs 
3. nano 


 whenever you are working on file using vim editor. 
save and exit files 

:w - save the file 
:q exit, if there is any unsaved change, it wont let you exit 
:q!  - exit without save
:wq - to save and exit 
:x - to save and exit

cat - to print the content of the file without opening the file.. 


// 
Directory management 
1. Folder ----- directory 
cd - to change directory
cd .. - to go back to previous directory 
pwd - present working directory. 


         praga [d]
  |             |          | 
Mobile(d)      (d)Phone      file.txt [f]
 |             |
mobile.txt[f]    phone.txt  [f] 


 ## File permissions
permissions 
-rw-r--r--.
rw-     owner permission 
r--    group permission 
r--   other permission 

r - read 
w - write 
x - execute
chmod 000 file_name

0 - no permission 
1 - execute permission 
2 write perm
3 - write and execute 
4 - read permission 
5 - read and execute 
6 read and write 
7 all read, write and execute 

1. owner - all rwx, group - rw, other - no permission     ----  760 
2. owner - rw, group - rwx, other - rwx  - 677



-- [ cp exiting_file  new_file]
copy files --- cp 
rename     --- mv 
remove     -- rm 
remove dir - rmdir 

5- 10 minutes - practice above commands 



UNIX DOC : https://drive.google.com/file/d/1TN_JDyMcLPWLIr3PB0vpMAQ_lJuD83OC/view







