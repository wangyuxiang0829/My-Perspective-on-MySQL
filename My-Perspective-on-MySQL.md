# My-Perspective-on-MySQL



## Overview



> Be a specialist in using Structured Query Language, or SQL, to  retrieve and analyze big data from industrial-sized relational databases



## Induction

### How Do You Pronounce SQL



**SQL**

> Structured query language: a computer programming language used for database management



```
Ess-Cue-Ell
```

or

```
See-Quill
```



is both ok



### Why Should Data Analysts learn SQL?



> You write SQL queries to retrieve the data you have to analyze



### Relational Databases



> Relational databases are the gold standard for data bases that store highly organized and structured business data. Almost every single company in the world has at least one relational database



### Why MySQL



> MySQL is a particular brand or platform of relational database 



1. it's reliable
2. it's mature
3. it's open source
4. it's well understood
5. There's a lot of industry and community around MySQL
6.  There are a lot of tools for it



## Problems Databases Solve

### Problems with Having a Lot of Data Used by a Lot of People



> 1. Why do we need databases in all this complicated database query language?
> 2. Why can't businesses keep things simple and just store things in spreadsheets? It seems like that would make things a lot easier on everyone



* First of all, the spreadsheets are pretty big, so they take a while to open and search
* Second, sometimes multiple people end up interacting with a spreadsheet at the same time, and they end up writing over each other's entries
* Third, there's starting to be a lot of inconsistencies in the data which are hard to catch if you don't have multiple spreadsheets open at once
* And only a few people have computers that are powerful enough to open multiple spreadsheets of that size at once anyway



**Good data storage allows**

1. Easy retrieval
2. Easy updating
3. Accessibility for multiple people at same time
4. Data consistency
5. Space efficiency
6. Speed
7. Security



### How Relational Databases Help Solve Those Problems



#### How Does Relational Databases works

* The fundamental concept behind relational databases is that they break up data sets into individual pieces or subsets of data. Each subset of the data will have a theme that logically binds the data records and that subset together
* When you ask to retrieve information, the database only interacts with the subsets of data it needs to provide the information you asked for rather than interacting with the entire dataset at the same time



#### What Does Programmers Do

> Computers don't yet run on magic although admittedly it often seems like they do



So in order to have a computer program do something like link up tables for you, you have to have a way of telling the computer how to do that.

You have to be able to program in the appropriate rules and operations that will lead to the outcomes you want.

It turns out that *thinking of data as groups of related items* that can interact allows programmers to take advantage of the mathematical theory called set theory and a kind of algebra called relational algebra to write an elegant and complete programming language for each reading information.



#### Requirements

The database will be configured to abide by as many of the requirements of set theory as possible.

1. First of all, single tables should represent the smallest logical part of a data set
2. Next, each column in a table must represent a unique category of information
3. Each row in a table must represent unique instance of that information as well
4. Order of columns or row in a table can't matter



#### Features

As long as we can figure out how to put the data we care about into collections of tables, relational databases provide a very powerful way to **store** and **retrieve** our data in an extremely **safe** and **reliable** fashion. They pretty much solve all the problems spreadsheets don't



