# get_next_line

|   |   |
:-------- | -------:
Function name | get_next_line
Prototype     | char *get_next_line(int fd);
Turn in files| get_next_line.c, get_next_line_utils.c, get_next_line.h
Parameters     | fd: The file descriptor to read from   
Return value     | Read line: correct behavior NULL: there is nothing else to read, or an error occurred 
External functs.     | read, malloc, free
Prototype     | Write a function that returns a line read from a file descriptor 

<table>
<tr>
    <td>Key 1</td>
    <td>Value 1</td>
</tr>
<tr>
    <td>Key 2</td>
    <td>Value 2</td>
</tr>
</table>

## Bonus part
- get_next_line() using only one static variable.
- get_next_line() can manage multiple file descriptors at the same time.
