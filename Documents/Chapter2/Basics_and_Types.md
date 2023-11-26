# Basics

## I. Basics
### 1. Indentation
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

### 2. Comments
To structure and explain your code better, maybe for urself in the future or for you teamm, you should use comments
```
# Assign 10 to x
x  = 10
```
Simply add '#' where you want to comment, usually before the code you want to explain.

### 3. Variables
You need to define your variables to programm.
Python variable names have some rules:
-  They can contain only these characters:
    - Lowercase letters (a - z) 
    - Uppercase letters (A -Z)
    - Digits (0 - 9)
    -  Underscore (_)
-  case-sensitive: python, Python, PYTHON are different names.
-  they must begin with a letter or an underscore, not a digit
```
count = True
total_score = 30
user1_input = 'hi'
```
## II. Types
In Python, just like in the real world where things come in different types, such as cars, animals, and fruits, data in programming also has types. These types help Python understand and manage the information you're working with. 

[Boolean][Boolean.md]
