# Passing Functions as Props

## React Docs - lists and keys

1. What does .map() return?

It returns a new array with a new values of manipulated inputs using a function inside the method.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

First, we use the .map() method to render data then Parse and display data in an array of objects.

3. Each list item needs a unique **Key**

4. What is the purpose of a key?

Help React identify which items have changed, are added, or are removed.

<hr>

## The Spread Operator

1. What is the spread operator?

The use of (...) three dots to transform objects into arguments.

2. List 4 things that the spread operator can do.

* Copying an array
* Using Math functions
* Adding an item to a list
* Combining objects

3. Give an example of using the spread operator to combine two arrays.

const hello = {hello: "😋😛😜🤪😝"}<br>
const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}<br>
const helloWorld = {...hello,...world}

4. Give an example of using the spread operator to add a new item to an array.

const fruits = ['🍏','🍊','🍌','🍉','🍍']<br>
const moreFruits = [...fruits];<br>
fruits[0] = '🍑'

5. Give an example of using the spread operator to combine two objects into one.

const objectOne = {hello: "🤪"}<br>
const objectTwo = {world: "🐻"}<br>
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}

<hr>

## How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?

He set state outside to handle and pass the function to other components.

2. In your own words, what does the increment function do?

It target the count value and update it every time you click on the button.

3. How can you pass a method from a parent component into a child component?

Using props.

4. How does the child component invoke a method that was passed to it from a parent component?

By passing it using a prop. 


&nbsp;



&nbsp;



&nbsp;


<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021