# HTML TEXT & CSS & JS

This a summary of what I have learned reading Jon Duckett's material.

## HTML TEXT

We learned about HTML in general and know we will discuss the text application in details

>When creating a web page, you add tags (known as markup) to the contents of the page. These tags provide extra meaning and allow browsers to show users the
appropriate structure for the page.                &nbsp;
 **Jon Duckett**

&nbsp;

So, adding text is like structuring the page, some tags affect the page structure and others don't, they add extra info to the page so the browser can know what this line means. the first type is called Structural markup whereas the second called Semantic markup

* **Structural markup**: Tags that affect the page structure.
* **Semantic markup**: Tags that give extra meanings.

&nbsp;

### TAGS

#### closing tags

1. **headers**: headers work as titles for paragraphs and can, there are 6 levels of headers. the biggest one is **H1** down to **H6**.
2. **paragraphs**: they are text boxes that you can add to the page.
3. **< b >**: used to make a text bold
4. **< i >**: used to make a text italic
5. **< sup >**: used to contain characters that should be superscript such
as the suffixes
6. **< sub >**: used to contain characters that should
be subscript.

#### empty tags

1. **< br/ >** : used to make a new line after the world it placed after.
2. **< hr/ >** : used to create a break between paragraphs.

&nbsp;

## CSS

>CSS allows you to create rules that specify how the content of an element should appear.                &nbsp;
 **Jon Duckett**

&nbsp;

First, we need to know what is CSS stands for, it's simply a styling tool, while HTML structure the webpage, CSS presents it with the design.

&nbsp;

The CSS code is simple, let us look at the components and describe each:

           h1 {
             font-size: 5pc;
           }

h1 is the **Selector** a Selector indicate which element the rule applies to. and they are the same tags in the HTML code.
   &nbsp;The **Declaration** is contained within brackets, the font-size is the **Property** it indicates the aspects of the element you want to
change, then you have the **Value** set by 5pc so the text size will be exactly as indicated.

   &nbsp;

There are 3 types that you can add CSS lines to the HTML file:

* External CSS
* Internal CSS
* Inline CSS

&nbsp;

1. **The External CSS** means that you define a sole file just for the CSS so you can implement its command to the whole page, and you need to connect to the HTML page using:

* `<link rel="stylesheet" href="mystyle.css">`

&nbsp;

2. **The internal CSS** means that you can assign a special unique style for one page and type it between the HTML code using `<style>`

&nbsp;

3. **The Inline CSS** allows you to assign one single element with some special attributes by adding in inside the same tag, for example:

* `< h1 style="color:blue;text-align:center;">This is a heading </h1>`

&nbsp;

## JavaScript

JavaScript is one of many programming languages used with HTML and CSS to accomplish a webpage, but what is JavaScript, and why we use it?

>JavaScript is a scripting or programming language that allows you to implement complex features on web pages  
&nbsp;
**Mozilla and individual contributors**

&nbsp;

 JavaScript is implemented by lines of code called statements, codes are intended to apply specific commands to run a program at the webpage, there are many types of those programs and can be triggered in many ways also.

 JavaScript is written in the shape of scripts.
 > A script is a series of instructions that a
a computer can follow to achieve a goal
 &nbsp;
  **Jon Duckett**

You can set some steps and instructions and code each one to perform a certain task, using the right JavaScript syntax and an assigned group of objects with some Properties.

The syntax is simple, for example, you want to assign a value for a variable:

`var userName = "Emam";`

* Here you can notice that **var** is used to identify that **userName** is a variable that we use var to declare variables.

* **userName** is an **identifier**, it is a sequence of characters in the code that identifies a variable, function, or property. In JavaScript, identifiers are case-sensitive and can contain Unicode letters, and digits, but may not start with a digit.

* **(=)**, is an **operator**, An operator performs some operation on single or multiple operands (data value) and produces a result.

* You can see that we used **"Emam"** as a value to our variable, this value is called string because it's written between quotation marks. Data types can include:  

&nbsp;

   1. Numbers = var HQ = 66;

   2. String = lastName = "Bond"; .... James Bond.

   3. BOOLEAN  = it can be true or false and it can perform as an on/off switch.

&nbsp;

### ARRAYS

>An array is a special type of variable. It doesn't just store one value; it stores a list of values.
&nbsp;
  **Jon Duckett**
  
As told, an array can hold multiple values for one variable, its useful and saves time.

`var colors; colors= ['white ' ,
'black ' ,
' green'];`
The values are assigned to the array inside a pair of square brackets, and each value is
separated by a comma.

&nbsp;

## Expressions and Operators

&nbsp;

The programming operation with JavaScript requires some tools to be done:

* Operators
* Expression

&nbsp;

&nbsp;

* **Operators** An operator performs some operation on single or multiple operands (data value) and produces a result. there are many types of Operators:

1. Assignment operators
2. Comparison operators
3. Arithmetic operators
4. Bitwise operators
5. Logical operators
6. String operators
7. Conditional (ternary) operator
8. Comma operator
9. Unary operators
10. Relational operators

&nbsp;

* **Expression** an expression is a snippet of code that evaluates to a value.

1. the Expression
2. Arithmetic
3. String
4. Logical
5. Primary expressions
6. Left-hand-side expressions

&nbsp;

## Logical operators

&nbsp;

We can use Logical operators to make the code more readable and to merge many IF statements in one function:

* && the AND operator.

 > Returns expr1 if it can be converted to false; otherwise, returns expr2. Thus, when used with Boolean values, && returns true if both operands are true; otherwise, returns false.

* || the OR operator

>Returns expr1 if it can be converted to true; otherwise, returns expr2. Thus, when used with Boolean values, || returns true if either operand is true; if both are false, returns false.

* ! logical NOT

>Returns false if its single operand that can be converted to true; otherwise, returns true.

&nbsp;

&nbsp;

&nbsp;

## LOOPS

Loops make it easier to repeat a function, for now, we will mention 2 types of loops. they are:

1. FOR loop  we use when we want to perform a task for a known number of times  `for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement`

2. WHILE loop we use this when we want to repeat the action for an unknown number of times `while (condition)
  statement`

&nbsp;

## IF statement & SWITCH statement

**iF statements** check a condition, and execute the code given if the the value is true.

![if](https://cdn.programiz.com/sites/tutorial2program/files/java-if-working.png)

&nbsp;

**SWITCH statement** given a "switch value" and a number of "cases", a number of codes is ready to be executed if any of those cases values matched the input.

![switch](https://bytesofgigabytes.com/IMAGES/java/Switch/GeneralFormOFSwitch.png)
&nbsp;

We connect our JavaScript code to the index by adding

&nbsp;
 `<script src="script.js"></script>`  

anywhere within the HTML code, and the code will be performed at the same spot when viewing the page and running the program.

&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021
