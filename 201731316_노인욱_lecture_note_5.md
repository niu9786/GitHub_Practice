# Lecture Note 2
### about CLI
---

## IO Redirection: Standard Output
---
### Default
screen output

### >
to create and save the output in a file

### cat
displays the content of a text file

### >>
- append
- create and write to a new file(doesn't exist)

## IO Redirection: Standard Input
---
### Default
keyboard

### <
redirect input from a file

### < + >
can use together

### PipeLine |
feed output of previous command to input of next command

## Expansion
---
special characters expand its meaning when given to shell commands

### Tip: Backslash
ignore line change in command("enter"), to enter a long command in multiple lines

## Permissions
---
Linux is a multi-user system (Server is multi-user system)
not to be accepted anyone

### - or d | rwx | rwx | rwx | user | group | 
1. file type : - is regular file, d is directory
2. owner's permissions
3. group owner's permissions
4. all other users's permissions


