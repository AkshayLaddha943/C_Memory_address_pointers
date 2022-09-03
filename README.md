# C_Memory_address_pointers

## Memory Address
When a variable is created in C, a memory address is assigned to the variable.

The memory address is the location of where the variable is stored on the computer

To access it, use the reference operator (&), and the result will represent where the variable is stored -

```
int myAge = 43;
printf("%p", &myAge)

```
&myAge is often called a "pointer". A pointer basically stores the memory address of a variable as its value.
