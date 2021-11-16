# RecyclerView

## What is RecyclerView?

It is a container for displaying large datasets which can be scrolled efficiently by maintaining limited number of views. 

## Views

The Android platform uses the View and ViewGroup classes to draw items on the screen. These classes are abstract and are extended to different implementations to suite a use-case.
It’s possible to create our own custom views to be able to achieve more flexibility when developing user interfaces.

## ViewGroups

ViewGroup gives us the ability put multiple views into one view, which we can reference as a whole. the View that’s created at the top level that we add other simple views(we can also add viewGroups) to is called the “parent,” and the views that are added inside are “children”. The ViewGroup also enables us to define how the children are organized inside the view.

## LinearLayout

LinearLayout allows us to add View items in it. LinearLayout is an orientation attribute that dictates how it will be laid out on the screen.

## RecyclerView.Adapter

An adapter is a device that transforms attributes of system or device to those of an otherwise incompatible device or system. 

## RecyclerView.LayoutManager

When dealing with a ViewGroup we would have Views placed inside it. It is LayoutManager would have the task of describing how the Views are laid out inside. `GridLayout`, it’s use case is when we would want to place Views in a rectangular Grid structure.

## RecyclerView.ViewHolder

The ViewHolder is an abstract class that we also extend from RecyclerView. The ViewHolder provides us with common methods to help us reference a View we have placed on the RecyclerView even after the Recycling machinery in the RecyclerView has changed various references we don’t know about.


![view](https://miro.medium.com/max/700/1*8go_yZFE5Gf9au_P48_qKw.png)



<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021