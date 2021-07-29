## _printf -- Proyect Holberton
This project is for replicate the C standard library printf() function
file            |   Description
--|--
holberton.h     | A file for call to prototypes and structurs.
_putchar.c      | A file for call to (writer)  putchar print  in _printf.
_printf.c       | A file  for call base structur from holberton.h.
get_format.c    | A file that helps to make the evaluation of the format in the structure.
special_cases.c | A File that evaluates the number of edge cases with "%" in the input.
print_basic.c   | A File containing the basic printing functions in %i %d %s %c %% %u format.
print_advanced.c| A File containing the advanced printing functions in %r %R %x %X and function of print_hex format.
print_pro.c     | A File containing the advanced printing functions in %o format.
Makefile        | File containing the basic compilation commands.
man_3_printf    | A file man type for printf function.
## Prototype
``` int _printf(const char *format, ...);```
<h2>Repositorio</h2>
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=yazgiraldoa&repo=/printf)](https://github.com/yazgiraldoa/printf)
<h2 align = 'center'>Authors</h2>
<h2 align = 'center' ><img src='https://raw.githubusercontent.com/ShahriarShafin/ShahriarShafin/main/Assets/handshake.gif' width="300px">
* **Juan Duque** - @Juan_Duque0
  <a href = 'https://www.twitter.com/@juan_duque0'> <img width = '32px' align= 'center' src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/twitter.svg"/></a>
  <a href = 'https://www.github.com/DKBARB10'> <img width = '32px' align= 'center' src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/github.svg"/></a>
* **Yazmin Giraldo** - @yazgiraldoa
  <a href = 'https://www.twitter.com/@yazgiraldoa'> <img width = '32px' align= 'center' src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/twitter.svg"/></a>
  <a href = 'https://www.github.com/yazgiraldoa'> <img width = '32px' align= 'center' src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/github.svg"/></a>
  <img src="http://www.holbertonschool.com/holberton-logo.png" alt="Holberton School logo">
  </h2>
  heart
  +1
  raised_hands






Yazmín Giraldo  9:55 PM
A file that contains a structure and the prototypes of the functions.
9:55
Para la descripción de Holberton.h :see_no_evil:

Juan Duque  10:53 PM
a (edited)
10:57
### Examples with format
Here specific cases are evaluated with each of the formats.
#### d, i
The `int` argument is converted to signed decimal notation.
Example `main.c`:
```
int main(void)
{
    _printf("%d\n", 7);
}
```
Output:
```
7
```
#### o, u, x, X
The `unsigned int` argument is converted to unsigned octal (`o`), unsigned
decimal (`u`), or unsigned hexadecimal (`x` and `X`). The letters `abcdef` are
used for `x` conversions and the letters `ABCDEF` are used for `X` conversions.
Example `main.c`:
```
int main(void)
{
    _printf("%o\n", 77);
}
```
Output:
```
115
```
#### c
The `int` argument is converted to an `unsigned char`.
Example `main.c`:
```
int main(void)
{
    _printf("%c\n", 48);
}
```
Output:
```
0
```
#### s
The `const char *` argument is expected to be a pointer to a character array. Characters from the array are written starting from the first element of the array and ending.
Example `main.c`:
```
int main(void)
{
    _printf("%s\n", "Hello, World!");
}
```
Output:
```
Hello, World!
```
#### R
Identical to the `s` conversion specifier, except each character of the array
is converted to its corresponding character in ROT13 before being written.
Example `main.c`:
```
int main(void)
{
    _printf("%R\n", "Hello, World");
}
```
Output:
```
Uryyb, Jbeyq
```
#### %
A `%` is written. No argument is converted. The complete conversion
specification is `%%`.
Example:
```
int main(void)
{
    _printf("%%\n");
}
```
Output:
```
%
```

## Return Value
Upon successful return, _printf returns the number of characters printed (excluding the terminating null byte used to end output to strings). If an output error is encountered, the function returns -1.


<h2>Repositorio</h2>
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=yazgiraldoa&repo=/printf)](https://github.com/yazgiraldoa/printf)

 <h2 align = 'center'>Authors</h2>
<h2 align = 'center' ><img src='https://raw.githubusercontent.com/ShahriarShafin/ShahriarShafin/main/Assets/handshake.gif' width="300px"> 

* **Juan Duque** - @Juan_Duque0 

<a href = 'https://www.twitter.com/@juan_duque0'> <img width = '32px' align= 'center' src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/twitter.svg"/></a> 
<a href = 'https://www.github.com/DKBARB10'> <img width = '32px' align= 'center' src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/github.svg"/></a> 

* **Yazmin Giraldo** - @yazgiraldoa 

<a href = 'https://www.twitter.com/@yazgiraldoa'> <img width = '32px' align= 'center' src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/twitter.svg"/></a> 
<a href = 'https://www.github.com/yazgiraldoa'> <img width = '32px' align= 'center' src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/github.svg"/></a> 
   
 <img src="http://www.holbertonschool.com/holberton-logo.png" alt="Holberton School logo">
  
   
</h2>



