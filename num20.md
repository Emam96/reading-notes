# Intents, Activities, and 


![backstack](https://developer.android.com/images/fundamentals/diagram_backstack.png)



## Tasks and the back stack

By using the manifest file, you can create a set of activities that are defined on the principles of first in last out, it. called the back stack. 

>Using Android Manifest <activity> tag with attribute android:launchMode.
Including Flags in the intent delivered to the startActivity().
This launchModes and its equivalent startActivity Flags allow us to define, how a new instance of an Activity is associated with the current Task and specifies the instruction for its launch in the given Task.

### Background and foreground tasks

Processing data in the background is an important part of creating an Android application that is both responsive for your users as well as a good citizen on the Android platform.
In general, any task that takes more than a few milliseconds should be delegated to a background thread.

### Multiple activity instances

Multi-instance activities are denoted by three parallel lines at the bottom-center of the activity/task symbol. It's purpose is to show that the activity occurs for a collection of objects or items.

## Save key-value data

If you have a relatively small collection of key-values that you'd like to save, you should use the `SharedPreferences` APIs. A SharedPreferences object points to a file containing key-value pairs and provides simple methods to read and write them. Each SharedPreferences file is managed by the framework and can be private or shared.

<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021