# Android Fundamentals

>Android applications are organized as a collection of components. There are four types of components, and applications can be composed of one or more of each type. A dynamic instance of a component corresponds to an application subset that can be executed independently of the others.
[source](https://www.sciencedirect.com/topics/computer-science/android-application)

## App components

There are four different types of app components:

* Activities
* Services
* Broadcast receivers
* Content providers

###  Activities

 An activity component implements interactions with the user. Activities are typically designed to manage a single type of user action, and multiple activities are used together to provide a complete user interaction.

 ### Services 

 Long-running or background components that do not directly interact with the user are expressed as service components.
 Services define and expose their own interfaces, which other components bind to in order to make use of the service.

 ### Broadcast receivers

 A broadcast receiver is an Android component which allows you to register for system or application events. All registered receivers for an event are notified by the Android runtime once this event happens.

 ### Content providers

 Components that provide access to an application’s data are content providers. Content providers let you centralize content in one place and have many different applications access it as needed. A content provider behaves very much like a database where you can query it, edit its content, as well as add or delete content using insert(), update(), delete(), and query() methods.

 ## App resources

 Resources are used for anything from defining colors, images, layouts, menus, and string values. The value of this is that nothing is hardcoded. Everything is defined in these resource files and then can be referenced within your application's code.


 ![android](https://cdn-images-1.medium.com/max/1200/1*3tLD4Ve66pbBpuawm9Fu9Q.png)

 <hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021