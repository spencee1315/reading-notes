# This is my reading from CODE-102 class 6 on Javascript

This is reading from the book JavaScript & jQuery by Jon Duckett

## Intro + Scripts: 1 - 24

**Javascript makes pages more interactive**

Things you can do:
1. Access content - you can use JS to select any element, attribute, or text from an HTML page
        - 
2. Modify content - you can add to  elements, attributes, and tex to the page.
        - size/position of an image
        - value of a class
        - add a paragraph after the first ``<h1>`` element
3. Program Rules - specify a set of steps for the browser to follow which allows it to access/change the content of a page.
        - calc from a form
        - script checking on which image a person clicks
        - animation to the page
4. React to Events - you can specify that a script shoud run when a specific event has occured

Ex of JS

- Slideshow
- Forms
- Reload Part of a Page
- Filtering Data

- All these rely on the ability to:
    - *Access* the content of a page
    - *Modify* the content of a page
    - *Program* rules or instructions the browser can follow
    - *React* to events triggered by the user or browser

### ABC's of Programming 

**A Script is a series of instructions**
Ex. Recipes, Handbooks, Manuals, putting on a sweatshirt

**To write a Script**
- State your goal
- List the tasks that need to be completed in order to achieve it
    - Design the script -split the goal into a series of tasks. This can be respresented in a flowchart.
        - Flow chart
        - List of steps: 1) Action 2) Action 3) Action 4) Action
    - Code each step

Learning the CPU language
    - Vocabulary the computer understands
    - Syntax - how you put the words together to creat instructions cpu can follow

Computers use the **Programmatic** approach to problem solving - they follow a series of instrucitons.


## Expressions + Operators: 74 - 79

### Expressions 
*Evaluates into a single value*

Two types of expressions:

1. That just assign a value to a variable
    - Ex. ``var color = 'beige';``
    - when you first declare a variable using the var keyword, it is given a special value of undefined. Then you assign a value to it.
2. That use two or more values to return a single value
    - Ex. ``var area = 3 * 2;``
    - this uses the assingment operator, the expression 3*2 is stored in a variable named area


### Operators
*Expresions rely on operators*
*Operators allow programmers to create a single value from one or more values*

- Types of Operators
- Assignment Operators
    - Assign a value to a variable

    - 
- Arithmetic Operators
    - Perform basic math

    - Multiple can be performed in one expresson but there is an order:
    - Multiplication and division are performed before addition or subtraction
    - Using parentheses can be important to obtain the right result

- String Operators
    - Combine two strings

    -There is one string operator the ``+``
    - *Concatenation* - process of joining together two or more strings into one new string
    - Parentheses around numbers turns them into strings / cannot to mathematical operations
    - Adding a number to a string, the number becomes apart of the string
    - **NaN** - not a number, trying to use any arithmetic operator on a string. 
- Comparison Operators
    - Compare two values and return a true/false
- Logical Operators
    - Combine Expressions and return true/false


## Functions: 88 - 94

What is a function?
- Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function.
- Calling the function - asking it to perform it's task
- Parameters - pieces of information passed to a function
- Return Value - when you write a function and expect it to provide an answer

- Name/Value pairs - programming languages rely upon these

**Creating a Function**
- To create a function, perform a *Function Declaration*
    - Give it a name
    - Then write the statements needed to achieve its task inside the curly braces.
    -       keyword   name
    - Ex. ``function sayHello() { document.write('Hello!');}``

- *Call a Function*
    - After declaring a function you can execute the statements between the curly braces with one line of code.
    - Aka - the code calles the function
    -       function name
    - Ex. ``sayHello();``
    
- Some functions need **information** or **parameters** inside the function the parameters act like variables.
-                       parameters      
- Ex. ``function getArea(width, height) { return width * height; }``
                                        the parameters are used like variables in the function
- When you call a function with parameters, you specify the values it should use in the parentheses that follow its name. The values are called **arguments**

- Arguments as values
    - ``getArea(3, 5)``
    - when the function is called the number 3 is the width, 5 is the height

- Argumnents as variables
    - ``wallWidth = 3;``
    - ``wallHeight = 5;``
    - ``getArea(wallWidth, wallHeight);``
    - you do not have to specify actual values when calling a funtion - you can use variables in their place. This example does that

***Paramters vs Arguments***
Parameters-
- Words that act as variables.

    - Ex. In the first example above. *Width* and *Height* used, inside the curly braces of the funtion act as variables. These names (width and height) are parameters.

Arguments-
- Values that you pass into the code (the information it needs to perform the calculation)

    - Ex. In the second examples. information inside the getArea() function is being called and the code specifies real numbers that will be used to perform the calculation (or variables that hold real numbers).

**Getting A Value Out of a Function**
- Some functions return information to the code that called them.

    - Ex. ``calculateArea()`` function returns the area of a rectangle to the code.
    - A var ``area`` holds the calculated area of the box.
    - ``return`` keyword is usde to return a value to the code that called the function

    ``function calculatedArea(width, height)`` 
    ``{var area = width * height;``
    `` return area;``
    ``}``
    ``var wallOne = calculatedArea(3, 5);``  (15)
    ``var wallTwo = calculatedArea(8, 5);``  (40)

    
[<== Back to Readme](README.md)