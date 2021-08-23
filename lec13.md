# CRUD

## Status Codes Based On REST Methods 

### 1.  In your own words, describe what each group of status code represents:
  * 100’s = for information only, like if the server can't accommodate what the client is asking.
  * 200’s = success codes, tells the client the request was accepted.
  * 300’s = these tell the client that the information they want is no longer available there, and redirects them.
  * 400’s = error codes.
  * 500’s = error codes, but for the server.



&nbsp;


### 2. What is a status code 202?

the request met all validation requirements at the time of sending

&nbsp;


### 3.  What is a status code 308?

 This tells the client to use another URL to access the resource and not use the current URL anymore.

&nbsp;


### 4. What code would you use if an update didn’t return data to a client?

204 

&nbsp;


### 5. What code would you use if a resource used to exist but no longer does?

410 

&nbsp;


### 6. What is the ‘Forbidden’ status code?

The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.


&nbsp;

## Videos

### 1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

because you won't use the localhost when it's on another computer/server.

&nbsp;


### 2. What is middleware?

it's code that runs after a request was passed, but before it gets to the route.

&nbsp;


### 3. What does `app.use(express.json())` do?

this lets the server accept json as a body

&nbsp;


### 4. What does the `/:id` mean in a route?

a parameter the client passes to the sever, you can access it through `request.params.id ` which allows you to access whatever they pass after that `/`.

&nbsp;


### 5. What is the difference between `PUT` and `PATCH`?

put updates the whole object, patch only updates whatever gets passed from the client.

&nbsp;


### 6. How do you make a default value in a schema?

 by writing `default` inside a schema and then using the value/function you want as a value

&nbsp;


### 7. What does a `500` error status code mean?

the server had an internal error

&nbsp;


### 8. What is the difference between a status `200` and a status `201`?

200 means the request was successful, but 201 says the create request was successful.


&nbsp;


<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021