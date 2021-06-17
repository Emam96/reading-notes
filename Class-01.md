#   HTML & JS
This a summary of what I have learned reading Jon Duckett's material.

We are learning how to design and develop web pages, but what are those web pages anyway?

>A web page (or webpage) is a hypertext document provided by a website and displayed to a user in a web browser. A website typically consists of many web pages linked together in a coherent fashion. The name "web page" is a metaphor of paper pages bound together into a book. The core element of a web page is one or more text files written in the Hypertext Markup Language (HTML). Many web pages also make use of JavaScript code for dynamic behavior and Cascading Style Sheets (CSS)                &nbsp;   
 **Wikipedia**



So, a webpage is a combination of markup languages and sometimes a program, powered with one or more than one type of programming language. 
It's all displayed using a browser, when you want to view a certain webpage, your browser asks the server to show the contents of a certain page and once it gets the permission, it will be displayed.





&nbsp;



## HTML
First, we need to know what is HTML stands for, it's a language used to structure a web page and its content.





&nbsp;



HTML codes use TAGS, tags are used to give a specific form for a line on the webpage, any line between tags called ELEMENT, for example:
- `<p>My name is Emam.</p>`
&nbsp;   
tags arent visible on the page so what will be showen is `My name is Emam`

Also, you can add Attributes to your tag, 
>Attributes provide additional information 
about the contents of an element. They appear 
on the opening tag of the element and are 
made up of two parts: a name and a value, 
separated by an equals sign.                                    
 &nbsp; 
  **Jon Duckett**

 &nbsp; 

In general, we will use the (ID) & (CLASS) Attributes the most, as we will use CSS to style the rest. 

* `<p class="main somthing" > this is a main stuff <p>`
here, we can call the class later in the style-sheet to make our adjustments.




&nbsp;



#### MAIN TAGS

1. **<!DOCTYPE html>** — it act as links to a set of rules that the HTML page had to follow to be considered good HTML.
2. **<html></html>** — the <html> element. This element wraps all the content on the entire page.
3. **<head></head>** — the <head> element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers.
4. **<title></title>** — the <title> element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. 
5. **<body></body>** — the <body> element. This contains all the content that you want to show to web users when they visit your page, and it contain another sub tags,header, main and footer.



&nbsp;


&nbsp;

#### OTHER TAGS
1. **<div>** div is a grouping tag that allows you to include many elements inside a block-level box. and it can take an attribute like an ID or a class. 
2.  **<a>**  you can use this tag to create linksm for example,   &nbsp;    &nbsp;

     &nbsp;
            `<a href="https://github.com/Emam96">Emam96</a>` will create a link to take you to my github page.           
  
  3.  **<img>** here, you can add images to your page, by adding the image path you can make it appear on the page, the format should be like this: 
  `<img src="url" alt="note">`         
  


&nbsp;



#### LAYOUT 

We mentioned earlier that the (div) is a grouping element, what is that mean? we use this element and many more to control the page layout or how it will be displayed, how many blocks, and what every block contains. 

&nbsp;


![layout](https://www.logicify.com/media/filer_public/88/72/88722592-b71c-47d1-aadb-25643aca6821/schematic_representation_of_semantics_in_a_page_layout.png)

&nbsp;

We  use elements such as `<div> <nav> <article> <header> <main> <footer> <aside>` to divide our page into blocks or sections, making it esier to style and to define special attributes to every block. &nbsp;

Sometimes, we want to make the <nav> or the navagation bar to hold still on top even if we scrolled down the page, so we add the commands to a single section by using the elemnt <nav>.  




&nbsp;

## JavaScript 

JavaScript is one of many programming languages used with HTML and CSS to accomplish a webpage, but what is JavaScript, and why we use it?

>JavaScript is a scripting or programming language that allows you to implement complex features on web pages  
&nbsp;
**Mozilla and individual contributors** 

&nbsp;
 
 JavaScript is implemented by lines of code, codes are intended to apply specific commands to run a program at the webpage, there are many types of those programs and can be triggered in many ways also. 

 JavaScript is wrote in a shape of scripts. 
 > A script is a series of instructions that a 
computer can follow to achieve a goal       
 &nbsp; 
  **Jon Duckett** 

You can set some steps and instructions and code each one to perform a certain task, using the right JavaScript syntax and an assigned group of objects with some Properties. 

The syntax is simple, for example, you want to assign a valude for a varibale: 

`var userName = "Emam";` 

* Here you can notice that **var** is used to identify that **userName** is a variable that we use var to declare variables.

* **userName** is an **identifier**, it is a sequence of characters in the code that identifies a variable, function, or property. In JavaScript, identifiers are case-sensitive and can contain Unicode letters, and digits, but may not start with a digit.

* **(=)**, is an **operator**,An operator performs some operation on single or multiple operands (data value) and produces a result.

* You can see that we used **"Emam"** as a value to our variable, this value called string because it's written between quotation marks. Data types can include:  

   1. Numbers = var HQ = 66;

   2. String = lastName = "Bond"; .... James Bond.

   3. An Object itself  = var x = {firstName:"John", lastName:"Doe"}; 



We connect our JavaScript code to the index by adding 

&nbsp;
 `<script src="script.js"></script>`  

anywhere within the HTML code, and the code will be performed at the same spot when viewing the page and running the program.

&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021