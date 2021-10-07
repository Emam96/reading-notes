# Java Basics 

## Language Basics 

### Variables 

We can say that there are two main types of fields or variables used within a ava code: 

1. Instance Variables (Non-Static Fields): Instance variables (non-static variables) within a class are created  at run-time, meaning that we declare them inside the class and if their values changed it will be reflected inside the same class only and will affect other classes.

2. static field: are fields that are shared and used by all the objects and loaded when class is loaded. you declare one at the main class and use it with every copy.

&nbsp;

### Operators 

> Operators are special symbols that perform specific operations on one, two, or three operands, and then return a result.
[source](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/operators.html)

![op](https://www.j2eeonline.com/java-certification/module4/images/operator_precedence_2019.png)

&nbsp;

### Expressions, Statements, and Blocks


**Expressions** are lines of code contain variables and operators, work together to bring out a result, for example: 

`1 + 2` 

this is an expressions that uses the operator "+" to generate a new value.

**Statements** are a complete line of code than when we run it, we can have a final result and we alwa send it with a semicolon ";" 

`int result = 1 + 2;`

**Blocks** is a group of  more than one statements between balanced braces.

class BlockDemo {<br>
     public static void main(String[] args) {<br>
          boolean condition = true;<br>
          if (condition) { // begin block 1<br>
               System.out.println("Condition is true.");<br>
          } // end block one<br>
          else { // begin block 2<br>
               System.out.println("Condition is false.");<br>
          } // end block 2<br>
     }<br>
}<br>

&nbsp;


<hr>

## Compiling

Compiling simply means is to stick to the languages rules (syntax) so your machine can correctly read the instruction you wrote without any errors. 

<hr> 


&nbsp;


## Reading Java Documentation 

If you needed a refrence while coding with java, you can always go to stack overflow..., just kidding, you can always go [here](https://docs.oracle.com/javase/8/docs/api/), the Oracle documentation for java and search for anything you need. by going to the "Index" option and search for a key word for the method you are searching for and you will easly get the results. 


<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021


