This is a collaboration project where we create our own printf function.This team project is a custom made printf function for the C
programming language called printf.This function printf() writes output to stdout, the standard output stream with the format and options without making use off
any of the standard library files. It was written to use a local buffer of 1024 bytes when printing although it can print larger sets of data. The function returns the total number of characters printed to the stdout(excluding the null byte at the end of strings) after a successful execution.
If an output error is encountered, a negative value of -1 is returned.
The prototype of this function is: int printf(const char format, ...);
This means that it has one mandatory format argument, and an extra number of arguments that can be none, or many.

Format of the format string

The format string is a character string starting and ending with double quotes. The format string is composed of zero or more directives; ordinary characters (not %), and conversion specifications, each of which results in fetching zero or more subsequent arguments.
Each conversion specification is introduced by the character % and ends with a conversion specifier. In between there may be (in this order):
Zero or more flags
An optional field width
An optional precision modifier
An optional length modifier
The flag characters
Flag Description                                                                To Install, You will need to clone the repository of the project from Github. This will contain the printf function and all of its dependencies. there is no main.c file provided for testing, therfore you will need to create one. Submitted by Ibrahim Amir Gambo and Nurudeen Adeagbo
