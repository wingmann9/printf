This repository contains a C program that is a psuedo-recreation of the standard C library function, printf.

The function _printf prints to standard output. To use the _printf function, all the .c files in the repository including the header file must be compiled with any main function.

The _printf function writes under the control of a format string that specifies how subsequent arguments are converted to stdout. 
Upon successful return, _printf returns the number of characters printed (excluding the terminating null byte used to end output to strings). If an output error is encountered, the function returns -1.

Prototype: int_printf(const char *format, ...);
