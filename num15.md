# Spring Authentication

Spring Security is implemented to control access. Each request to a protected resource goes through its methods. Each request can either ignore the request, or do something and then pass it to the next method, or generate a response and terminate the request.

* The Security Context object contains information about the currently authenticated user. It is accessible to all the Java code handling the request via the thread-local object SecurityContextHolder.

* The Login Processing Filter is responsible for handling login requests. Normally, this filter is triggered based on URL patterns. If a request URL matches one of the patterns configured for the filter, it will try to authenticate the user based on information contained in the request; otherwise, it will simply pass the request to the next filter in the chain.

* The Filter Security Interceptor is the last line of defense in the security filter chain. It is responsible for making sure that no unauthenticated request reaches protected resources. If this filter determines that a request to a protected resource is not authenticated, it delegates to the Login Entry Point bean responsible for initiating the login dialog with the user.


* Spring Security is the leading choice for securing Spring applications. It offers a significant number of alternatives that apply to different styles and architectures.

* You should apply security in layers for your system, and for each layer, you should use different practices.
Spring Security is a project related to application-level security.

* Security is a cross-cutting concern, and you should consider it from the beginning of a software project.
Usually, the cost of an attack is higher than the investment in avoiding vulnerabilities.

* The Open Web Application Security Project (OWASP) is an excellent place to start, then always refer to that when it comes to vulnerabilities and security concerns.

* Sometimes the smallest mistakes can cause significant harm. For example, exposing sensitive data through logs or error messages is a common way to introduce vulnerabilities in your application.


![chain](https://abyte.stream/assets/2019-05-31-Spring%20Security%20Architecture-2.png)

<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021