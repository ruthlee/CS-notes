# WHAT THE HECK IS A SHELL? 

Source: http://www.ee.surrey.ac.uk/Teaching/Unix/unixintro.html

I've heard the words "shell," "linux/unix," and "bash" bandied about. It's time to get down to business and really figure out what each of those things mean and how they play together.

OPERATING SYSTEMS:
On Macs, the operating system is the UNIX operating system which is made up of three parts: 

	1) The kernel
	2) The shell
	3) The programs

**THE KERNEL:**
 - allocates time/memory to programs and handles system calls.
 - for example, when I type "rm" or "ls," these are commands which must be executed by the kernel.

**THE SHELL:** 
 - Interprets the commands the user types in and sends them to the kernel to be analyzed
 - the shell that I'm using (and that most people use) is bash. 
 - type echo $SHELL will return the shell, which in my case should return : /bin/bash

**FILES AND PROCESSES:** 
 - Everything is one of the two in a UNIX system
 - Process: an executing program (so I suppose these might be the unix commands? unsure)
 - File: a collection of data created by users using text editors and compilers (these are all codes, directories, office files, etc) 
