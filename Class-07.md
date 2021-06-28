# HTML Tables & JS Constructor Functions

This a summary of what I have learned reading Jon Duckett's material.

## HTML Tables

Its super simple, you can add tables to your page structure by using the table tags, The `<table>` tag defines an HTML table.

Each table row is defined with a` <tr>` tag. Each table header is defined with a `<th>` tag. Each table data/cell is defined with a `<td>` tag.

By default, the text in `<th>` elements are bold and centered and the text in `<td>` elements are regular and left-aligned.


`<tr>` <br>
    `<th>Firstname</th>`<br>
    `<th>Lastname</th>`<br>
    `<th>Age</th>`<br>
  `</tr>`<br>
  `<tr>`<br>
    `<td>Jill</td>`<br>
    `<td>Smith</td>`<br>
    `<td>50</td>`<br>
  `</tr>`<br>
  `<tr>`<br>
    `<td>Eve</td>`<br>
    `<td>Jackson</td>`<br>
   ` <td>94</td>`<br>
 ` </tr>`



This should appear like this at the page 

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>

&nbsp;




 
&nbsp;


  <hr>

## Constructor Functions

Basically, the Constructor Functions raise to its name, its literally construct objects, If you have a big number of objects, it wont be smart to use the literal object way.

So, instated of creating many objects, we create one function that will create for us the objects without filling the memory with unnecessary code

![box](https://miro.medium.com/max/756/1*pp_oBq5mUaxOcyTiT3cnZQ.png)
![box](https://miro.medium.com/max/756/1*FV5pGUFrVhshmxQI9WdsuA.png)



function Person(first, last, age, eye) {

  **this.firstName**= first;<br>
  **this.lastName** : "Doe",<br>
  **this.color**       : eye;<br>
 
};

* **This** we use this so we can generalize those properties on every object we create
*  **new** we use new to create objects, for example `const myFather = new Person("John", "Doe",  "blue");` here, we crated this object and assigned the properties for it.


This is how we converted the properties into general assigned items that we can change from object to object. 

If there were methods, we can add them by using `prototype`
For example: 
`Person.prototype.getAvgCst = function (min, max) {
  this.avgCst = Math.floor(Math.random() * (max - min + 1) + min);
};` this method provides a random number you can call it age.




&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021