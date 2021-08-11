# Putting it all together

## React Docs - thinking in React


![react](https://survivejs.com/950d04f6f2ce70288627835f007bb9eb.png)


### 1. How would you break a mock into a component hierarchy?

you can divide each component by a container or draw a box around, you should know how to separate individual component, as every component needs to do only one activity.

&nbsp;


### 2. What is the single responsibility principle and how does it apply to components?

That a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller sub-components.

&nbsp;


### 3. What does it mean to build a ‘static’ version of your application?

 To make a model and render it without interactivity, we do this by making components and pass data using props. props are a way of passing data from parent to child, we only use props because the static version is not interactive.

&nbsp;


### 4. Once you have a static application, what do you need to add?

We need to make the app interactive by using "state", to pass interchangeable data and functions.

&nbsp;


### 5. What are the three questions you can ask to determine if something is state?

* Is it passed in from a parent via props? If so, it probably isn’t state.
* Does it remain unchanged over time? If so, it probably isn’t state.
* Can you compute it based on any other state or props in your component? If so, it isn’t state.
[1]


&nbsp;


### 6. How can you identify where state needs to live?

First, we need to identify every component that renders something based on that state, then we
find a common owner component.

&nbsp;



<hr>

## Things I want to know more about

### 1. I want to read more about applying CSS to react files. 

### 2. More knowledge about react state and how to place them. (this reading was helpful TBH).

&nbsp;



&nbsp;
[1] reactjs.org / Thinking in React


<hr>
&nbsp;
&nbsp;



Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021