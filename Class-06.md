# Problem Domain & JS Objects and DOM

This a summary of what I have learned reading Jon Duckett's material.

## Problem domain 

So, a client asked you to make a program that shows motivational quotes every day on his blog, you made the code and it works by taking some quotes from random websites that offer the same thing and change the font to show it to the client's page, the client did not like the design and refuse to pay you because you "missed up".<br>
You may want to rethink the reasons that made the client unhappy, Except that he's an idiot. You did not take the time needed to ask him about some details like the type of quotes he wants or the color of the font.<br>
Let's say that he did not give a clear description about what he wanted in the first place, he just want the blog to be "fresh" every day, in that case, Except making a dumb joke about refreshing his page, you need to discuss his query and try to take notes. hoping that it may help you later.

&nbsp;


>If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things: 
>1. Make the problem domain easier
>2. Get better at understanding the problem domain



 
&nbsp;


  <hr>

## JS Objects 
>Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world.

Objects are made of variables and functions and they are used to accomplish an action, the variables inside an objects named **property** and the functions are named **Methods**, lastly, the values assigned for each property are called **Keys**.



**const person** = {<br>
  **firstName**: "John",<br>
  **lastName** : "Doe",<br>
  **id**       : 5566,<br>
  **fullName** : function() {<br>
    return this.firstName + " " + this.lastName;<br>
  }<br>
};


We create objects by declaring a variable with the name of the object and then add the properties and assign keys to them, finally setting a method to run the object.

Here you can see an object that returns the full name using the properties it holds **firstName** is a property and **"John"** is the key for that property, finally the method is **fullName** that process the inputs inside the object.


![box](https://sunilsandhu.com/assets/post-content/array-object-performance.png)

&nbsp;

<hr>

## DOM

>he Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web.

&nbsp;

### Nodes and Nodes types 
Every object located within a document is a node of some kind. In an HTML document, an object can be an element node but also a text node or attribute node.


&nbsp;


![box](https://www.codeguage.com/Images/js/node-tree.png)


&nbsp;


* **THE DOCUMENT NODE** At the top of the tree a document node is added; it 
represents the entire page
* **ELEMENT NODES**   elements 
* **ATTRIBUTE NODES** The opening tags of HTML elements can carry 
attributes and these are represented by attribute nodes in the DOM tree.
* **TEXT NODES** you can then reach the text within that element. This is stored in its own text node. 


&nbsp;


### Accessing elements
You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax. 

* **METHODS THAT RETURN A SINGLE ELEMENT NODE:** <br>

`getElementByld('id')` Selects an individual element given the value of its ID attribute. The HTML must have an ID attribute in order for it to be selectable. 
 
`querySel ector('css selector') ` Uses CSS selector syntax that would select one or more elements. This method returns only the first of the matching elements. 


* **METHODS THAT RETURN ONE OR MORE ELEMENTS (AS A NODELIST):** <br>

`getElementsByClassName('class') `
Selects one or more elements given the value of their class attribute. 
The HTML must have a class attribute for it to be selectable. 


`getEl ementsByTagName('tagName') `
 Selects all elements on the page with the specified tag name. This method is faster than querySe 1ectorA11 (). 
 
 
 `querySelectorAll ('css select or•) ` Uses CSS selector syntax to select one or more elements and returns all 
 of those that match. 

&nbsp;


When a DOM method can return more than one element, it returns a 
Nodelist (even if it only finds one matching element).

>A Nodelist is a collection of element nodes. Each 
node is given an index number (a number that starts 
at zero, just like an array).

The item() method returns a specific node from 
the Nodelist when you tell it the index number 
of the item that you want (in the parentheses). 
However, it is more common to use array syntax 
(with square_brackets) to retrieve an item from a 
Nodelist 

&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021