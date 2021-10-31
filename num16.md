# Spring Authorization

## Spring Boot and OAuth2


OAuth2 is an authorization framework superseding it first version OAuth, created back in 2006. It defines the authorization flows between clients and one or more HTTP services in order to gain access to protected resources.

##  Authorization

The main interface is `AccessDecisionManager`; which  delegate to a chain of `AccessDecisionVoter`. Each instance of the latter interface represents an association between an Authentication (a user identity, named principal), a resource and a collection of ConfigAttribute, the set of rules which describes how the resource’s owner allowed the access to the resource itself, maybe through the use of user roles.

The security for a web application is implemented using the basic elements described above in a chain of servlet filters, and the class `WebSecurityConfigurerAdapter` is exposed as a declarative way to express resource’s access rules.

Method security is first enabled by the presence of the `@EnableGlobalMethodSecurity(securedEnabled = true)` annotation, and then by the use of a set of specialized annotations to apply to each method to be protected such as `@Secured`, `@PreAuthorize`, and `@PostAuthorize`.

Spring Boot adds to all of this a collection of opinionated application configurations and third-party libraries in order to ease the development while maintaining an high quality standard.


<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021