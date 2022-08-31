[Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles. Read more about JavaScript.
The standards for JavaScript are the ECMAScript Language Specification (ECMA-262) and the ECMAScript Internationalization API specification (ECMA-402). As soon as one browser implements a feature, we try to document it. This means that cases where some proposals for new ECMAScript features have already been implemented in browsers, documentation and examples in MDN articles may use some of those new features. Most of the time, this happens between the stages 3 and 4, and is usually before the spec is officially published.

[input and output in javascript](https://code-maven.com/input-output-in-plain-javascript)

In this example we have a bit more HTML than earlier. In addition to having a button, and a div element where we'll show our results, we also have two input elements. Each one with its own ID.

If you click on the Try link, you'll see two input boxes and a button:

In the JavaScript code we have a function called say_hi. It used the getElementById we have already seen to locate the DOM element representing the input element with the id first_name. The object returned has a method value that will return the text the user has typed in that field.

We use this technique to retrieve the content of both input fields and assign their content to two variables: fname and lname.

Then, using these variable we create an HTML snippet and assign it to a new variable called html.

Then we set the innerHTML attribute as earlier to show the HTML we generated. The result might look like this:

Even in such a simple HTML we wanted to create we had to use + several time and the code is quite unreadable. Imagine what would happen if we wanted to build a more complex application where we might want to build a list of items, or even a table. Building the HTML on the fly and the inserting in the DOM would be quite nasty.

In the back-end systems written in Perl, Python or Ruby, people have encountered the same problem and the solution was the creation of various templating engines. Basically a template would be an HTML snippet with some place holders and then a function call that gets the HTML snippet (the template) as a parameter, and gets several key-value pairs. The function then returns a new HTML snippet in which the place holders were replaced by the value of the appropriate key.

[javascript variables](https://www.w3schools.com/js/js_variables.asp)

When to Use JavaScript var?
Always declare JavaScript variables with var,let, orconst.

The var keyword is used in all JavaScript code from 1995 to 2015.

The let and const keywords were added to JavaScript in 2015.

If you want your code to run in older browser, you must use var.

When to Use JavaScript const?
If you want a general rule: always declare variables with const.

If you think the value of the variable can change, use let.

In this example, price1, price2, and total, are variables:

JavaScript Identifiers
All JavaScript variables must be identified with unique names.

These unique names are called identifiers.

Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).

The general rules for constructing names for variables (unique identifiers) are:

Names can contain letters, digits, underscores, and dollar signs.
Names must begin with a letter
Names can also begin with $ and _ (but we will not use it in this tutorial)
Names are case sensitive (y and Y are different variables)
Reserved words (like JavaScript keywords) cannot be used as names
In JavaScript, the equal sign (=) is an "assignment" operator, not an "equal to" operator.

This is different from algebra. The following does not make sense in algebra:
Note
The "equal to" operator is written like == in JavaScript.

JavaScript variables can hold numbers like 100 and text values like "John Doe".

In programming, text values are called text strings.

JavaScript can handle many types of data, but for now, just think of numbers and strings.

Strings are written inside double or single quotes. Numbers are written without quotes.

If you put a number in quotes, it will be treated as a text string.

Declaring a JavaScript Variable
Creating a variable in JavaScript is called "declaring" a variable.

You declare a JavaScript variable with the var or the let keyword:
