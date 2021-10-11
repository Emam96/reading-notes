# Maps, primitives, File I/O

## Java Primitives versus Objects

The primitive types are  faster and require less memory than objects.

&nbsp;

**Primitive Data Type**: a data types that specify the size and type of any standard values. you can use from:

* byte
* short
* int
* long
* float
* double
* char
* boolean

 When they are used, a copy of the variable is created and changes made to the copied variable will not reflect changes in the original variable.

&nbsp;

**Object Data Type**: These are also referred to as Non-primitive. They are so-called because they refer to any particular objects. Unlike the primitive data types, the non-primitive ones are created by the users in Java. Examples include `arrays, strings, classes, interfaces`.

<hr>

## Exceptions

### What Is an Exception?

An exception is a problem that arises during the execution of a certain code in java. When an Exception occurs the normal flow of the program is disrupted and the program/Application terminates abnormally, which is not recommended, therefore, these exceptions needs to be fixed before any other execution.

### The Catch or Specify Requirement

To write solid code in Java you must use the catch or specify requirement. This means that we can foolproof our code from exceptions in 2 ways.

1. try statement : the try statement catches the exception with an appropriate exception handler.

2. throws statement : A method that specifies it can throw a exception must specify the throws clause in the method signature.

There are 3 types of exceptions in Java:

1. Checked exceptions : these are exceptions that your application should be able to recover from.

2. Errors : errors are a type of unchecked exception that happens externally to our application.

3. Runtime Exceptions : these are exceptions that happen internally to our application.

### Catching and Handling Exceptions 

The try-catch is the simplest method of handling exceptions. Put the code you want to run in the try block, and any Java exceptions that the code throws are caught by one or more catch blocks. This method will catch any type of Java exceptions that get thrown. This is the simplest mechanism for handling exceptions.

<hr>

## Using Scanner to read in a file in Java

Scanner is a class in java. util package which can parse primitive types and strings using regular expressions. It can read text from any object which implements the Readable interface. We can also construct a Scanner that produces values scanned from the a chosen file.


<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021