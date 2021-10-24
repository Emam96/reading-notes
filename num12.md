# Spring RESTful Routing & Static Files

## Request Mapping Basics

In Spring MVC applications, the RequestDispatcher (Front Controller Below) servile is responsible for routing incoming HTTP requests to handler methods of controllers.

When configuring Spring MVC, you need to specify the mappings between the requests and handler methods.
The class-level annotation maps a specific request path or pattern onto a controller. You can then apply additional method-level annotations to make mappings more specific to handler methods.

## JPA (Java Persistence API)

 JPA is a specification. It is a collection of classes and methods to persistently store the vast amounts of data into a database. It provides common prototype and functionality to ORM tools. By implementing the same specification, all ORM tools (like Hibernate, TopLink..) follows the common standards.

 ## CrudRepository VS JPA repository
 
 CrudRepository and JPA repository both are the interface of the spring data repository library. Spring data repository reduces the boilerplate code by providing some predefined finders to access the data layer for various persistence layers.

JPA repository extends CrudRepository and PagingAndSorting repository. It inherits some finders from crud repository such as findOne, gets and removes an entity. It also provides some extra methods related to JPA such as delete records in batch, flushing data directly to a database base and methods related to pagination and sorting.

We need to extend this repository in our application and then we can access all methods which are available in these repositories. We can also add new methods using named or native queries based on business requirements.

![dif](https://i.stack.imgur.com/hTg7t.png)



<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021