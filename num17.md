# Web App Security

## Many-to-many relationships

>A many-to-many relationship occurs when multiple records in a table are associated with multiple records in another table.

Relational database systems usually don't allow you to implement a direct many-to-many relationship between two tables. This is why we assign a unique value to each invoice.

Also, To avoid this problem, you can break the many-to-many relationship into two one-to-many relationships by using a third table, called a join table. Each record in a join table includes a match field that contains the value of the primary keys of the two tables it joins.

![manytomany](https://condor.depaul.edu/gandrus/240IT/accesspages/images/many_to_many_er.gif)

## Mickens on Security

Mickens’ argument that good security practices will defend against attackers who are merely curious or with limited resources; you can never defend against the well-funded intelligence and counter-intelligence agencies of rich countries, against whom the best defense was simply not to be a target of national importance.

There are, however, three problems with this:

1. Even if we can’t keep out Mossad 100% of the time, that doesn’t mean we should make things easy for them or fail to understand the techniques they may be using to accomplish it. 
2. As cybercrime becomes more profitable and cyberwarfare becomes more economically appealing, the line between the capabilities of Mossad and not-Mossad is going to get blurry.
3. The line between political and non-political targets is also will vanish. To some extent this is already happening: Russian, Chinese and US intelligence agencies obtain secrets that end up not in their governments’ hands but in those of private companies. 


<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021