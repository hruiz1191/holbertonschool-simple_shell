# Simple Shell
simple shell implementation that can execute commands from the command line, similar to the standard Unix/Linux shell.
___
# Usage 
shell will not display a prompt when it is ready to accept commands. Enter the command you wish to execute and press Enter. The shell will then execute the command and display the output.

* [$ ./hsh
* [ls
  * file1 file2 file3
* [echo  Hello, world!
  * Hello, world!
* [cat  file1
  * This is the content of file1.
* The shell also supports some built-in commands, such as exit.

# Files

Overview of the files in this repository:
| file | description |
|---|---|
| shell.h | Header file containing function prototypes and macros. |
| env_fetch.c| Verifies tokens|
| _getenv.c | Finds the environment |
| parse_input.c | Analyzes the user input and tokenizes it. |
| execute_command.c |Forks process, executes a command and waits if necessary.|
| find_or_execute_command | Checks the command input for execution.|
| mainshell.c| Entry point, command line interptreter.|
___
# AUTHORS
This shell was created by:
* Lucy ann [TGithub](https://www.ejemplo.com)
* Hector Ruiz [Github](https://github.com/hruiz1191/)
