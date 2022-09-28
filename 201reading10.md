[troubleshooting JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)

When you built up the "Guess the number" game in the previous article, you may have found that it didn't work. Never fear — this article aims to save you from tearing your hair out over such problems by providing you with some tips on how to find and fix errors in JavaScript programs.

Types of error
Generally speaking, when you do something wrong in code, there are two main types of error that you'll come across:

Syntax errors: These are spelling errors in your code that actually cause the program not to run at all, or stop working part way through — you will usually be provided with some error messages too. These are usually okay to fix, as long as you are familiar with the right tools and know what the error messages mean!
Logic errors: These are errors where the syntax is actually correct but the code is not what you intended it to be, meaning that program runs successfully but gives incorrect results. These are often harder to fix than syntax errors, as there usually isn't an error message to direct you to the source of the error.
Okay, so it's not quite that simple — there are some other differentiators as you drill down deeper. But the above classifications will do at this early stage in your career. We'll look at both of these types going forward.

An erroneous example
To get started, let's return to our number guessing game — except this time we'll be exploring a version that has some deliberate errors introduced. Go to GitHub and make yourself a local copy of number-game-errors.html (see it running live here).

To get started, open the local copy inside your favorite text editor, and your browser.
Try playing the game — you'll notice that when you press the "Submit guess" button, it doesn't work!

Fixing syntax errors
Earlier on in the course we got you to type some simple JavaScript commands into the developer tools JavaScript console (if you can't remember how to open this in your browser, follow the previous link to find out how). What's even more useful is that the console gives you error messages whenever a syntax error exists inside the JavaScript being fed into the browser's JavaScript engine. Now let's go hunting.

Go to the tab that you've got number-game-errors.html open in, and open your JavaScript console. You should see an error message along the following lines:

[JS debugger](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger)

What are browser developer tools?
Every modern web browser includes a powerful suite of developer tools. These tools do a range of things, from inspecting currently-loaded HTML, CSS and JavaScript to showing which assets the page has requested and how long they took to load. This article explains how to use the basic functions of your browser's devtools.

