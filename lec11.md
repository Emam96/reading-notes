# Authentication

## What is OAuth?


![oth](https://1tskcg39n5iu1jl9xp2ze2ma-wpengine.netdna-ssl.com/wp-content/uploads/2020/02/oauth-2-flow-diagram.png)

### 1. What is OAuth?

OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential


&nbsp;


### 2. Give an example of what using OAuth would look like.

when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon

&nbsp;


### 3. How does OAuth work? What are the steps that it takes to authenticate the user?

When you try to login to a site using OAuth, this site connects to another website(that uses OAuth) you already logged in to, and then a token is generated between the two so you can log in,.

&nbsp;


### 4.  What is OpenID?

It's an alternative to OAuth, but it tries to actually identify users and make sure the access is secure, while OAuth is more about authorizing more than authenticating.

&nbsp;

<hr>

## Authorization and Authentication flows

### 1. What is the difference between authorization and authentication?

Authorization is only giving access to simple, or general info about your account, and not really giving away any private info.
While Authentication tries to actually authenticate who the user is, and make sure who ever is logging in is actually the owner of the account.

&nbsp;


### 2. What is Authorization Code Flow?

It exchanges an Authorization Code for a token so the user can login to website using credentials from another.

&nbsp;


### 3.  What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

When public clients (e.g., native and single-page applications) request Access Tokens, some additional security concerns are posed that are not mitigated by the Authorization Code Flow alone.
So,OAuth 2.0 provides a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange (PKCE)

&nbsp;


### 4.  What is Implicit Flow with Form Post?

Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls. With this method, you don’t need to obtain, maintain, use, and protect a secret in your application.

&nbsp;


### 5. What is Client Credentials Flow?

M2M (machine-to-machine) apps use the Client Credentials Flow in which they pass along their Client ID and Client Secret to authenticate themselves and get a token.

&nbsp;


### 6. What is Device Authorization Flow?

With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device. This avoids a poor user experience for devices that do not have an easy way to enter text.

&nbsp;


### 7. What is Resource Owner Password Flow?

highly-trusted applications can use the Resource Owner Password Flow, which requests that users provide credentials (username and password), typically using an interactive form. The Resource Owner Password Flow should only be used when redirect-based flows (like the Authorization Code Flow) cannot be used.



&nbsp;




<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021