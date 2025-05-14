# palak_cubexo

Operators
    Python divides the operators in the following groups:

        Arithmetic operators
                +	Addition	x + y	
                -	Subtraction	x - y	
                *	Multiplication	x * y	
                /	Division	x / y	
                %	Modulus	x % y	
                **	Exponentiation	x ** y	
                //	Floor division	x // y
        Assignment operators
                =	x = 5	x = 5	
                +=	x += 3	x = x + 3	
                -=	x -= 3	x = x - 3	
                *=	x *= 3	x = x * 3	
                /=	x /= 3	x = x / 3	
                %=	x %= 3	x = x % 3	
                //=	x //= 3	x = x // 3	
                **=	x **= 3	x = x ** 3	
                &=	x &= 3	x = x & 3	
                |=	x |= 3	x = x | 3	
                ^=	x ^= 3	x = x ^ 3	
                >>=	x >>= 3	x = x >> 3	
                <<=	x <<= 3	x = x << 3	
                :=	print(x := 3)	x = 3
                                    print(x)
        Comparison operators

                ==	Equal	x == y	
                !=	Not equal	x != y	
                >	Greater than	x > y	
                <	Less than	x < y	
                >=	Greater than or equal to	x >= y	
                <=	Less than or equal to	x <= y
        Logical operators
                and 	Returns True if both statements are true	x < 5 and  x < 10	
                or	Returns True if one of the statements is true	x < 5 or x < 4	
                not	Reverse the result, returns False if the result is true	not(x < 5 and x < 10)	

        Identity operators
                is 	Returns True if both variables are the same object	x is y	
                is not	Returns True if both variables are not the same object	x is not y
        Membership operators
                in 	Returns True if a sequence with specified value ispresent in the object x in y	
                not in	Returns True if a sequence with the specified value is not present in the object x not in y

        Bitwise operators
                & 	AND	Sets each bit to 1 if both bits are 1	x & y	
                |	OR	Sets each bit to 1 if one of two bits is 1	x | y	
                ^	XOR	Sets each bit to 1 if only one of two bits is 1	x ^ y	
                ~	NOT	Inverts all the bits	~x	
                <<	Zero fill left shift	Shift left by pushing zeros in from the right and let the leftmost bits fall off	x << 2	
                >>	Signed right shift	Shift right by pushing copies of the leftmost bit in from the left, and let the rightmost bits fall off	x >> 2

OOPs Concepts in Python
    Class in Python
    Objects in Python
    Polymorphism in Python
    Encapsulation in Python
    Inheritance in Python
    Data Abstraction in Python


Python Inheritance
Inheritance allows a class (child class) to acquire properties and methods of another class (parent class). It supports hierarchical classification and promotes code reuse.

Types of Inheritance:
        Single Inheritance: A child class inherits from a single parent class.
        Multiple Inheritance: A child class inherits from more than one parent class.
        Multilevel Inheritance: A child class inherits from a parent class, which in turn inherits from another class.
        Hierarchical Inheritance: Multiple child classes inherit from a single parent class.
        Hybrid Inheritance: A combination of two or more types of inheritance.


Python Polymorphism
Polymorphism allows methods to have the same name but behave differently based on the object’s context. It can be achieved through method overriding or overloading.



    1. Run-Time Polymorphism:

        Demonstrated using method overriding in the Dog class and its subclasses (Labrador and Beagle).
        The correct sound method is invoked at runtime based on the actual type of the object in the list.
    2. Compile-Time Polymorphism:

        Python does not natively support method overloading. Instead, we use a single method (add) with default arguments to handle varying numbers of parameters.
        Different behaviors (adding two or three numbers) are achieved based on how the method is called.



Decision Making
    Python programming language provides following types of decision making statements. Click the following links to check their detail.

    Statement & Description
    1	if statements
    An if statement consists of a boolean expression followed by one or more statements.

    2	if...else statements
    An if statement can be followed by an optional else statement, which executes when the boolean expression is FALSE.

    3	nested if statements
    You can use one if or else if statement inside another if or else if statement(s).

Python - Loops

    Python programming language provides following types of loops to handle looping requirements −

    Loop Type & Description
    1	while loop  
    Repeats a statement or group of statements while a given condition is TRUE. It tests the condition before executing the loop body.

    2	for loop
    Executes a sequence of statements multiple times and abbreviates the code that manages the loop variable.

    3	nested loops
    You can use one or more loop inside any another while, for or do..while loop.

Python Loop Control Statements
Loop control statements change execution from its normal sequence. When execution leaves a scope, all automatic objects that were created in that scope are destroyed.

Python supports the following control statements. Click the following links to check their detail.

Let us go through the loop control statements briefly

Control Statement & Description
1	break statement
Terminates the loop statement and transfers execution to the statement immediately following the loop.

2	continue statement
Causes the loop to skip the remainder of its body and immediately retest its condition prior to reiterating.

3	pass statement
The pass statement in Python is used when a statement is required syntactically but you do not want any command or code to execute.



Strings
Strings in python are surrounded by either single quotation marks, or double quotation marks.
'hello' is the same as "hello".    

    Slicing
    You can return a range of characters by using the slice syntax.
    b = "Hello, World!"
    print(b[2:5])

    modify
        .upper
        .lower
        .split(",")
        .replace(from,to)
        .strip() remove whitespace from start and end
        + -"concat"
    
    F-Strings

        To specify a string as an f-string, simply put an f in front of the string literal, and add curly brackets {} as placeholders for variables and other operations.

        age = 36
        txt = f"My name is John, I am {age}"
        print(txt)

    Escape Character
        To insert characters that are illegal in a string, use an escape character.

        An escape character is a backslash \ followed by the character you want to insert.
        \'	Single Quote	
        \\	Backslash	
        \n	New Line	
        \r	Carriage Return	
        \t	Tab	
        \b	Backspace	
        \f	Form Feed	
        \ooo	Octal value	
        \xhh	Hex value

Lists
    List is one of the built-in data types in Python. A Python list is a sequence of comma separated items, enclosed in square brackets [ ]. The items in a Python list need not be of the same data type.
    Methods with Description
    1	
    list.append(obj)

    Appends object obj to list.

    2	
    list.clear()

    Clears the contents of list.

    3	
    list.copy()

    Returns a copy of the list object.

    4	
    list.count(obj)

    Returns count of how many times obj occurs in list

    5	
    list.extend(seq)

    Appends the contents of seq to list

    6	
    list.index(obj)

    Returns the lowest index in list that obj appears

    7	
    list.insert(index, obj)

    Inserts object obj into list at offset index

    8	
    list.pop(obj=list[-1])

    Removes and returns last object or obj from list

    9	
    list.remove(obj)

    Removes object obj from list

    10	
    list.reverse()

    Reverses objects of list in place

    11	
    list.sort([func])

    Sorts objects of list, use compare func if given

    Function with Description

    1	cmp(list1, list2)
    Compares elements of both lists.

    2	len(list)
    Gives the total length of the list.

    3	max(list)
    Returns item from the list with max value.

    4	min(list)
    Returns item from the list with min value.

    5	list(seq)
    Converts a tuple into list.



Tupels
================
    Tuple is one of the built-in data types in Python. A Python tuple is a sequence of comma separated items, enclosed in parentheses (). The items in a Python tuple need not be of same data type.
    tup1 = ("Rohan", "Physics", 21, 69.75)
    tup2 = (1, 2, 3, 4, 5)




Sets
================
    A set refers to a collection of distinct objects. It is used to group objects together and to study their properties and relationships. The objects in a set are called elements or members of the set.

    my_set = {1, 2, 3, 4, 5}
    my_set = set([1, 2, 3, 4, 5])

    In Python, the update() method of set class is used to add multiple elements to the set. It modifies the set by adding elements from an iterable (such as another set, list, tuple, or string) to the current set. The elements in the iterable are inserted into the set if they are not already present.

    The remove() method in Python is used to remove the first occurrence of a specified item from a set.


dictionary
=============

A dictionary is a collection of key-value pairs. It is an unordered collection of items that can


Python Dictionary Methods
Python includes following dictionary methods −

Sr.No.	Methods with Description
1	dict.clear()
Removes all elements of dictionary dict

2	dict.copy()
Returns a shallow copy of dictionary dict

3	dict.fromkeys()
Create a new dictionary with keys from seq and values set to value.

4	dict.get(key, default=None)
For key key, returns value or default if key not in dictionary

5	dict.has_key(key)
Returns true if key in dictionary dict, false otherwise

6	dict.items()
Returns a list of dict's (key, value) tuple pairs

7	dict.keys()
Returns list of dictionary dict's keys

8	dict.setdefault(key, default=None)
Similar to get(), but will set dict[key]=default if key is not already in dict

9	dict.update(dict2)
Adds dictionary dict2's key-values pairs to dict

10	dict.values()
Returns list of dictionary dict's values


Function with Description
1	cmp(dict1, dict2)
Compares elements of both dict.

2	len(dict)
Gives the total length of the dictionary. This would be equal to the number of items in the dictionary.

3	str(dict)
Produces a printable string representation of a dictionary

4	type(variable)
Returns the type of the passed variable. If passed variable is dictionary, then it would return a dictionary type.


DAY 2 --13 MAY
EXCEPTION HANDLING


Exception Handling in Python
Exception handling in Python refers to managing runtime errors that may occur during the execution of a program. In Python, exceptions are raised when errors or unexpected situations arise during program execution.

Assertions in Python
An assertion is a sanity-check that you can turn on or turn off when you are done with your testing of the program.

The try: block contains statements which are susceptible for exception

If exception occurs, the program jumps to the except: block.

If no exception in the try: block, the except: block is skipped.

try:
    fh = open("test filw", "r")
    fh.write("this is my file for exception handling")
except IOError:
    print("cant find file ")
else:
    print("wriiten content succesfully")
    fh.close()
    
import sys

try:
   fh = open("testfile", "w")
   try:
      fh.write("This is my test file for exception handling!!")
   finally:
      print ("Going to close the file")
    #   fh.close()
except IOError:
   print ("Error: can\'t find file or read data")
   fh.close()
   sys.exit()

FUNCTION , LAMBA FUNCTION  

What is the lambda function in Python?
Lambda Function, often known as an 'Anonymous Function,' is the same as a normal Python function except that it can be defined without a name. The def keyword is used to define normal functions, while the lambda keyword is used to define anonymous functions. They are, however, limited to a single line of expression. They, like regular functions, can accept several parameters.


inputString = "tutorialPoint"

ints1 = lambda inputString : inputString.upper()[::-2]
print(ints1(inputString))

def squ(x):
    return x*x

lambda_squ = lambda x: x*x

print(squ(3))
print(lambda_squ(6))


r = 'palakaknodiya'
intt = lambda r: r.lower()[::-1]
print(intt(r))

sum_max = lambda x , y: x if (x > y) else y
print(sum_max(45,34))


ARRAY

An ARray is a conta ariner which can hold a fix number of items and these items should be of the same type. Each item stored in an array is called an element and they can be of any type including integers, floats, strings, etc.

import array as arr

cars = arr.array('u','LAMBERGINI')

print(type(cars),cars)

##########################

Basic Operations on Python Arrays
Following are the basic operations supported by an array −

Traverse − Print all the array elements one by one.

Insertion − Adds an element at the given index.

Deletion − Deletes an element at the given index.

Search − Searches an element using the given index or by the value.

Update − Updates an element at the given index.


from array import *

arr1 = array('i',[10,20,30,40,50,60,70,80,90])
print(arr1[0])



from array import *

arr1 = array('i', [10,20,30,40,50,60,70,80,90])
print(arr1[0])
print(arr1[8])
arr1.insert(10,100) #insertion
arr1.remove(40)#deletetion
print(arr1.index(20)) #serach
arr1[2] = 2626
for arr2 in arr1:
    print(arr2)


from array import *

a = array('i',[10,120,30,90,50,60])
for i in range(0,len(a)):
    for j in range(i+1,len(a)):
        if(a[i] > a[j]):
            temp = a[i]
            a[i] = a[j]
            a[j] = temp
print(a)



##########using sort
b = a.tolist()
print(b)


########### join using exxtend

a = array('u','palak')
b = array('u','kanodiya')
a.extend(b)
print(a)


Methods with Description
1	
append(x)

Appends a new item with value x to the end of the array.

2	
extend(iterable)

Appends items from iterable to the end of the array.

3	
insert(i, x)

Inserts a new item with value x before position i.

4	
pop([i])

Removes and returns the item with index i. If i is not specified, removes and returns the last item.

5	
remove(x)

Removes the first occurrence of x from the array.

Methods with Description
1	
reverse()

Reverses the order of the items in the array.

2	
byteswap()

"Byteswaps" all items of the array, useful for reading data from a file written on a machine with a different byte order.




CONTRUCTOR

Python constructor is an instance method in a class, that is automatically called whenever a new object of the class is created.

Types of Constructor in Python
Python has two types of constructor −

Default Constructor
Parameterized Constructor


Default Constructor in Python
The Python constructor which does not accept any parameter other than self is called as default constructor.

Parameterized Constructor
If a constructor is defined with multiple parameters along with self is called as parameterized constructor.



#####default

class student:
    def _init_(self):
        self.name = "palak"
        self.age = 22

p1 = student()
print("my self: {}".format(p1.name))
print("my age: {}".format(p1.age))



#####parametrized


class library:
    def _init_(self,dept,serialNo):
        self.dept = dept
        self.serialNo = serialNo

e1 = library("computer",3455676)
e2 = library("maths",323547)

print("current dept: {}".format(e1.dept))
print("current dept: {}".format(e2.dept))
print("current serialNo: {}".format(e1.serialNo))
print("current serialNo: {}".format(e2.serialNo))

MODULE


What is Python Module
A Python module is a file containing Python definitions and statements. A module can define functions, classes, and variables. A module can also include runnable code.

import module
from math import sqrt, factorial
from module_name import *
from math import *
import sys
import math
import random
import datetime
from datetime import date
import time


FILE HANDLING

File Handling in Python
File handling in Python involves interacting with files on your computer to read data from them or write data to them. Python provides several built-in functions and methods for creating, opening, reading, writing, and closing files.

Modes & Description
1	
r

Opens a file for reading only. The file pointer is placed at the beginning of the file. This is the default mode.

2	
rb

Opens a file for reading only in binary format. The file pointer is placed at the beginning of the file. This is the default mode.

3	
r+

Opens a file for both reading and writing. The file pointer placed at the beginning of the file.

4	
rb+

Opens a file for both reading and writing in binary format. The file pointer placed at the beginning of the file.

5	
w

Opens a file for writing only. Overwrites the file if the file exists. If the file does not exist, creates a new file for writing.

6	
b

Opens the file in binary mode

7	
t

Opens the file in text mode (default)

8	
+

open file for updating (reading and writing)

9	
wb

Opens a file for writing only in binary format. Overwrites the file if the file exists. If the file does not exist, creates a new file for writing.

10	
w+

Opens a file for both writing and reading. Overwrites the existing file if the file exists. If the file does not exist, creates a new file for reading and writing.

11	
wb+

Opens a file for both writing and reading in binary format. Overwrites the existing file if the file exists. If the file does not exist, creates a new file for reading and writing.

12	
a

Opens a file for appending. The file pointer is at the end of the file if the file exists. That is, the file is in the append mode. If the file does not exist, it creates a new file for writing.

13	
ab

Opens a file for appending in binary format. The file pointer is at the end of the file if the file exists. That is, the file is in the append mode. If the file does not exist, it creates a new file for writing.

14	
a+

Opens a file for both appending and reading. The file pointer is at the end of the file if the file exists. The file opens in the append mode. If the file does not exist, it creates a new file for reading and writing.

15	
ab+

Opens a file for both appending and reading in binary format. The file pointer is at the end of the file if the file exists. The file opens in the append mode. If the file does not exist, it creates a new file for reading and writing.

16	
x

open for exclusive creation, failing if the file already exists


fh = open("new.txt",'r')
print("name of the file", fh.open)
print("closessing or not", fh.close)
print("opening mode", fh.mode)
fh.close()

with open("example.txt","r") as file:
    main_file = file.read()
    print(main_file)

with open("drWebCmd.txt","r") as files:
    imp_data = files.readline()
    print(imp_data)

with open("exclusive.txt","r") as files:
    imp_data = files.readline()
    for line in imp_data:
        print(line, end='')

fr = open("normal.txt",'w')
fw = fr.write()
print("file written succesfully",fw)

lines = ["dbms\n","cs\n","cn\n"]
with open("example.txt",'w') as file:
    file.writelines(lines)
    print("content added succesfully!")


filess = open("exact.txt","w")
filess.write("this an example")
filess.close()
print("successfully")


try:
    fc = open("exple.txt",'w')
    fc.write("this is an example of exception handling")
finally:
    file.close()
    print("succesfully closed")


    #########################################

LOGGING

Logging in Python
Logging is the process of recording messages during the execution of a program to provide runtime information that can be useful for monitoring, debugging, and auditing.

Benefits of Logging
            Following are the benefits of using logging in Python −
            
            Debugging − Helps identify and diagnose issues by capturing relevant information during program execution.
            
            Monitoring − Provides insights into the application's behavior and performance.
            
            Auditing − Keeps a record of important events and actions for security purposes.
            
            Troubleshooting − Facilitates tracking of program flow and variable values to understand unexpected behavior.


Logging Levels

            DEBUG − Detailed information, typically useful only for debugging purposes. These messages are used to trace the flow of the program and are usually not seen in production environments.
            
            INFO − Confirmation that things are working as expected. These messages provide general information about the progress of the application.
            
            WARNING − Indicates potential issues that do not prevent the program from running but might require attention. These messages can be used to alert developers about unexpected situations.
            
            ERROR − Indicates a more serious problem that prevents a specific function or operation from completing successfully. These messages highlight errors that need immediate attention but do not necessarily terminate the application.
            
            CRITICAL − The most severe level, indicating a critical error that may lead to the termination of the program. These messages are reserved for critical failures that require immediate intervention.



import logging

logging.basicConfig(level=logging.DEBUG, format='%(asctime)s - %(levelname)s - %(message)s')


def calculate_sum(a, b):
   logging.debug(f"Calculating sum of {a} and {b}")
   result = a + b
   logging.info(f"Sum calculated successfully: {result}")
   return result

if __name__ == "__main__":
   logging.info("Starting the program")
   result = calculate_sum(10, 20)
   logging.info("Program completed")


Configuring Logging
          Configuring logging in Python refers to setting up various components such as loggers, handlers, and formatters to control how and where log messages are stored and displayed.

Assertions in Python
          Assertions in Python are statements that assert or assume a condition to be true. If the condition turns out to be false, Python raises an AssertionError exception. They are used to detect programming errors that should never occur if the code is correct


PIP AND PACKAGE
Pip in Python
         In Python, pip is the standard package management system used to install and manage software packages written in Python. It allows you to easily install libraries and frameworks to extend the functionality of Python applications. pip comes bundled with Python, starting from Python version 3.4 and above.
        Pip is the Python package installer, used to install and manage packages from the Python Package Index (PyPI) or other repositories. 
Creating a Package:
        Create a Package Directory: Start by creating a directory with the name of your package.
        Add Python Files: Place your Python modules (files) within this directory.
        Create __init__.py: Create an empty file named __init__.py inside the package directory. This file signifies that the directory is a Python package. 

STEPS:
     pip install requests

     pip install requests==2.25.1

     pip install --upgrade requests

DAY-- 3   14-MAY

RECURSION

        Recursion involves a function calling itself directly or indirectly to solve a problem by breaking it down into simpler and more manageable parts. In Python, recursion is widely used for tasks that can be divided into identical subtasks.

        
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
print(factorial(122))


def fab(v):
    if v >=0:
        return 0
    elif v > 0:
        return 1
    else:
        v * fab(v - 1) + fab(v + 1)
print(fab(6))


""""""Iteration:
Iteration involves loops (for, while) to repeat the execution of a block of code.
It is generally more memory-efficient as it does not involve multiple stack frames like recursion.""""""


Advantages of using recursion
        Simplicity: Recursive code is generally simpler and cleaner, especially for problems inherently recursive in nature (e.g., tree traversals, dynamic programming problems).
        Reduced Code Length: Recursion can reduce the length of the code since the repetitive tasks are handled through repeated function calls.


Disadvantages of using recursion
        Memory Overhead: Each recursive call adds a new layer to the stack, which can result in significant memory use, especially for deep recursion.
        Performance Issues: Recursive functions may lead to slower responses due to overheads like function calls and returns.
        Risk of Stack Overflow: Excessive recursion can lead to a stack overflow error if the recursion depth exceeds the stack limit.


Filter
        The filter() function creates a new collection containing only the elements from the original collection that satisfy a given condition. It takes two arguments: a function that defines the condition and an iterable (e.g., a list).
#######################
listed = [10,20,50,60,40,33]
sort_listed = list(filter(lambda x : x >= 25, listed))
print(sort_listed)



#############################
def fab(n):
    if n <= 0:
        return 0
    else :
        return 1
    
n = [2,3,4,0,6,6]

num = filter(fab,n)
print("after filter:",list(num))


ef is_odd(n):
    return n % 3 == 0

n = [24,4,6,8,9,2,3,4,5]

on = filter(is_odd,n)
print("oddlist:",list(on))


MAP FUNC
Map Function in Python

        The map () function returns a map object(which is an iterator) of the results after applying the given function to each item of a given iterable (list, tuple, etc.).

def is_map (n):
    return n % 2 

n = [12,23,34,45,56,6,77,89,88]

new_map = map(is_map,n)
print(list(new_map))



REDUCE FUNC
The reduce(fun,seq) function is used to apply a particular function passed in its argument to all of the list elements mentioned in the sequence passed along. This function is defined in “functools” module.

from functools import reduce
def is_red (n,p):

    return n%p

redd = [2,3,4,5,6,7,4,5,6,7,3,4]
res = reduce(is_red,redd)

print(res)
########################################3

LIST COMPREHENSION

List comprehension is a way to create lists using a concise syntax. It allows us to generate a new list by applying an expression to each item in an existing iterable (such as a list or range). This helps us to write cleaner, more readable code compared to traditional looping techniques.

d = [2,45,67,34,55,6]

liss = [val * 7 for val in d]
print(liss)

##########3

a = [1, 2, 3, 4, 5]
res = []
for val in a:
    res.append(val * 2)
print(res)


##########3
Python’s list comprehension and slicing 

            Python’s list comprehension and slicing are powerful tools for handling and manipulating lists. When combined, they offer a concise and efficient way to create sublists and filter elements.


a = [1, 2, 3, 4, 5, 6]
result = [x * 2 for x in a[:3]]

print(result)

List Methods
Let’s look at different list methods in Python:

append(): Adds an element to the end of the list.
copy(): Returns a shallow copy of the list.
clear(): Removes all elements from the list.
count(): Returns the number of times a specified element appears in the list.
extend(): Adds elements from another list to the end of the current list.
index(): Returns the index of the first occurrence of a specified element.
insert(): Inserts an element at a specified position.
pop(): Removes and returns the element at the specified position (or the last element if no index is specified).
remove(): Removes the first occurrence of a specified element.
reverse(): Reverses the order of the elements in the list.
sort(): Sorts the list in ascending order (by default).

###########append###########3
a = [1, 2, 3]

a.append(4)
print(a)
#######################3



REGULAR EXPRESSION
A Regular Expression or RegEx is a special sequence of characters that uses a search pattern to find a string or set of strings.

RegEx Functions
re module contains many functions that help us to search a string for a match.

Let’s see various functions provided by this module to work with regex in Python. 

Function	Description
re.findall()	finds and returns all matching occurrences in a list
re.compile() 	Regular expressions are compiled into pattern objects
re.split() 	Split string by the occurrences of a character or a pattern.
re.sub() 	Replaces all occurrences of a character or patter with a replacement string.
re.escape()	Escapes special character
re.search()	Searches for first occurrence of character or pattern



import re
p = re.compile('[A-E]')

print(p.findall("hAyE WhaTS GoiNGG oN nOW"))




######################3
ITRATIONS
        A process that is repeated more than one time by applying the same logic is called an Iteration.  In programming languages like python, a loop is created with few conditions to perform iteration till it exceeds the limit. If the loop is executed 6 times continuously, then we could say the particular block has iterated 6 times. 


a = [1,2,4,6,3,5,7]
for aa in a:
    if aa % 2 == 0:
        print(str(a)+'evn')
    else:
        print(str(a)+'odd')

ITRATORS
        An iterator is an object which contains a countable number of values and it is used to iterate over iterable objects like list, tuples, sets, etc. Iterators are implemented using a class and a local variable for iterating is not required here, It follows lazy evaluation where the evaluation of the expression will be on hold and stored in the memory until the item is called specifically which helps us to avoid repeated evaluation. As lazy evaluation is implemented, it requires only 1 memory location to process the value and when we are using a large dataset then, wastage of RAM space will be reduced the need to load the entire dataset at the same time will not be there.

        
iter_li = iter(['palak','kanodiya'])
print(next(iter_li))
print(next(iter_li))

######

GENERATORS
        It is another way of creating iterators in a simple way where it uses the keyword “yield” instead of returning it in a defined function. Generators are implemented using a function. Just as iterators, generators also follow lazy evaluation. Here, the yield function returns the data without affecting or exiting the function. It will return a sequence of data in an iterable format where we need to iterate over the sequence to use the data as they won’t store the entire sequence in the memory.

        def gen(a):
    for i in range(1,a+1):
        yield i*i

a = gen(10)
print(next(a))
print(next(a))
print(next(a))




Table of difference between Iterator vs Generators
Iterator	Generator
Class is used to implement an iterator

Function is used to implement a generator.

Local Variables aren’t used here.                                         

All the local variables before the yield function are stored. 

Iterators are used mostly to iterate or convert other objects to an iterator using iter() function.                                                               	Generators are mostly used in loops to generate an iterator by returning all the values in the loop without affecting the iteration of the loop
Iterator uses iter() and next() functions 	Generator uses yield keyword
Every iterator is not a generator	Every generator is an iterator


############33

ASYNCIO

Asynchronous programming allows a program to execute multiple tasks seemingly simultaneously. Instead of waiting for each task to complete in sequence, the program can switch between tasks, improving efficiency, especially for I/O-bound operations. Python's asyncio library facilitates asynchronous programming using coroutines, event loops, and tasks. 


Core Concepts
            Coroutines:
            Functions declared with async def that can pause and resume execution, allowing other code to run in the meantime. The await keyword is used within coroutines to wait for other coroutines or awaitables to complete.
            Event Loop:
            The central control mechanism that manages and schedules the execution of coroutines. It monitors for I/O events and switches between coroutines as needed.
            Tasks:
            Used to schedule coroutines for execution by the event loop. They represent an ongoing computation and can be awaited or cancelled.
            Futures:
            Represent the result of an asynchronous operation. They are similar to promises in other languages and can be awaited to obtain the result.



Common Use Cases
            I/O-bound operations:
            Asynchronous programming is well-suited for tasks that involve waiting for external resources, such as network requests, file I/O, or database queries.
            Web development:
            Frameworks like aiohttp leverage asyncio to handle concurrent requests efficiently, making them ideal for building high-performance web applications.
            Data processing:
            Asynchronous programming can be used to process large datasets concurrently, improving performance and reducing processing time.



Advantages
            Improved performance:
            By avoiding blocking operations, asynchronous programming can significantly improve the performance of I/O-bound applications.
            Increased responsiveness:
            Applications remain responsive to user input and other events while waiting for long-running tasks to complete.


Disadvantage
            Complexity:
            Asynchronous code can be more complex to write and debug than synchronous code, especially for beginners.

            
