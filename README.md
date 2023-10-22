# Monty Interpreter

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Learning Objectives](#learning-objectives)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributors](#contributors)
- [License](#license)

## Introduction
This project is a Monty ByteCode interpreter implemented in C. Monty is a scripting language that uses a unique stack with specific instructions to manipulate it. The goal of this project is to create a program that can read and execute Monty ByteCode files.

## Project Overview
In this project, we have implemented a Monty interpreter according to the specifications provided. The interpreter can process Monty ByteCode files and execute the specified instructions, handling errors and memory allocation.

## Learning Objectives
By working on this project, we aimed to achieve the following learning objectives:
- Understand and implement LIFO (Last In, First Out) and FIFO (First In, First Out) data structures.
- Gain proficiency in C programming, including file I/O, memory management, and error handling.
- Learn how to create and work with global variables in C.
- Develop a deeper understanding of coding style and adherence to coding standards (Betty style).


## Requirements
To successfully use and build this Monty interpreter, please ensure you have the following requirements in place:

- A C development environment (e.g., GCC, Linux)
- An editor (e.g., vi, vim, emacs)
- Access to a Unix-like system (e.g., Ubuntu 20.04 LTS)
- `betty-style.pl` and `betty-doc.pl` for code style checking
- A Monty ByteCode file to test the interpreter

## Getting Started
1. Clone the repository to your local machine:
git clone https://github.com/AKRAM-2002/monty-interpreter.git


2. Compile the Monty interpreter:
$ gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty


3. Run the Monty interpreter:
./monty your-monty-file.m



## Usage
The Monty interpreter is used to execute Monty ByteCode files. To run the interpreter, use the following command:
./monty your-monty-file.m

- `your-monty-file.m`: The path to the Monty ByteCode file you want to execute.

The interpreter will execute the commands in the specified Monty file and produce output or error messages as per the Monty language specifications.

## File Structure
- `monty.c`: The main program file that parses and executes Monty ByteCode files.
- `monty.h`: The header file containing function prototypes and data structures.
- Other C source files for specific functionalities (implementations of stack and queue operations, error handling, etc.).

## Contributors
- AKRAM BOUTZOUGA

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
