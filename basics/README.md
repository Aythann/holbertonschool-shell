Shell Basics Project
Description

This project introduces the fundamentals of using the Unix shell and working in a command-line environment. You’ll learn how to navigate the Linux filesystem, manipulate files and directories, understand shell commands, use manual (man) pages, and make your own Bash scripts executable.

The goal is to become comfortable using the terminal and understand what happens behind the scenes when commands are executed.

Learning Objectives

By the end of this project, you should be able to explain the following concepts without using Google:

General

What RTFM means and why it matters

What a Shebang (#!/bin/bash) is and its purpose

What the Shell is and how it differs from a Terminal

What the Shell prompt is

How to use your command history

Navigation

Commands: cd, pwd, ls

How to move around the filesystem

Meaning of . and .. directories

What the working directory is and how to print or change it

What the root directory and the home directory are

Difference between /root and a user’s home directory

What hidden files are and how to list them

What cd - does

Looking Around

Commands: ls, less, file

How to use options and arguments

Understanding the long format output of ls

A Guided Tour

Command: ln

Structure of common system directories

What symbolic links and hard links are

Difference between symbolic and hard links

Manipulating Files

Commands: cp, mv, rm, mkdir

What wildcards are and how to use them

Working With Commands

Commands: type, which, help, man

Different kinds of commands (built-in, external, aliases, etc.)

When to use help instead of man

What an alias is

Reading Man Pages

How to read and understand man pages

What man page sections are

Section numbers for:

User commands

System calls

Library functions

Keyboard Shortcuts for Bash

Common shortcuts to make command-line work faster and more efficient

LTS

What LTS (Long Term Support) means in Linux distributions

Requirements

Allowed editors: vi, vim, emacs

Tested on Ubuntu 22.04 LTS

Each script must:

Be exactly two lines long

End with a new line

Start with the line:

#!/bin/bash


Be executable (chmod u+x filename)

No use of backticks, &&, ||, or ;

Must include:

A README.md file at the root of the repository

A README.md file inside the project folder, describing each script

Example
julien@ubuntu:/tmp$ wc -l 12-file_type
2 12-file_type
julien@ubuntu:/tmp$ head -n 1 12-file_type
#!/bin/bash


To make a script executable:

chmod u+x filename


To run it:

./filename

Tips

Explore the man pages using man <command>

Use help <command> for built-in commands

Don’t forget: practice is key — the shell becomes powerful only when used regularly.
