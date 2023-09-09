# Ft_printf

## Overview

`ft_printf` is a custom implementation of the `printf` function in the C programming language. This function allows you to format and print text to the standard output or a specified output stream. `ft_printf` supports various format specifiers, such as `%s`, `%d`, `%x`, and more, providing versatile text formatting capabilities.

This repository contains a sample implementation of the `ft_printf` function, along with usage examples to help you understand how to integrate it into your C projects.

## Features

- Supports a wide range of format specifiers, including `%s`, `%d`, `%x`, `%f`, and more.
- Enables custom formatting options through flags and modifiers.
- Handles variable-length argument lists (varargs) like the standard `printf`.
- Compatible with Unix-like systems (Linux, macOS) and Windows.

## Usage

### Including `ft_printf` in Your Project

1. Clone this repository or download the `ft_printf.c` and `ft_printf.h` files.

2. Add the `ft_printf.c` and `ft_printf.h` files to your project's source code directory.

3. Include the `ft_printf.h` header in your source files where you intend to use `ft_printf`.

```c
#include "ft_printf.h"
```

### Function Signature

```c
int ft_printf(const char *format, ...);
```

## Example Usage

```c
#include "ft_printf.h"

int main() {
    int num = 42;
    char *str = "Hello, world!";

    // Format and print text
    ft_printf("Integer: %d\n", num);
    ft_printf("String: %s\n", str);
    return (0);
}
```

## Build and Run

You can compile the example code using a C compiler (e.g., GCC):
```bash
gcc -o example example.c ft_printf.c -I.
```
Then, run the compiled executable:
```bash
./example
```

## Format Specifiers

`ft_printf` supports a wide range of format specifiers and formatting options. Refer to the (official printf format specifiers documentation)[https://en.cppreference.com/w/c/io/fprintf] for details on how to use them in your format strings.

## Acknowledgments

This implementation is inspired by the standard printf function and various open-source printf implementations available in the C community.


## Support 

If you have any questions, encounter issues, or need assistance with the libft project, please feel free to open an issue on GitHub. Im here to help and improve the library together.

This implementation is inspired by the standard printf function and various open-source `printf` implementations available in the C community.
