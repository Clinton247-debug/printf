`printf` project

```markdown
# Custom printf Function in C

This project involves the implementation of a custom `printf` function in the C programming language. The goal is to create a function that can produce formatted output according to a given format string, similar to the standard `printf` function in C. However, in this project, we are not limited to the standard format specifiers; we will also implement some custom format specifiers and handle various flags and modifiers.

## Project Overview

The custom `printf` function is implemented in the `_printf.c` source file. This function is the heart of the project and handles the formatting and printing of output based on the provided format string and arguments.

## Getting Started

To compile and test the custom `printf` function, you can use the provided compilation command:

```shell
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c
```

This command compiles all the source files in the project directory.

## Project Structure

The project consists of several source files:

- `main.c`: This file contains test cases for the custom `printf` function. You can add your own test cases here.
- `main.h`: The header file where function prototypes are declared.
- `_printf.c`: The source file where the custom `printf` function is implemented.
- `_putchar.c`: Contains a custom `_putchar` function used for character output.
- Other source files for handling different features and options as specified in the project tasks.

## Project Tasks

The project includes a series of tasks, both mandatory and advanced, to enhance the functionality of the custom `printf` function. These tasks involve:

- Handling various standard and custom conversion specifiers (`%c`, `%s`, `%d`, `%i`, `%u`, `%o`, `%x`, `%X`, `%p`, `%b`, `%S`, `%r`, `%R`).
- Supporting flag characters (`+`, `space`, `#`, `0`, `-`) and length modifiers (`l`, `h`).
- Implementing field width and precision.
- Creating a local buffer for efficient writing.
- Handling non-printable characters and applying ROT13.
- Comprehensive testing to ensure all features work well together.

## Collaborate and Contribute

This project is a group project, and collaboration between team members is crucial. With coordinated efforts and shared responsibilities with my  team member, we were able to develop this project.
Feel free to contribute additional features, optimizations, or improvements to the custom `printf` function.

## Conclusion

Creating a custom `printf` function is a challenging but rewarding task that allows you to gain a deeper understanding of C programming, string manipulation, and the intricacies of formatting and printing.

```
