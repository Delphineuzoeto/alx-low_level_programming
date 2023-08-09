# File I/O Project in C

This repository contains solutions to a series of tasks related to file input/output and system calls in C programming. The tasks involve creating functions that perform various file-related operations. The goal of the project is to enhance your understanding of file handling, system calls, and error handling in C programming.

## Project Structure

This project is organized into multiple tasks, each with its own set of requirements and functions to implement.

- `0-read_textfile.c`: A function to read a text file and print its content to the standard output.
- `1-create_file.c`: A function to create a new file and write specified text content to it.
- `2-append_text_to_file.c`: A function to append text content to the end of a specified file.
- `3-cp.c`: A program to copy the content of one file to another file.

Each task includes its own test program (`*_main.c`) to validate the functionality of the implemented functions.

## Getting Started

To compile and run the programs, follow these steps:

1. Compile the C files using the provided compilation command.
2. Run the compiled program using `./a`, `./b`, `./c`, etc., depending on the task.

```bash
gcc -Wall -pedantic -Werror -Wextra -std=gnu89 <source_file.c> <main_file.c> -o <output_name>
./<output_name>
```

## Task Details

### Task 0: Read a Text File

- Implement the `read_textfile` function to read and print a given number of letters from a text file.
- Return the number of letters read and printed, handling error cases where necessary. 

### Task 1: Create a File

- Create the `create_file` function to create a new file with specified permissions and write text content to it.
- Return 1 on success, -1 on failure, while handling various error scenarios.

### Task 2: Append Text to a File

- Implement the `append_text_to_file` function to append text content to the end of a specified file.
- Return 1 on success, -1 on failure, considering cases where the file doesn't exist or text content is NULL.

### Task 3: Copy File Content

- Develop a program (`3-cp.c`) to copy content from one file to another.
- Handle error cases such as non-existent source file, read/write failures, and file descriptor closure issues.

 

 

