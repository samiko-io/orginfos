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

4. 8 Data types: 
a) Numbers: Infinity, -Infinty and NaN (not a number) Numbers larger than 2^53- 1are denoted by 'n' at the
end of the number, indicating a 'BigInt' type
b) Strings: text enclosed in quotes
   -Simple quotes - "double" and 'single'
   -Extended Functionality quotes - `Backticks`:used to embed variables/expressions into a string using ${}
   e.g. greeting = (`Hello ${name}!`);
c) Booleans:** true/false;**, yes/no; 0/1
d) Null: represents 'empty' values
e) Undefined: represents an unassigned value
f) Object: store colections of data/complex entities
g) typeof: returns the type of operand
   eg. typeof 10 **'number'**

5. Interactive Functions
   a) alert: displays a message in a modal window (output)
   alert('Hello');
   b) prompt: provides a field in a modal window (input); takes two arguments
      title - text displayed to user
      [default] - default value of input field (optional)
      cancel=null
   prompt(title, [default]);
   let value = prompt(title, [default]);
   c) confirm: displays a question and 'OK' and 'CANCEL' buttons
      ok=true, cancel=false
   confirm(question); 




















   











   
