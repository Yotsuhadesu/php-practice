# PHP Practice - Day 2
## Aritmetic Operators
- `+`, `-`, `*`, `/`, `%`
## Loose Comparison vs Strict Comparison
- `==`/`!=` - compares the value
- `===`/`!==` - compares the value and the data type

## Concatenation
- concatenate string using the dot (.) symbol

        Example:
        $name = "Yotsuha";
        echo "My name is " . $name;
        // Output
        My name is Yotsuha
## Conditional Statements
- executes a code block if the condition is true
### If Statements    
- executes the first code block to meet the condition
1. if

        Syntax:
        if (condition) {
            // code statement(s)
        }
2. ifelse

        Syntax:
        if (condition) {
            // code statement(s)
        } else {
            // code statement(s)
        }
3. ifelseif

        Syntax:
        if (condition) {
            // code statement(s)
        } elseif (condition) {
            // code statement(s)
        } else {
            // code statement(s)
        }
### Switch Statements
- executes a code block if a variable/value matches a value

        Syntax:
        switch(value) {
            case value:
                // code statement(s)
                break;
            default:
                // code statement(s) to execute if no matching case
        }
### Ternary Operator
- shorthand way of simple if else

        Syntax:
        $var = (condition) ? value if true : value if false;
## Logical Operators
1. && (AND)
2. || (OR)
3. ! (NOT)