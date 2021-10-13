# Linked Lists 

## Big O: Analysis of Algorithm Efficiency 

### Big-O Definition

An algorithm’s Big-O notation is determined by how it responds to different sizes of a given dataset. For instance how it performs when we pass to it 1 element vs 100 elements.

### Time Complexity

Instead of focusing on units of time, Big-O puts the number of steps in the spotlight. because machines vary in performance The hardware factor is taken out of the equation. Therefore we are not talking about run time, but about time complexity.

### O(1) — Constant

O(1) means that the algorithm takes the same number of steps to execute regardless of how much data is passed in.

### O(N) — Linear

An algorithm that is O(N) will take as many steps as there are elements of data. So when an array increases in size by one element, an O(N) algorithm will increase by one step.

### O(N²) — Quadratic

O(N²) represents the complexity of an algorithm, whose performance is proportional to the square of the size of the input elements. It is generally quite slow: 
>If the input array has 1 element it will do 1 operation, if it has 10 elements it will do 100 operations, and so on.


### O(logN) — Logarithmic

Simply put, O(logN) describes an algorithm that its number of operations increases by one each time the data is doubled.


### O(2ᴺ) — Exponential

Exponential growth means that the algorithm takes twice as long for every new element added.

<hr>

## Linked Lists 

A linked list is a linear data structure where each element is a separate object.
Linked list elements are not stored at contiguous location; the elements are linked using pointers.

Each node of a list is made up of two items - the data and a reference to the next node. The last node has a reference to null. The entry point into a linked list is called the head of the list. It should be noted that head is not a separate node, but the reference to the first node. If the list is empty then the head is a null reference.

![linked](https://s3-us-west-2.amazonaws.com/ib-assessment-tests/problem_images/singly-ll.png)

Here is how we can create linked lists in Java:

`LinkedList<Type> linkedList = new LinkedList<>();`

Here, Type indicates the `type` of a linked list. For example,

`// create Integer type linked list`
`LinkedList<Integer> linkedList = new LinkedList<>();`

`// create String type linked list`
`LinkedList<String> linkedList = new LinkedList<>();`
  `// create linkedlist`
    `LinkedList<String> animals = new LinkedList<>();`

We can use the add() method to add an element (node) at the end of the LinkedList. For example,

 `// add() method without the index parameter`<br>
    `animals.add("Dog");`<br>
    `animals.add("Cat");`<br>
    `animals.add("Cow");`



<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021