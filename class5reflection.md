[css](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)
CSS (Cascading Style Sheets) allows you to create great-looking web pages
As we have mentioned before, CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc.
CSS can be used for very basic document text styling — for example, for changing the color and size of headings and links. It can be used to create a layout — for example, turning a single column of text into a layout with a main content area and a sidebar for related information. It can even be used for effects such as animation. Have a look at the links in this paragraph for specific examples.
CSS is a rule-based language — you define the rules by specifying groups of styles that should be applied to particular elements or groups of elements on your web page.
In the above example, the CSS rule opens with a selector . This selects the HTML element that we are going to style. In this case, we are styling level one headings (<h1>).
We then have a set of curly braces { }.
Inside the braces will be one or more declarations, which take the form of property and value pairs. We specify the property (color in the above example) before the colon, and we specify the value of the property after the colon (red in this example).
This example contains two declarations, one for color and the other for font-size. Each pair specifies a property of the element(s) we are selecting (<h1> in this case), then a value that we'd like to give the property.

[how to add css](https://www.w3schools.com/css/css_howto.asp)

With an external style sheet, you can change the look of an entire website by changing just one file!

Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.
External styles are defined within the <link> element, inside the <head> section of an HTML page:

An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the <style> element, inside the head section.
Internal styles are defined within the <style> element, inside the <head> section of an HTML page:

An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

Inline styles are defined within the "style" attribute of the relevant element:

[css color](https://www.w3schools.com/cssref/pr_text_color.asp)
