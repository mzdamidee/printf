# _PRINTF

## SYNOPSIS
This is a simple implementation of printf function. 

## DESCRIPTION
The **_printf** The printf function prints formatted strings according to specifed formats listed below.

Interpreted sequences and available specifiers are:
+ \\:   backslash
+ \n:   New line
+ \r:   Carriage return
+ \t:   Horizontal tab
+ %%:   Prints a single %
+ %c:   Prints a single character
+ %s:   Prints a string of characters
+ %d:   Prints integers
+ %i:   Prints integers
+ %b:   Prints the binary representation of an unsigned decimal.
+ %o:   Prints the octal representation
+ %x:   Prints hexadecimal values
+ %X:   Prints hexadecimal values
+ %p:   Prints addresses.
+ %u:   Prints unsigned integers

## Example

```

#include "main.h"

/**
 * main - Entry point
 *
 * Return: Always 0
 */
int main(void)
{
    _printf("%S\n", "Best\nSchool");
    return (0);
}

maureen@MaureenO:~/c/printf$ gcc -Wall -Wextra -Werror -pedantic -std=gnu89 main.c 
maureen@MaureenO:~/c/printf$ ./a.out
Best\x0ASchool
maureen@MaureenO:~/c/printf$

```

## Authors:
- [Maureen Oguche](https://www.github.com/MaureenMOguche)
- Deborah Thomas
