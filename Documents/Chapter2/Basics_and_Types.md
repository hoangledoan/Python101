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

### 3. Variables and Assignment
You need to define your variables to programm.
Python variable names have some rules:
-  They can contain only these characters:
    - Lowercase letters (a - z) 
    - Uppercase letters (A -Z)
    - Digits (0 - 9)
    -  Underscore (_)
-  Case-sensitive: python, Python, PYTHON are different names.
-  They must begin with a letter or an underscore, not a digit
```
count = True
total_score = 30
user1_input = 'hi'
```

You can assign a value to multiple variables:
```
mot = one = eins = 1
```

You can copy a value from an existing variable:
```
x = 5
y = x
>>> y = 5
```

### 4. Expression
An expression is a combination of values, variables, operators, and function calls that results in a single value. It can be as simple as a single constant or as complex as a combination of multiple variables and operations.

## II. Types
In Python, just like in the real world where things come in different types, such as cars, animals, and fruits, data in programming also has types. These types help Python understand and manage the information you're working with. 

Some types (List, Set, Dictionary) are mutable (ability to change flexibly change its type without needing to manually convert them). 
### 1. Boolean
In short, boolean only has 2 values: True or False. Booleans are essential for making decisions in your code, controlling the flow of your programs, and creating conditions for different actions.
```
is_true = True
is_false = False
```
[More examples](Boolean.md)

###


