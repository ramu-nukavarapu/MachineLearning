# 2 Python Basics

The programming languages used for machine learning

- python
- R

# Python

- python is a high level, interpreted programming language known for its simplicity and readability
- It is a dynamically typed language, you don’t need to declare the type of a variable
- It runs on various OS including windows, mac, Linux.

# Jupyter Notebook
All the concepts covered in this module are practically covered in the [Notebook.](/2%20Python_Basics/Python_Basics.ipynb)

# Basics in Python

## Variables

- variables are the **storage locations** that can store different types of values and can **accessed by variable names**
- The aim is to **reduce the complexity** to the programmer.
- In general, everything you’re stored in a computer stores in a specific memory address. It is hard to remember the memory address of any data then the variable comes.
- **syntax : variableName = value**

### Rules

- start with alphabets or _ (underscore) only
- case-sensitive
- do not use reserved keywords
- no spaces allowed

## Data Types

- int - non-decimal values
- float - decimal values
- string - sequence of characters
- Boolean - True or False

** type() function is used to see what type the variable is.

## Input & Output

## Output

- **print()** function is used to display the output in the computer
- It accepts **‘n’** number of arguments. But, all arguments are strings, constants, variables that are already declared and expressions as well
- **syntax : print(arguments)**

## Input

- **input()** function is used to get the input from the keyboard
- It accepts **one argument at once**
- input() function takes the input in the form of **strings only.** If you need other type of data, you have to **convert it from strings**
- **syntax : input()**
- If you want to convert from strings to other type
    
    **syntax : type(input())**
    

---

## Operators

- There are six operators in python:
    - Arithmetic
    - Assignment
    - Comparison
    - Logical
    - Identity
    - Membership

## Arithmetic Operators

- **+** → adds two numbers
- **-** → subtracts two numbers
- * → multiply two numbers
- **/** → divides and gives the quotient
- **%** → divides and gives the remainder
- ** → exponential(powerof) two numbers

## Assignment Operators

- **=** → assigns right value to left variable
- **+=, -=, *=, /=, %=** → these are perform the corresponding assignment operations with left variable and re-assign the left variable with the result

## Comparison Operators

- comparison operators returns boolean values
- **a == b** → returns true if both are equal else false
- **a ! = b** → returns true if both are not equal else false
- **a < b** → returns true if a is less than b else false
- **a < =  b** → returns true if a is less than or equal to b else false
- **a > b** → returns true if a is greater than b else false
- **a > =  b** → returns true if a is greater than or equal to b else false

## Logical Operators

- These are also return boolean values but based on the truth table values
- **and** → returns true, if both conditions are true, else false
- **or** → returns false, if both conditions are false, else true
- **not** → returns true, if condition false and vice versa

## Identity Operators

- compares the memory address of two variables
- **is** → returns true if both are pointing to the same memory address and vice versa
- **is not** → returns true if both are not pointing to the same memory address and vice versa

## Membership Operators

- checks in the data structure for the value is present or not
- **in** → returns true if the DS contains the value else false
- **not in** → returns true if the DS doesn’t contains the value else false

## Data Structures

- Data structures are used to store collection of elements that are heterogeneous
- Python provides 4 types of data structures each one has their own advantages. They are:
    - List
    - Tuple
    - Set
    - Dictionary

## List

- List is used to  **store collection of elements** of different type and allows duplicates.
- It is a **mutable data structure** which means you can perform all **CRUD** operations on the list
- List is **index-based** data structure( zero-index)
- **syntax : list = [] (or) list([elements])**

### Methods to perform operations on List

- **Accessing and modifying** the elements done using index
- **ListName.**append(value) → adds an element to the list at the end of the list
- **ListName.**insert(index,value) → adds an element to the list based on the index
- **ListName.**extend(list) → adds an another list to the current list at the end
- **ListName.**index(value) → if value present it returns index of first occurrence of the element  otherwise **valueError**
- **ListName.**copy() → copies the list into another list
- **ListName.**reverse() → reverse the list
- **ListName.**sort() → sorts the list if reverse parameter equals to  true then it is sorted in descending order
- **ListName.**remove(value) → if value present it removes the element that first occurs otherwise **valueError**
- **ListName.**pop([index]) → removes the last element from the list. if we pass an index, it removes the element in that index if the index is present otherwise **indexError**
- **ListName.**clear() → clears the entire list

## Tuples

- Tuple is used to  **store collection of elements** of different type and allows duplicates.
- It is a **immutable data structure**
- Tuple is **index-based** data structure( zero-index)
- **syntax : tup = () (or) tuple([elements])**

### Methods to perform operations on Tuple

- **Accessing** the elements done by index
- **TupleName.**count(value) → It returns the count of the value in the tuple
- **TupleName.**index(value) → if value present it returns index of first occurrence of the element  otherwise **valueError**

## Set

- Set is used to  **store collection of elements** of different type and doesn’t allow duplicates.
- It is a **mutable data structure**
- Set is an unordered data structure( no-index)
- **syntax : set = set([elements])**

### Methods to perform operations on Set

- **SetName.**add(value) → adds an element to the set
- **SetName.**remove(value) → if value present it removes the element that first occurs otherwise **keyError**
- **SetName.**discard(value) → removes if the value is present else do nothing
- **SetName.**pop() → returns and removes an arbitary value from set. raise keyError if set is empty
- **SetName.**clear() → it clears the entire set

## Dictionary

- Dictionary is used to store **key-value pairs**. where the key is unique and immutable, and the value can be of any data type, including other dictionaries.
- It is an **unordered** data structure
- **syntax : dict = {} (or) dict([ [key, value] ])**

### Methods to perform operations on Dictionary

- **DictName.**get(key,[default]) → returns the value in the key if key is present else returns the default value
- **DictName.**items() → returns a view object that displays a list of dictionary's key-value tuple pairs.
- **DictName.**keys() → returns a view object that displays a list of all the keys in the dictionary.
- **DictName.**values() → returns a view object that displays a list of all the values in the dictionary.
- **DictName.**update( [key-value] ) → updates the dictionary with the key-value pairs from [key-value pair], overwriting existing keys.
- **DictName.**pop(key,[default]) → Removes the specified key and returns the corresponding value. If the key is not found, default is returned if provided, otherwise a keyError is raised.
- **DictName.**popitem() → removes and returns a (key, value) pair from the dictionary. Pairs are returned in LIFO (last-in, first-out) order.
- **DictName.**copy() → returns a copy of the dictionary
- **DictName.**clear() → clears  the entire dictonary

---

## Conditional Statements

- conditional statements are used to perform a specific operations based on the condition
    - simple if
    - if else
    - if elif ladder
    - nested if

## Simple if

- if the condition is true, the block will execute else it skips that part and start executing next statements
- syntax :
    
    if condition :
    
    //if body
    

## if - else

- if the condition is true, the if-block will execute otherwise else-block will execute
- syntax :
    
    if condition :
    
    //if body
    
    else:
    
    //else body
    

## if - elif - ladder

- if the condition is true, the if-block will execute otherwise it checks for next elif condition and executes if it is true. if all conditions are failed then else-block will execute
- syntax :
    
    if condition :
    
    //if body
    
    elif condition:
    
    //else body
    
    else:
    
    //else body
    

## Nested if

- if the condition is true, then it checks for the inner if condition the if-block will execute if  it is true otherwise else-block will execute
- syntax :
    
    if condition :
    
    if condition:
    
    //inner if block
    
    else:
    
    //else body
    

## Loops

- Python provides two loops:
    - for loop
    - while loop

## for loop

- used to iterate over the sequence or data structures
- syntax:
    
    for i in sequence/DS :
    
    //for body
    

## while loop

- used to iterate over the sequence or data structures
- syntax:
    
    i = 0 //initialization
    
    while condition :
    
    //while body
    
    updation
    

## Functions

- Function consists of set of instructions that are executed only when it is called
- syntax :
    
    def functionName(parameter(s)):
    
    //function body
    
    return value
    

### Function Components

- **Function Name**: A unique identifier for the function.
- **Parameters (Arguments)**: Variables that are passed into the function.
- **Docstring**: Optional, but recommended. Describes the function’s purpose.
- **Body**: The block of code that performs the function's task.
- **Return Statement**: Returns a value from the function. This is optional; if omitted, the function returns None.

### Parameters and Arguments

- **Positional Arguments**: Arguments that are passed to a function in a specific order.
- **Keyword Arguments**: Arguments passed using the name of the parameter.
- **Default Arguments**: Parameters that assume a default value if a value is not provided.
- **Variable-length Arguments**: Functions can accept an arbitrary number of arguments using *args and **kwargs.
    - *args: Allows a function to accept any number of positional arguments, which are then accessible as a tuple.
    - **kwargs: Allows a function to accept any number of keyword arguments, which are then accessible as a dictionary.