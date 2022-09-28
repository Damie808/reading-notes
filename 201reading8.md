[flexbox css](https://web.dev/learn/css/flexbox/)

Flexbox
Flexbox is a layout mechanism designed for laying out groups of items in one dimension. Learn how to use it in this module.

A design pattern that can be tricky in responsive design is a sidebar that sits inline with some content. Where there is viewport space, this pattern works great, but where space is condensed, that rigid layout can become problematic.

The Flexible Box Layout Model (flexbox) is a layout model designed for one-dimensional content. It excels at taking a bunch of items which have different sizes, and returning the best layout for those items.

This is the ideal layout model for this sidebar pattern. Flexbox not only helps lay the sidebar and content out inline, but where there's not enough space remaining, the sidebar will break onto a new line. Instead of setting rigid dimensions for the browser to follow, with flexbox, you can instead provide flexible boundaries to hint how the content could display.

[flexbox layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

Why Flexbox?
For a long time, the only reliable cross-browser compatible tools available for creating CSS layouts were features like floats and positioning. These work, but in some ways they're also limiting and frustrating.

The following simple layout designs are either difficult or impossible to achieve with such tools in any kind of convenient, flexible way:

Vertically centering a block of content inside its parent.
Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.
Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

