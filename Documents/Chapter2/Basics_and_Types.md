# Basics

## I. Basics
#### 1. Indentation
Python is unique among programming languages because it uses whitespace and indentation to determine block structure.
###### C++
```
for (int i = 0; i < 5; i ++)
{                                    |
cout << "Hi!";                       |  In the scope -> do the command within the '{}'
}                                    |      
```
###### Python
```
i = 0;
for (i = 0, i < 5, i++):
  print("Hi!")
^
Indentation, 1 tab or 3 spaces, up to you ^^ I prefer tab.
```
We will get in deeper into that when you learn about function programming.

#### 2. Comments
To structure and explain your code better, maybe for urself in the future or for you teamm, you should use comments
```
# Assign 10 to x
x  = 10
```
Simply add '#' where you want to comment, usually before the code you want to explain.

## II. Types
In Python, just like in the real world where things come in different types, such as cars, animals, and fruits, data in programming also has types. These types help Python understand and manage the information you're working with. Whether it's numbers, words, or other kinds of data, knowing about types is fundamental to writing effective and accurate Python code. 

[Boolean][]