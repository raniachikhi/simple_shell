# Simple Shell

This is a simple shell program written in C as part of a project.

## Description

The Simple Shell project aims to create a basic shell program that mimics the functionality of the `/bin/sh` shell. The program reads commands from the user, executes them, and displays the output. It supports both interactive and non-interactive modes.

## Features

- Executes commands entered by the user
- Supports basic shell functionality (e.g., executing programs, handling built-in commands)
- Handles both interactive and non-interactive modes
- Provides error handling and displays appropriate error messages
- Supports input and output redirection
- Supports piping of commands
- Implements a subset of the available shell built-in commands

## Getting Started

### Compilation

To compile the Simple Shell program, use the following command:


### Usage

The Simple Shell program can be used in interactive mode by running the executable file without any arguments:


In interactive mode, the program will display a prompt and wait for the user to enter commands.

Alternatively, you can use the program in non-interactive mode by providing commands through standard input or file redirection:


## Example

Here's an example of how the Simple Shell program can be used:


## File Structure

The project repository has the following structure:

- `shell.c`: Main source code file
- `helper_functions.c`: Implementation of helper functions
- `header_file.h`: Header file containing function prototypes and necessary includes
- `README.md`: Project documentation

## Resources

- [Betty Style Guide](https://github.com/holbertonschool/Betty/wiki)

## Authors

- [Rania CHIKHI](https://github.com/raniachikhi)
- [Tlhoucine namouh](https://github.com/elhocyn)

## Acknowledgements

We would like to thank our instructors and peers for their guidance and support throughout this project.
