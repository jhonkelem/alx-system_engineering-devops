0x03. Shell, init files, variables and expansions
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What happens when you type $ ls -l *.txt
Shell Initialization Files
What are the /etc/profile file and the /etc/profile.d directory
What is the ~/.bashrc file
Variables
What is the difference between a local and a global variable
What is a reserved variable
How to create, update and delete shell variables
What are the roles of the following reserved variables: HOME, PATH, PS1
What are special parameters
What is the special parameter $??
Expansions
What is expansion and how to use them
What is the difference between single and double quotes and how to use them properly
How to do command substitution with $() and backticks
Shell Arithmetic
How to perform arithmetic operations with the shell
The alias Command
How to create an alias
How to list aliases
How to temporarily disable an alias
Other help pages
How to execute commands from a file in the current shell
Requirements
General
Allowed editors: vi, vim, emacs
All your scripts will be tested on Ubuntu 20.04 LTS
All your scripts should be exactly two lines long ($ wc -l file should print 2)
All your files should end with a new line (why?)
The first line of all your files should be exactly #!/bin/bash
A README.md file, at the root of the folder of the project, describing what each script is doing
You are not allowed to use &&, || or ;
You are not allowed to use bc, sed or awk
All your files must be executable
More Info
Read your /etc/profile, /etc/inputrc and ~/.bashrc files.

Look at some files in the /etc/profile.d directory.

Note: You do not have to learn about awk, tar, bzip2, date, scp, ulimit, umask, or shell scripting, yet.

Tasks
0. <o>
mandatory
Create a script that creates an alias.

Name: ls
Value: rm *

1. Hello you
mandatory
Create a script that prints hello user, where user is the current Linux user.
2. The path to success is to take massive, determined action
mandatory
Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.

3. If the path be beautiful, let us not ask where it leads
mandatory
Create a script that counts the number of directories in the PATH.

4. Global variables
mandatory
Create a script that lists environment variables.

5. Local variables
mandatory
Create a script that lists all local variables and environment variables, and functions.

6. Local variable
mandatory
Create a script that creates a new local variable.

Name: BEST
Value: School

7. Global variable
mandatory
Create a script that creates a new global variable.

Name: BEST
Value: School

8. Every addition to true knowledge is an addition to human power
mandatory
Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.

9. Divide and rule
mandatory
Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.

POWER and DIVIDE are environment variables

10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath
mandatory
Write a script that displays the result of BREATH to the power LOVE

BREATH and LOVE are environment variables
The script should display the result, followed by a new line

11. There are 10 types of people in the world -- Those who understand binary, and those who don't
mandatory
Write a script that converts a number from base 2 to base 10.

The number in base 2 is stored in the environment variable BINARY
The script should display the number in base 10, followed by a new line

12. Combination
mandatory
Create a script that prints all possible combinations of two letters, except oo.

Letters are lower cases, from a to z
One combination per line
The output should be alpha ordered, starting with aa
Do not print oo
Your script file should contain maximum 64 characters

13. Floats
mandatory
Write a script that prints a number with two decimal places, followed by a new line.

The number will be stored in the environment variable NUM.


