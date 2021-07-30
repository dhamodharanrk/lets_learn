---
sort: 2
---

# Data Types & Data objects/structures

Data types are the classification or categorization of data items. It represents the kind of value that tells what operations can be performed on a particular data. 

- Variables can store data of different types, and different types can do different things

Following are the standard or built-in data type of Python,

## Numeric Types

There are three numeric types in Python,
- int
- float
- complex

### Integers

There is no maximum limit on the value of an integer. The integer can be of any length without any limitation which can go up to the maximum available memory of the system. 

### Floating Point Number

The difference between floating points and integers is decimal points. Floating point number can be represented as “1.0”, and integer can be represented as “1”. It is accurate up to 15 decimal places.

### Complex Number

“x + yj” is the written form of the complex number. Here y is the imaginary part and x is the real part.

## Text Type

A String is a sequence of Unicode characters. In Python, String is called str. Strings are represented by using Double quotes or single quotes

```python
s = “Python String”
```
 
## Sequence Types
 - range
 - tuple
 - list

## Mapping Type

Dictionary is a type of python data type in which collections are unordered, and values are in pairs called key-value pairs.

The value can only be retrieved if one knows the key to retrieve it. 

```python
d = {3:’key’,4:’value’}
```

## Set Types
- frozenset
- set

### Python set

The Collection of Unique items that are not in order is called Set. Braces {} are used to defined set and a comma is used to separate values. One will find that the items are unordered in a set data type.

Duplicates are eliminated in a set and set only keeps unique values. Operations like intersection and union can be performed on two sets. 

Python set will look like this:

```python
a = {4,5,5,6,6,6}
print(a)
#{4, 5, 6}
```

## Boolean Type

There can be only two types of value in the Boolean data type of Python, and that is True or False. 

For example,

```python
a = True
b = False
```

