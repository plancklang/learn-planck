# Variables

In Planck, variable declarations are extremely similar to those in Java or C. They are a type, followed by a list of names.

## Type declaration
In Planck, variables are given a type as soon as instantiated. 
`float angle;`<br>
`char[] name;`<br>

## Redefining
Variables cannot be declared more than once, with the same type or not. So both of the below are invalid.
`char a; char a;` `char a; int a;`

In general in Planck, declarations are only of the form `[type] [name] ...` when they actually allocate space (as variables do). Otherwise, they are in the form `[name]: [type] ...`, as will be seen in other files.

## Examples
```c
char[] full;

char[] first = "Jake";
char[] last = "Roggenbuck";

full = last + " " + first;

int age = 10;
age++;
```
