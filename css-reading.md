# This is my notes on CSS

Readings Notes found here a from the book:
![HTML & CSS design and build websites, by Jon Duckett]( https://img.thriftbooks.com/api/images/m/42286e8944500ef27a6e5a777b7b95c27953d150.jpg "HTML and CSS: Design and Build Websites by Jon Duckett" alt"HTML&CSS desing and build websites by Jon Duckett")

## Today's Chapters:
1. Chapter 10: Introducing CSS
1. Chapter 11: Color


### Chapter 10: Introducing CSS
1. **What is CSS?**

CSS stands for cascading style sheets. It makes your site pretty, adds style to the functional elements (HTML) of your site.

**The Key: to understanding how CSS works is to imagine that there is an invisible box around every HTML element.**

Understand block vs inline elements.


- Block level elements look like they start on a new line


 Ex: \*<h1>, <p>, <div>\*
    
    

- Inline elements flow within the text and do not start a new line.


 - Ex.:
   \*<b>, <i>, <img>, <em>, <span>\*
   

CSS allows you to create rule that control the way each individual box (and the contents of that box) is presented.

CSS works by associating rules with HTML elements. A CSS rule contains two parts: a *selector* and a *declaration*.
Ex:

selector    declaration
css
    p {
    font-family: Arial;
    }


The declaration sits inside curly brackets and each is made up of two parts: a property and a value. You can specify several properties in one delcaration, each separated by a semi-colon.

Ex. h1, h2, h3 {
            font-family: Arial;
            color: yellow;
            }

Using External CSS vs Internal CSS

- External: 
Ex. \*<link href="css/styles.css" type="text/css" rel="stylesheet" >\*


The link element can be used in an HTML doument to tell the browser where to find the CSS.

An HTML page can use more than one CSS style sheet. To do this it could have a link element for every CSS file it uses. EX. one CSS file to control the presentation (such as fonts and colors) and a second to control the layout.

- Internal: 
Ex. \*<style type="text/css">\*


Benefits to an External- 
Wen building a site with ore than one page, you should use an eternal style sheet:

- Allows all pages to use the same style rules (rather than repeating them in each page)
- Keeps the content separate from how the page looks.
- Means you can change the styels used across all pages by altering just one file (rather than each individual page)

***Watch out: CSS can be a time suck because you can never git it perfect. Always to a minimal amount of HTML / CSS, get in functional on JS then go back and polish up the CSS.***


### Chapter 11: Color

- Foreground Color
1. color - color property allows you to specify the color of text inside an element
1. RGB Values - *{color: rgb(100,100,90);}* these express colors in teresm of how much red, green and blue is used to make it up
1. Hex Codes - {color: #ee3e80;} six digit codes that represent the aount of red, green, and blue are present.
1. Color Names - there are 147 predefined color names recognized by browsers. Ex. DarkCyan

- Background Color - CSS treats each TML element as if it appears in a box, and the *background-color* property sets the color of the backgroud for that box.

Things to consider when choosing color:
* Contrast - when picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.
    * Text is easier to read when there is higher contrast between the background and foreground colors.
    * If the text is revesed out (a lighter color on a darker background) the height or spacing between the lines can be increased and the weight of the font can be increased to make it easier to read.
* Opacity - a property in CSS3 that allows you to specify the opacity of its child elements. The vlue is a number between 0.0 and 1.0.
* rgba - is a property in CSS3 that allows you to specify a color, just like you would with an RGB value but adss a fourth value to indicate opacity ***rgba(0,0,0,0.5)***. It will only affect the element it is on (not the child elements)
* CSS3: HSL Colors
* HUE - the colloquial idea of color. Represented asa color circle, where the angel represents the color. 0-360.
    * Ex.: {background-color: hsl(0,0%,78%);}
    * Ex. 2: hsla {background-color: hsl(0,0%,78%,0.5);}
    
* Saturation - 0% is a shade of gray, 100% is full saturation
* Lightness - 0% is black, 100% is white     


Another good example of the power of CSS:
[CSS Zen Garden](http://www.csszengarden.com/)


[<== Back to Readme](README.md)