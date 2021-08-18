# In memory storage

## Understanding the JavaScript Call Stack

&nbsp;


### 1.  What is a ‘call’?

function invocation.


&nbsp;


### 2.  How many ‘calls’ can happen at once?

one, since the javascript engine is single-threaded.


&nbsp;


### 3.  What does LIFO mean?

Last In, First Out (LIFO), which temporarily stores and manages function invocation (call), and solves the last function that was called .

&nbsp;


### 4.  Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.


to get this error in console 

![error message](https://i.imgur.com/kQ6XHy5.png)

will look like this 

```
function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();
```


&nbsp;


### 5.  What causes a Stack Overflow?

the function that calls itself without the need of an exit point.

&nbsp;


<hr />

## JavaScript error messages


<br />

### 1.  What is a ‘reference error’?

It's when you try to reference something that wasn't declared yet.


&nbsp;


### 2.  What is a ‘syntax error’?

this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.


&nbsp;


### 3.  What is a ‘range error’?

Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

&nbsp;


### 4.  What is a ‘type error’?

this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

&nbsp;


### 5.  What is a breakpoint?

It's where the code will stop when you are debugging it.

&nbsp;


### 6.  What does the word ‘debugger’ do in your code?

add a breakpoint.

&nbsp;



<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021