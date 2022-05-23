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
    <td>Function name</td>
    <td>get_next_line</td>
</tr>
<tr>
    <td>Prototype</td>
    <td>char *get_next_line(int fd);</td>
</tr>
<tr>
    <td>Turn in files</td>
    <td> get_next_line.c, get_next_line_utils.c, get_next_line.h</td>
</tr>
<tr>
    <td>Parameters</td>
    <td>fd: The file descriptor to read from </td>
</tr>
<tr>
    <td>Return value</td>
    <td>Read line: correct behavior NULL: there is nothing else to read, or an error occurred</td>
</tr>
<tr>
    <td>External functs.</td>
    <td>read, malloc, free</td>
</tr>
<tr>
    <td>Prototype</td>
    <td>Write a function that returns a line read from a file descriptor</td>
</tr>
</table>

## Bonus part
- get_next_line() using only one static variable.
- get_next_line() can manage multiple file descriptors at the same time.
