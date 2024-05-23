# C-scanf-printf

## Set Up
To set up scanf and printf in your C file, you must first add the stdio.h library. To do this type:
```
#include <stdio.h>
```

## Scanf
Scanf, which is used to scan user input, has the following syntax:
```
int scanf( const char *format, ... )
```
Int is the return type, and format is a format identifier, listed below. In place of ..., you write &A, where A is the variable in which the input is stored.

Acceptable formjat identifiers are:
%d to accept input of integers
%ld to  accept input of long integers
%lld to accept input of long long integers
%f to accept input of real number
%c to accept input of character types
%s to accept input of a string
