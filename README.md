# ALX _printf Group Project

## Project Description
We are to create a pintf group project. This is a low-level programme.
This project was done in a group of 2 people [Obadare Ayobami Joel](https://github.com/Ayondrun) and [Aduragbemi Oduntan](https://github.com/Salemori).
Our aim is to replicate the C standard
library printf() function.
The _printf() functions will produce output to the standard output based on the format specified.

**Prototype:** ```int _printf(const char *, ...);```

## Project Requirements

### Environment
* Operating system: Ubuntu 20.04 LTS
* Editor: vim 8.1.2269
* Language: C
* Compiler: gcc 9.3.0

### Specifications
* Not allowed to use global variables
* No more than 5 functions per file
* Code should use the Betty style,
  see [betty-style.pl](https://github.com/holbertonschool/Betty/blob/master/betty-style.pl) and [betty-doc.pl](https://github.com/holbertonschool/Betty/blob/master/betty-doc.pl)
* Compile using -Wall -Werror -Wextra
  -pedantic -std=gnu89 option.

### Authorized Functions and Macros

* ```write``` (man 2 write)
* ```malloc``` (man 3 malloc)
* ```free``` (man 3 free)
* ```va_start``` (man 3 va_start)
* ```va_end``` (man 3 va_end)
* ```va_copy``` (man 3 va_copy)
* ```va_arg``` (man 3 va_arg)

## Task Details
- [x] Write function that produces output with conversion specifiers ```c```, ```s```, and ```%```.
- [x] Handle conversion specifiers ```d```, ```i```.
- [x] Handle custom conversion specifier ```b```.
- [x] Handle conversion specifiers ```u```, ```o```, ```x```, ```X```.
- [x] Use a local buffer of 1024 chars in order to call ```write``` as little as possible.
- [x] Handle custom  conversion specifier ```S```.
- [x] Handle conversion specifier ```p```.
- [x] Handle flag characters ```+```, ```space```, and ```#``` for non-custom conversion specifiers.
- [x] Handle length modifiers ```l``` and ```h``` for non-custom conversion specifiers.
- [x] Handle the field width for non-custom conversion specifiers.
- [x] Handle the precision for non-custom conversion specifiers.
- [x] Handle the ```0``` flag character for non-custom conversion specifiers.
- [x] Handle the ```-``` flag character for non-custom conversion specifiers.
- [x] Handle the custom conversion specifier ```r``` that prints the reversed string.
- [x] Handle the custom conversion specifier ```R``` that prints the rot13'ed string.
- [x] All above options work really well together.

## Team Members
[Obadare Ayobami Joel](https://github.com/Ayondrun)\
[Aduragbemi Oduntan](https://github.com/Salemori)
