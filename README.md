
# LINUX-BASIC-COMMANDS

* To create a file with cat  :
```bash
 cat > <Filename>
```
* To apend more lines to a file :
```bash
 cat >> <Filename>
```
* To view the file :
```bash
 cat <Filename>
```
* To create an empty file :
```bash
 touch <Filename>
```
*  To create mutiple files at a time :
```bash
 touch <Filename{1..n}>
```
* To create or edit an existing  file :
```bash
 vi <Filename>
```
* To create a directory :
```bash
 mkdir <Dirname>
```
* To create directory recursively :
```bash
 mkdir -p <Dirname>
```
* To know present working directory :
```bash
 pwd 
```
* To move one dir to another dir :
```bash
 cd <Dirname>
```
* To list the content in pwd :
```bash
 ls 
```
*  To move one dir back :
```bash
 cd ..
```
* To directly go to home from any dir :
```bash
 cd 
```
* To remove a file :
```bash 
 rm <Filename>
```
* To remove an empty dir :
```bash
 rmdir <Dirname>
```
* To remove a non empty dir :
```bash
 rm -rf <Dirname>
```
* To list the perticular dir :
```bash
 ls <Dirname>
```
* To create hidden dir :
```bash
 mkdir .<Dirname>
```
* To create a  hidden file ;
```bash
 touch .<Filename>
```
* To list the hidden files or dir :
```bash
 ls -a
```
* To display the content with size :
```bash
 ls -s
```
* To list the full information of the content (Long listing) :
```bash
 ls -l
```
* To view the permissions of perticular file or dir :
```bash
 ls -ld <Filename/Dirname>
```
*  To list the content with time of creation (recently created files first showing) :
```bash
 ls -lt
```
* To list the content with time but reverse (older ones first showing) :
```bash
 ls -lrt
```
* To change the permissions of a perticular file or dir :
```bash
 chmod number <Filename/Dirname>
```
* To create a user :
```bash
 useradd <Username>
```
* To create a user in ubuntu :
```bash
 adduser <Username>
```
* To change the ownership of a file or dir :
```bash
 chown <Username> <Filename/Dirname>
```
*  To delete a user :
```bash
 userdel <Username>
```
* All the existing users are locating in :
```bash
 /etc/passwd
```
* To create a group :
```bash
 groupadd <Groupname>
```
* To change a group membership of a file/dir :
```bash
 chgrp <Groupname> <Filename/Dirname>
```
* To delete a group :
```bash
 groupdel <Groupname>
```
* All the existing groups are located in this file :
```bash
 /etc/group  
```
* To copy  file into a dir :
```bash
 cp <Filename> <Dirname>
```
* Copy dir into a dir :
```bash
 cp -r <Dirname> <Dirname>
```
* To move file into a dir :
```bash
 mv <Filename> <Dirname>
```
* To move one dir into another dir :
```bash
 mv <Dirname> <Dirname>
```
* This command is also used for renaming :
```bash
 mv
```
* To create a hard link for a file :
```bash
 ln <srcfile> <linkname>
```
*  To create a softlink :
```bash
 ln -s <srcfile> <linkname>
```
* To remove the link :
```bash
 unlink <linkname>
```
