0:Write a beautiful code that passes the Betty checks

1:Write a UNIX command line interpreter.

2:Handle command lines with arguments

3:Handle the PATH
fork must not be called if the command doesn’t exist

4: Implement the exit built-in, that exits the shell
Usage: exit
You don’t have to handle any argument to the built-in exit

5:Implement the env built-in, that prints the current environme

6:Write your own getline function
Use a buffer to read many chars at once and call the least possible the read system call
You will need to use static variables
You are not allowed to use getline

7You are not allowed to use strtok

8:handle arguments for the built-in exit
Usage: exit status, where status is an integer used to exit the shell

9:mplement the setenv and unsetenv builtin commands

setenv
Initialize a new environment variable, or modify an existing one
Command syntax: setenv VARIABLE VALUE
Should print something on stderr on failure
unsetenv
Remove an environment variable
Command syntax: unsetenv VARIABLE
Should print something on st

10:Implement the builtin command cd:

Changes the current directory of the process.
Command syntax: cd [DIRECTORY]
If no argument is given to cd the command must be interpreted like cd $HOME
You have to handle the command cd -
You have to update the environment variable PWD when you change directory
man chdir, man getcwd

11:Handle the commands separator 

12:Handle the && and || shell logical operators

13:Implement the alias builtin command
Usage: alias [name[='value'] ...]
alias: Prints a list of all aliases, one per line, in the form name='value'
alias name [name2 ...]: Prints the aliases name, name2, etc 1 per line, in the form name='value'
alias name='value' [...]: Defines an alias for each name whose value is given. If name is already an alias, replaces its value with value

14:Handle variables replacement
Handle the $? variable
Handle the $$ variable

15:Handle comments (#)

16:Usage: simple_shell [filename]
Your shell can take a file as a command line argument
The file contains all the commands that your shell should run before exiting
The file should contain one command per line
In this mode, the shell should not print a prompt and should not read from stdin
