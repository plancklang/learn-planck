# Types

In Planck, a type denotes a pattern of bytes making up an object. Planck has
several built-in types, many more library-defined types, and the ability for
a user to make an indefinite number of their own types.

| Name   | Size    |
|--------|---------|
| char   | 1 bytes |
| bool   | 1 bytes |
| short  | 2 bytes |
| int    | 4 bytes |
| float  | TBD     |
| double | TBD     |

## Built in
float and double are not built in but will have definitions in the standard library, and will have literal syntaxes

## Singing
All built-in types are signed (except for bool, which can only be 0 or 1).
