ORGINFOS 244 - NOTES

=====javascript=====
1. "use strict" should be the first line (ie. a directive), and it indicates to the browser that the JS file should be interpreted in a 'modern' way.

2. Variabe: a named container to store data
Declaration: 'let message = 'Hello';' (assigns 'Hello' to a variable named message)
Multiple Declarations: 'let mesage = 'Hello', age = 25, etc...' (multiple assignments are separated by a comma)
    *let - block definitions 
    var - function wide and global definitions 
Naming Conventions: only letters and numbers (but never starting with a number)
Case sensitive - use camelCase
Language Reserved Words: let, var class, return, function etc.

Example
let name = 'John';
let admin = name;
alert(admin);
    or
let admin, name;
name = 'John';
admin = name; 

3. Constants: Variables that cannot be reassigned (error if changed)
Declaration: const name = 'Samiko';
Naming Convention: uppercase letters for constants that are aliases for forgettable values
eg const COLOR_RED = "#F00";
-otherwise, use camelCase

4. Data types: 
Numbers: Infinity, -Infinty and NaN (not a number)