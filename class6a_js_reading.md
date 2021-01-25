# This is my reading from CODE-102 class 6 on Javascript

This is reading from the book JavaScript & jQuery by Jon Duckett

## Pages 43 - 69
### 1/c - How do I write a script for a web page?

- Three languages that are used to create web pages:
    - HTML, CSS, JS

- HTML - **content layer**, HTML gives the page structure and adds semantics
- CSS - **presentation layer**, CSS enhances teh HTML page with rules that state how the HTML content is presented.
- JS - **behavior layer**, this is where we can change how the page behaves.

*Progressive Enhancement* - a popular approachto building web pages using these 3 layers.

JS is added last and enhances the usability of the page or the experience of interacting with the site. Keeping it separate means that the page will still work if the user cannont load or run the JS.

#### Creating a basic Javascript

- JS is written in plain text
- Steps:
1. Create a folder to create a file, it is a text file ending in '.js'
2. Your css, js, images will all live in their own file folders to stay organized
3. The HTML *script* element is used to load the JS file into the page. It has an attribute called **src** whose value is the path to the script you created.
4. Open the HTML file in your browser. You should see the JS is functioning.
    - IE sometimes prevents JS runing when you open a page sotred on your hard drive. Chrome, Firefox, Opera, or Safari is recommended.

- Using Objects & Methods
- object        method
- ``document.write('Good afternoon!');``

- Javascript is run where it is found in the HTML
- When the browser comes across a ``<script>`` element, it stops to load the script and then checks to see if it needs to do anything.
- Be mindful as where the items are placed can affect the loading time of pages.


### Chapter 2 - Basic Javascript Instructions

- Variables - allow a script to temporarily store the bits of information it needs to do its job.
- *A Variable can change (or vary) each time a script runs.*
- The result is said to be *computed* or *caluclated* from the date stored in the variables.

**How to declare variables**
- Step 1: giving it a name, aka, *declare the variable*
- keyword      name
- ``var quantity;``
- Variable name - sometimes called an *identifier* if a variable name is more than one word it is usually written like, ``camelCase``.

**How to assign variables value**
- Once created you can *assign a value* to the variable.
- name    operator      value
- ``quantity = 3;``

**Data Types in JS** - numbers, strings, and true or false values (or boolean).
- Numeric Data Type - for tasks that involve counting or calculating sums, you will use numbers 0-9. You can use negative numbers and decimals
    - Ex. ``5272, -23678, 0.75``
- String Data Type - is enclosed between a pair of quotes. It can be single or double quote but they must match. Strings can be used when working with any kind of text. *Frequently used to add new content into a page.*
- Boolean Data Type - True or False. It's like an on/off switch. Are helpful when determining which part of a script should be run.

**Using a variable to store a string**
- Ex. ``username = 'Molly';``
- the variable is used to hold a string. The quote used must match on the opening and close.
- Sometimes you can use *double or single quote marks* ***within a string***
- *Escaping* Technque- is done by useing a **backwards slash** or backslash before any type of quote mark that appears within a string. The backwards slash tells the interpreter that the character is part of the string, rather than the end of it.
- **Booleans** - can appear as a *check* (true) or as an *x* (false)
- Shorthand can be used to create variables.
    - It can save you some time but make it harder to follow.

**Follow the 6 Rules for Naming Variables**
1. Names must begin with a *letter, dollar sign, or an underscore*
1. Do not use a dash or period in a variable name
1. You **cannot** use *keywords* or *reserved* words. For ex. var is a keyword used to declare a variable. Reserved words are ones that may be used in a future version of Javascript.
1. Case sensitive. Ex. score and Score would be two different variables.
1. Use a name that describes the kind of information that the variable stores. Ex. **firstName or lastName**
1. If your variable name is made up of more than one word, use a capital letter for the first word *after* the first word. You can also *underscore* between each word.
    
[<== Back to Readme](README.md)