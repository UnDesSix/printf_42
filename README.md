# ft_printf

### Description
This project is pretty straight forward. I recoded printf.

***
### Function


| Function name  | libftprintf.a |
| ------------- | ------------- |
| Prototype  | `int ft_printf(const char *, ...);` |
| External functs.  | malloc, free, write, va_start, va_arg, va_copy,va_end |

***
### Mandatory part

- It must not do the buffer management like the realprintf
- It manages the following conversions: cspdiuxX%
- It manages any combination of the following flags: ’-0.*’ and minimum fieldwidth with all conversions
