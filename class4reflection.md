[wireframe and design](https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/)

Wireframes provide a clear overview of the page structure, layout, information architecture, user flow, functionality, and intended behaviors.
Wireframes serve three key purposes: They keep the concept user-focused, they clarify and define website features, and they are quick and cheap to create.
It’s likely to be to your advantage to start off hand-drawing your wireframes before executing more detailed versions using an online app or software.

Here are a number of ways different designers can structure the process from design to implementation:
Wireframe > Interactive Prototype > Visual > Design
Sketch > Code
Sketch > Wireframe > Hi-Def Wireframe > Visual > Code
Sketch > Wireframe > Visual > Code

The first two steps; namely understanding who your audience is by way of user research,
detailing requirements, creating user personas and defining use cases, and complementing this with further competitor and industry research.

What does that mean? That means carrying out analysis of similar product lines to your own, digging into prevailing UX trends 
and best practises, and, of course, reviewing your own internal design guidelines. 

As Jeff suggests in the video above, pose yourself the following three questions while you’re sketching:
How can you organise the content to support your users’ goals?
Which information should be most prominent? Where should your main message go? What should the user see first when arriving at the page?
What will the user expect to see on certain areas of the page?
Which buttons or touch points does the user need to complete the desired actions?

Think about the following:
Usability conventions, such as putting the navigation at the top next to your logo, having a search box on the top right, and so on
Simple, instructional wording for i.e. calls-to-action
Trust-building elements: What do you need to build trust in your customers and where would be the best place to put these elements?
Tooltips to indicate any functionality that could be included in a prototype transition

How to make your wireframe good: Three key principles
Clarity, Confidence, Simplicity is key

[HTML Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)

HTML is a markup language that defines the structure of your content. HTML consists of a series of elements, which you use to enclose, or wrap,
different parts of the content to make it appear a certain way, or act a certain way.

The main parts of our element are as follows:
The opening tag: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets.
This states where the element begins or starts to take effect — in this case where the paragraph begins.

The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends —
in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.

The content: This is the content of the element, which in this case, is just text.

The element: The opening tag, the closing tag, and the content together comprise the element.

Attributes contain extra information about the element that you don't want to appear in the actual content.

An attribute should always have the following:
A space between it and the element name (or the previous attribute, if the element already has one or more attributes).
The attribute name followed by an equal sign.
The attribute value wrapped by opening and closing quotation marks.

You can put elements inside other elements too — this is called nesting
The elements have to open and close correctly so that they are clearly inside or outside one another.

Some elements have no content and are called empty elements.
This contains two attributes, but there is no closing </img> tag and no inner content. 
This is because an image element doesn't wrap content to affect it. Its purpose is to embed an image in the HTML page in the place it appears.

<!DOCTYPE html> — doctype. It is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However these days, they don't do much and are basically just needed to make sure your document behaves correctly. That's all you need to know for now.
<html></html> — the <html> element. This element wraps all the content on the entire page and is sometimes known as the root element. It also includes the lang attribute, setting the primary language of the document.
<head></head> — the <head> element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.
<meta charset="utf-8"> — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this and it can help avoid some problems later on.
<meta name="viewport" content="width=device-width"> — This viewport element ensures the page renders at the width of viewport, preventing mobile browsers from rendering pages wider than the viewport and then shrinking them down.
<title></title> — the <title> element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.
<body></body> — the <body> element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.

Heading elements allow you to specify that certain parts of your content are headings — or subheadings. In the same way that a book has the main title, chapter titles, and subtitles, an HTML document can too.
  
<p> elements are for containing paragraphs of text; you'll use these frequently when marking up regular text content:
  
  A lot of the web's content is lists and HTML has special elements for these. Marking up lists always consists of at least 2 elements. The most common list types are ordered and unordered lists:
  
  [Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)
  
  In programming, Semantics refers to the meaning of a piece of code
  HTML should be coded to represent the data that will be populated and not based on its default presentation styling. Presentation (how it should look), is the sole responsibility of CSS.
  Some of the benefits from writing semantic markup are as follows:

Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
Screen readers can use it as a signpost to help visually impaired users navigate a page
Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
Suggests to the developer the type of data that will be populated
Semantic naming mirrors proper custom element/component naming
  
  
