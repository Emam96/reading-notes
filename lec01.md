# Introduction to React and Components

## Component Based Architecture

![comp](https://dev.mobify.com/v2.x/static/9b9e13e7763441f8f729add3b49a9805/ebf47/react-components.png)

### 1. What are Components? 

Components are units you create and use to build web applications, a web page can be made from multiple components that are grouped together inside a parent component that will render a completed page or application, for example, the nav bar can be a separate component as well as the cover or the footer of a web page. 

&nbsp;



### 2. What are the characteristics of a component?

*  **Reusability** − Components are  designed to be reused in more than one project.

* **Replaceable** − they can be replaced by better integrated components.

* **Not context specific** − Components are designed to operate in different environments and contexts.

* **Extensible** − A component can be extended to perform a new task or an improved one.

* **Encapsulated** − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

* **Independent** − Components are designed to have minimal dependencies on other components.

&nbsp;



### 3. What are the advantages of using component based architecture?

* **Ease of deployment and development** − the ability to update and improve some parts without redoing the whole project or impacting other parts of it.

* **Reduced cost and Reusability**[1] − using prepared components reduce the cost of development.

* **Modification of technical complexity** − A component modifies the complexity through the use of a component container and its services.

* **Reliability** − The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.

* **System maintenance and evolution** − Easy to change and update the implementation without affecting the rest of the system.

* **Independent** − Independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development.


&nbsp;

<hr>

##  What is Props and How to Use it in React

### 1. What is props short for? 
They stand for 'properties', its a special keyword in react and its used for data flow in react. 

&nbsp;


### 2. How are props used in React?

First you define an attribute and its value Then pass it to child components by using Props, after that, you render the Data that you passed earlier.


&nbsp;


### 3. What is the flow of props?

Uni-directional flow. (one way from parent to child), meaning that the data only goes in one direction from the parent component that includes the child's (the components inside it) and its good to mention that the [2] data  is read-only, which means that data coming from the parent should not be changed by child components.

![props](https://www.kirupa.com/react/images/color_property_144.png)

&nbsp;

[1] tutorials point - component based architecture <br>
[2] itnext - what is props and how to use it in react
<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021