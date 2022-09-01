[md control](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)

The control flow is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops.

For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:

A typical script in JavaScript or PHP (and the like) includes many control structures, including conditionals, loops and functions. Parts of a script may also be set to execute when events occur.

For example, the above excerpt might be inside a function that runs when the user clicks the Submit button for the form. The function could also include a loop, which iterates through all of the fields in the form, checking each one in turn. Looking back at the code in the if and else sections, the lines promptUser and submitForm could also be calls to other functions in the script. As you can see, control structures can dictate complex flows of processing even with only a few lines of code.

Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.

[functions](https://www.w3schools.com/js/js_functions.asp)

A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:

The code to be executed, by the function, is placed inside curly brackets: {}

[operators](https://www.w3schools.com/js/js_operators.asp)

JavaScript Arithmetic Operators
Arithmetic operators are used to perform arithmetic on numbers:

Operator	Description
+	Addition
-	Subtraction
*	Multiplication
**	Exponentiation (ES2016)
/	Division
%	Modulus (Division Remainder)
++	Increment
--	Decrement

JavaScript Arithmetic Operators
Arithmetic operators are used to perform arithmetic on numbers:

Operator	Description
+	Addition
-	Subtraction
*	Multiplication
**	Exponentiation (ES2016)
/	Division
%	Modulus (Division Remainder)
++	Increment
--	Decrement