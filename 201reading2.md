Continued
[css](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)

Applying CSS to HTML
First, let's examine three methods of applying CSS to a document: with an external stylesheet, with an internal stylesheet, and with inline styles.

External stylesheet
An external stylesheet contains CSS in a separate file with a .css extension. This is the most common and useful method of bringing CSS to a document. You can link a single CSS file to multiple web pages, styling all of them with the same CSS stylesheet. In the Getting started with CSS, we linked an external stylesheet to our web page.

The CSS language has rules to control which selector is stronger in the event of a conflict. These rules are called cascade and specificity. In the code block below, we define two rules for the p selector, but the paragraph text will be blue. This is because the declaration that sets the paragraph text to blue appears later in the stylesheet. Later styles replace conflicting styles that appear earlier in the stylesheet. This is the cascade rule.

However, in the case of our earlier example with the conflict between the class selector and the element selector, the class prevails, rendering the paragraph text red. How can this happen even though a conflicting style appears later in the stylesheet? A class is rated as being more specific, as in having more specificity than the element selector, so it cancels the other conflicting style declaration.

Try this experiment for yourself! Add HTML, then add the two p { } rules to your stylesheet. Next, change the first p selector to .special to see how it changes the styling.

The rules of specificity and the cascade can seem complicated at first. These rules are easier to understand as you become more familiar with CSS. The Cascade and inheritance section in the next module explains this in detail, including how to calculate specificity.

For now, remember that specificity exists. Sometimes, CSS might not apply as you expected because something else in the stylesheet has more specificity. Recognizing that more than one rule could apply to an element is the first step in fixing these kinds of issues.


[javascript](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

A Hello world! example
JavaScript is one of the most popular modern web technologies! As your JavaScript skills grow, your websites will enter a new dimension of power and creativity.

However, getting comfortable with JavaScript is more challenging than getting comfortable with HTML and CSS. You may have to start small, and progress gradually. To begin, let's examine how to add JavaScript to your page for creating a Hello world! example. (Hello world! is the standard for introductory programming examples.)

Warning: If you haven't been following along with the rest of our course, download this example code and use it as a starting point.

Go to your test site and create a new folder named scripts. Within the scripts folder, create a new text document called main.js, and save it.
In your index.html file, enter this code on a new line, just before the closing </body> tag:
<script src="scripts/main.js"></script>
Copy to Clipboard
This is doing the same job as the <link> element for CSS. It applies the JavaScript to the page, so it can have an effect on the HTML (along with the CSS, and anything else on the page).
Add this code to the main.js file:
const myHeading = document.querySelector('h1');
myHeading.textContent = 'Hello world!';
Copy to Clipboard
Make sure the HTML and JavaScript files are saved. Then load index.html in your browser. You should see something like this:
Heading "hello world" above a firefox logo
Note: The reason the instructions (above) place the <script> element near the bottom of the HTML file is that the browser reads code in the order it appears in the file.

If the JavaScript loads first and it is supposed to affect the HTML that hasn't loaded yet, there could be problems. Placing JavaScript near the bottom of an HTML page is one way to accommodate this dependency. To learn more about alternative approaches, see Script loading strategies.

