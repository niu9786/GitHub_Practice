# Lecture Note
### about CLI
---

CLI(Command Line Interface) is interface which run through line by line.

There are some differences between CLI and GUI

|CLI|GUI|
|---|---|
|Have to remember commands|Easy to use and Intuitive|
|Keyboards, mostly|Mouse mostly + Some keyboard shortcuts|
|Relatively fast|Relatively slow|
|Scripts enable automation and records|Manual labors required for repetitive tasks|
|Basic environment for developers|For daily users|



## How to use Shell Terminal
---
### In Linux or MacOS
Run ***"Terminal"*** App
### In Windows
Install ***"Git Bash"***



## Shell Command
---
### pwd
shows the current path in a hierarchical directory

### cd
change directory

#### cd arguments
---
- [directory name]
- / : root
- . : current directory
- .. : upper-level directory
- ~ : home of current user
- /[directory name] : absolute path
- ./[directory name] : relative path
- ../[directory name] : relative path

### ls
list files and directories

#### ls options
---
- -l : show detailed information (long format)
- -lh : same as above, but size in units
- /bin : list files in the /bin directory
- -l /etc /bin : list files in the /bin directory and the /etc directory in long form
- -la .. list all files in the parent of the working directory in long form

long format : file permisions_owner_group_size in bytes_modification time_file name

### Tips
- In current directory, if you press the **unique** word and press **tap** key, automatically inputted
- If you press the **up arrow** key, the past commands automatically inputted'
- Input **clear** : clear the Shell command

### Manipulation

#### cp
---
to copy files and directories
- cp file1 file2 : copies the contents of file1 into file2 (if file2 does not exist, it is created)
- cp -i file1 file2 : if file2 exists, the user is prompted before it is overwritten with the contents of file1
- cp file1 dir1 : copy the contents of file1 inside of directory dir1
- cp -R dir1 dir2 : copy the contents of the directory dir1 (if dir2 does not exist, it is created)

#### mv
---
move files and directories or rename them
- mv file1 file2 : file2 does not exist, file1 is renamed file2. file2 exist, its contents are silently replaced with the contents of file1
- mv -i file1 file2 : if file2 exists, the user is prompted before it is overwritten with the contents of file1
- mv file1 file2 dir1 : fie1 and file2 are moved to directory dir1 (if dir1 does not exist, *error*)
- mv dir1 dir2 : dir2 does not exist, dir1 is renamed dir2. dir2 exist, dir1 is moved within dir2

#### rm
---
delete files and directories permantely and irreversevely
- rm file1 file2 : delete file1 and file2
- rm -i file1 file2 : the user is prompted before each file is deleted
- rm -r dir1 dir2 : directory dir1 and dir2 are deleted along with all of their contents

#### mkdir
---
make a new directory

#### wildcards
---
- \* : all filenames
- g\* : all filenames that begin with the character **g**
- b\*.txt : all file names that begin with the character **b** and end with the characters **.txt**
- Data??? : any file name that begin with the characters **Data** followed by exactly 3 more characters
- cp \*.txt text_files : copy all files in current directory witn names ending **.txt** to directory named **text_files**
- mv dir1 ../\*.bak dir2 : move subdirectory dir1 and all files ending **.bak** in current directory to directory named **dir2**
- rm \*~ : delete all files in current directory end with **~**

### help command
---
- help
- man

### exiting terminal
---
- exit



