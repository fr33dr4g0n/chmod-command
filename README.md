# chmod-command
Chmod is an abbreviation of change mode.This page is dedicated to links to useful stuff about learning and using chmod.

# Syntax
chmod [options] [mode] [fileName]

# Options
-R recursive, i.e. include objects in subdirectories
-f force, forge ahead with all objects even if errors occur
-v verbose, show objects processed

# Octal modes 
7	= read, write and execute	( rwx )
6 =	read and write	(rw-)
5	= read and execute	(r-x)
4	= read only	(r--)
3	= write and execute	(-wx)
2	= write only	(-w-)
1	= execute only	(--x)
0	= none	(---)

# Users
u	= owner	file's owner
g	= group	users who are members of the file's group
o	= others	users who are neither the file's owner nor members of the file's group
a	= all	all three of the above, same as ugo

# Operators 
+	adds the specified modes to the specified classes
-	removes the specified modes from the specified classes
= the modes specified are to be made the exact modes for the specified classes

# Symbolic modes
r =	read	(read a file or list a directory's contents)
w =	write	(write to a file or directory)
x	= execute	(execute a file or recurse a directory tree)

# Learning links
[Chmod Wikipedia](https://en.wikipedia.org/wiki/Chmod)
[Chmod Man Pages](https://ss64.com/bash/chmod.html)
[Chmod PHP Pages](https://ss64.com/bash/chmod.html)
