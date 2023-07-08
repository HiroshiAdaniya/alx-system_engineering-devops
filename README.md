# Shell

The shell is a program that takes a list of commands, usually from the keyboard andpasses them onto the OS(operating system) to perform. Some OS might offer different shell programs, but we will be focusing on the bash shell which comes with most Linux machines.

In this project we will be focusing on the bash shell only

## #! SHEBANG

Shebang is a character sequence consiting of "#!" at the begining of a script. When an exectuable script is run, the loader reads this first line in the file and understands that it is an argument and uses it as input data. Thus running a script to perform a task.

An example of a script:

	#!/bin/bash
	pwd

when this file is executed and then run, it will print the current working directory.

Now, scripting normally becomes more usefull when multiple lines of commands needed to be used to perform a specific task. Remeber that the terminal useally only allows 2 arguments at best.
