# This is my reading from CODE-102 class 8 on Operators and Loops

This is reading from the book JavaScript & jQuery by Jon Duckett

## Part 1: Comparison and logical operators: 150-151, 156-157
## Part 2: For and While loops: 170-173 and 176

### Part 1 -

**Comparison Operators**
You can evaluate a situation by comparing one value in the script to what you might expect it might be. The result will be true or false (called a boolean).

Types:

- Is Eqaul To ``==``
- Is Not Equal To ``!=``
- Strict Equal ``===``
- Strict Not Equal To ``!==``
*It is typically preferable to use the strict form*

- Greater Than ``>``
- Less Than ``<``
- Greater Than or Equal To ``>=``
- Less Than or Equal To ``<=``

**Evaluating** the condition - the term programmers use to describe testing / checking a conditon.

- Conditions - usually result in a value of *true* or *false*
    - **Exceptions** - every value can be treated as true or false even if it is not a Boolean value
    - *In Short-Circuit Evaluation* - a condition might not need to run

**Logical Operators**
Allow you to compare the results of more than one comparison operator

Types:

- Logical AND ``&&``
    - Tests more than one condition
- Logical OR ``||``
    - Tests at least one condition
- Logical NOT ``!``
    - Takes a single boolean value and inverts it

**Short Circuit Evaluation**
- Logical expressions are evaluated left to right
- If the first condition can provide enough information to get the answer then no more evaluation is needed.

### Part 2: FOR and WHILE Loopes

**Loops**
Loops check a condition to evaluate if it's true. It will continue to run until the return is false.

**Three common types of Loops**

- **FOR** - to run code for a specific amount of time. The condition is ususally a counter.
- **WHILE** - if you don't know how long it should run for. It will continue to run until the condition is not true. The condition can be something other than a counter.
- **DO WHILE** - similar to the while loop BUT it will run the condition in the curly braces at least once, even if it evaluates to false.

**Conditions** - made up of three parts
1. Initialization - creat a variable and set it to 0. The variable is commonl called *i* and acts as the counter.
    Ex. ``var i = 0;``
2. Condition - the loop should continue to run until the counter reaches a specified number.
    Ex. ``i < 10;`
3. Update - Every time the loop has run the statements in the curly braces, it adds one to the counter.
    Ex. ``i++``
    You can also count downwards using the decrement operator ``i--``

**While Loops**
- Each time the loop is run, another calculation is written into the variable
- The loop will continue to run as long as the condition in the parentheses is true.
- A typical use of the while loop is when you do not know how many times you want the code to run; it should run until the conditions are met.

[<== Back to Readme](README.md)