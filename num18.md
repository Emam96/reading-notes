# Spring and Sockets

## Using WebSocket to build an interactive web application

### Create a Resource Representation Class

Begin the process by thinking about service interactions.

The service will accept messages that contain a name in a STOMP message whose body is a JSON object.

To model the message that carries the name, you can create a plain old Java object with a name property and a corresponding `getName()` method.

Upon receiving the message and extracting the name, the service will process it by creating a greeting and publishing that greeting on a separate queue to which the client is subscribed. The greeting will also be a JSON object.

### Create a Message-handling Controller

In Spring’s approach to working with STOMP messaging, STOMP messages can be routed to @Controller classes. 

The @MessageMapping annotation ensures that, if a message is sent to the /hellodestination, the greeting() method is called.

The payload of the message is bound to a HelloMessage object, which is passed into greeting().

### Configure Spring for STOMP messaging

WebSocketConfig is annotated with @Configuration to indicate that it is a Spring configuration class. It is also annotated with @EnableWebSocketMessageBroker. As its name suggests, @EnableWebSocketMessageBroker enables WebSocket message handling, backed by a message broker.

The configureMessageBroker() method implements the default method in WebSocketMessageBrokerConfigurer to configure the message broker. It starts by calling enableSimpleBroker() to enable a simple memory-based message broker to carry the greeting messages back to the client on destinations prefixed with /topic. It also designates the /app prefix for messages that are bound for methods annotated with @MessageMapping. This prefix will be used to define all the message mappings. For example, /app/hello is the endpoint that the GreetingController.greeting() method is mapped to handle.

### Create a Browser Client

HTML file imports the SockJS and STOMP javascript libraries that will be used to communicate with our server through STOMP over websocket. We also import app.js, which contains the logic of our client application


<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021