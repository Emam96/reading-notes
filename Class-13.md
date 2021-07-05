# Local Storage

>The localStorage and sessionStorage properties allow to save key/value pairs in a web browser.

The localStorage object saves the data without an expiration date. The data will not be deleted when the browser is closed, and will be available anytime you screen the page again.

localStorage is similar to sessionStorage, except that while localStorage data has no expiration time, sessionStorage data gets cleared when the page session ends.

&nbsp;

In all current browsers, localStorage seems to return a different object for each file: URL. In other words, each file: URL seems to have its own unique local-storage area. But there are no guarantees about that behavior, so you shouldn’t rely on it because, as mentioned above, the requirements for file: URLs remains undefined. So it’s possible that browsers may change their file: URL handling for localStorage at any time. In fact some browsers have changed their handling for it over time.

<hr>

* Syntax<br>

      window.localStorage

* Syntax for SAVING data to localStorage:<br>

      localStorage.setItem("key", "value");

* Syntax for READING data from localStorage:

          var lastname = localStorage.getItem("key");

* Syntax for REMOVING data from localStorage:<br>

          localStorage.removeItem("key");



&nbsp;

![ME](https://warcontent.com/wp-content/uploads/2020/06/angular-localstorage-1-1280x720.png)

<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021
