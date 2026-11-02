# PHP Practice - Day 1
## About PHP
- PHP runs in the server and the browser cannot see it until it is turned into plain HTML by the server.
- Codes must be put inside `<?php //put your code here ?>`.
- Code statements must always end with semicolon.
## Variables
- Declare a variable using the `$` symbol.

        $name = "Jethro";
## Concatenation
- Concatenate using `.` symbol.

        echo "Hello, my name is " . $name . ".";
- Concatenate directly (only works with double quotes)

        $introduction = "Hello, my name is $name.";
## Data Types
1. String - group of characters enclosed by double or single quotes
2. Integer - whole number
3. Float - decimal
4. Boolean - true or false
5. Null - no value
## Commands
- echo 
    - prints something as raw text
    - can also be used to add html elements
    - prints nothing if the value is null or false and prints 1 if the value is true
- var_dump() 
    - prints the data type of the variable
    - If used on a string, it will show the number of characters along with the value.
- define() - declares a constant