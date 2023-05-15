<<<<<<< HEAD
# 42Cursus-03-Minishell
The objective of this project is for you to create a simple shell.
=======
# Minishell

## Overview
### What is a shell
A shell is a command-line interface (CLI) program that provides users with an interface to interact with the operating system. It allows users to enter commands and execute them, and can perform various operations such as launching programs, managing files and directories, and setting environment variables. The shell is often the primary user interface on Unix-based systems, and provides users with a way to interact with the system using text-based commands.

### The project
The minishell program is designed to be a simplified version of a real shell, with a limited set of features including the ability to execute commands, handle I/O redirection, implement pipes, and handle environment variables. The project requires a good understanding of C programming, UNIX system calls, and process management.

#### Basic features
* Display a prompt when waiting for a new command.
* Keep track of command history.
* Find and execute executables based on the PATH environment variable, or using a relative or absolute path.
* Use only one global variable, with a specific purpose that needs to be explained.
* Not interpret unclosed quotes or unnecessary special characters.
* Handle single quotes to prevent interpretation of metacharacters.
* Handle double quotes to prevent interpretation of metacharacters except for the $ sign.
* Implement redirections using <, >, <<, and >> symbols.
* Implement pipes using the | symbol.
* Handle environment variables (denoted by $ followed by a sequence of characters) and expand them to their values.
* Handle $? which expands to the exit status of the most recently executed foreground pipeline.
* Handle ctrl-C, ctrl-D, and ctrl-\ signals as in bash:
    * ctrl-C displays a new prompt on a new line
    * ctrl-D exits the shell
    * ctrl-\ does nothing.

#### Built-ins 
* echo with option -n
* cd with only a relative or absolute path
* pwd with no options
* export with no options
* unset with no options
* env with no options or arguments
* exit with no options.

## Evaluation
#### First submission
03/05/2023  
0%  
Failed due to a simple mistake on calling for ft_strncmp during built_in check.

#### Second submission
08/05/2023  
0%  
Failed due to a segfault caused by the quote_remover function when passing an argument like "word"'anotherword'

#### Third submission

>>>>>>> ede739ff17efaecacc6b1f757b1005be11ffe7f0
