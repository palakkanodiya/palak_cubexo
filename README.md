# palak_cubexo
DAY 1 12-MAY
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

#######################3
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


####################### 
DAY 3 14 MAY

What is Package in Python?
Package refers to a distribution of Python code that includes one or more modules or libraries. These packages are typically published on the Python Package Index (PyPI) and can be easily installed using pip. Python packages may contain modules, sub-packages, and additional resources such as documentation and data files.

What is Python PIP?
Python PIP is the package manager for Python packages. We can use PIP to install packages that do not come with Python.


How to Install Python PIP?
Python PIP comes pre-installed on 3.4 or older versions of Python. To Check if PIP is Installed or not type the below command in the terminal.


pip –version



How to Install Package with Python PIP
We can install additional packages by using the Python pip install command. Let’s suppose we want to install the Numpy using PIP. We can do it using the below command.

Syntax: 


pip install numpy



Specifying Package Version using Python PIP
We can also install the package of a specific version by using the below command.

Syntax: 


pip install package_name==version


Display Package information using Python PIP
We can use the Python pip show command to display the details of a particular package. 

Syntax: 


pip show numpy


Get a list of locally installed Python Modules using Python PIP
The Python pip list command displays a list of packages installed in the system. 

Syntax: 


pip list


Uninstall Packages with Python PIP
The Python pip uninstall command uninstalls a particular existing package. 

Syntax: 


pip uninstall numpy


Search Packages with Python PIP
We can search for a particular existing package using the Python pip search command. 

Syntax: 


pip search numpy


Using Requirement files with Python PIP

Syntax: 


pip install -r requirements.txt


Downgrading Packages with Python PIP
the Python pip install –user command is used to downgrade a package to a specific version.

Syntax:


pip install –user package_name==version

####################3


Map Reduce and Filter Operations in Python
Below, are examples of Map Reduce and Filter Operations in Python:

map() Function
Reduce() Function
Filter() Function


Map Function in Python
The map () function returns a map object(which is an iterator) of the results after applying the given function to each item of a given iterable (list, tuple, etc.).

Syntax: map(fun, iter)

Parameters:

fun: It is a function to which map passes each element of given iterable.
iter:  iterable object to be mapped.

# Function to return double of n
def double(n):
    return n * 2

# Using map to double all numbers
numbers = [5, 6, 7, 8]
result = map(double, numbers)
print(list(result))

Reduce Function in Python
The reduce function is used to apply a particular function passed in its argument to all of the list elements mentioned in the sequence passed along.This function is defined in “functools” module.

Syntax: reduce(func, iterable[, initial])

Parameters:

fun: It is a function to execute on each element of the iterable object.
iter: It is iterable to be reduced

import functools

# Define a list of numbers
numbers = [1, 2, 3, 4]

# Use reduce to compute the product of list elements
product = functools.reduce(lambda x, y: x * y, numbers)
print("Product of list elements:", product)



Filter Function in Python
The filter() method filters the given sequence with the help of a function that tests each element in the sequence to be true or not. 

Syntax: filter(function, sequence)

Parameters:

function: function that tests if each element of a sequence is true or not.
sequence: sequence which needs to be filtered, it can be sets, lists, tuples, or containers of any iterators.


# Define a function to check if a number is even
def is_even(n):
    return n % 2 == 0

# Define a list of numbers
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

# Use filter to filter out even numbers
even_numbers = filter(is_even, numbers)
print("Even numbers:", list(even_numbers))


RECURSIVE FUNC

In other words, a recursive function is a function that solves a problem by solving smaller instances of the same problem. This technique is commonly used in programming to solve problems that can be broken down into simpler, similar subproblems.

Need of Recursive Function:
A recursive function is a function that solves a problem by solving smaller instances of the same problem. This technique is often used in programming to solve problems that can be broken down into simpler, similar subproblems.


1. Solving complex tasks:
Recursive functions break complex problems into smaller instances of the same problem, resulting in compact and readable code.

2. Divide and Conquer:
Recursive functions are suitable for divide-and-conquer algorithms such as merge sort and quicksort, breaking problems into smaller subproblems, solving them recursively, and merging the solutions with the original problem.

3. Backtracking:
Recursive backtracking is ideal for exploring and solving problems like N-Queens and Sudoku.

4. Dynamic programming:
Recursive functions efficiently solve dynamic programming problems by solving subproblems and combining their solutions into a complete solution.

5. Tree and graph structures:
Recursive functions are great for working with tree and graph structures, simplifying traversal and pattern recognition tasks.


Components of a recursive function:
Base case: Every recursive function must have a base case. The base case is the simplest scenario that does not require further recursion. This is a termination condition that prevents the function from calling itself indefinitely. Without a proper base case, a recursive function can lead to infinite recursion.

Recursive case: In the recursive case, the function calls itself with the modified arguments. This is the essence of recursion – solving a larger problem by breaking it down into smaller instances of the same problem. The recursive case should move closer to the base case with each iteration.


#include <iostream>
using namespace std;

// Recursive Function to calculate Factorial of a number
int factorial(int n)
{
    // Base case
    if (n == 0) {
        return 1;
    }

    // Recursive case
    return n * factorial(n - 1);
}

// Driver Code

int main()
{
    int n = 4;

    cout << "Factorial of " << n
         << " is:" << factorial(n);
    return 0;
}



##############3
LIST COMPREHENSIVE


List comprehensions offer a concise way to create lists in Python, while regular expressions provide a powerful tool for pattern matching in strings. They can be effectively combined to filter or transform list elements based on complex string patterns.

List Comprehension
It provides a compact syntax for creating new lists by applying an expression to each item in an existing iterable (like a list, tuple, or range). 


numbers = [1, 2, 3, 4, 5]
squared_numbers = [x**2 for x in numbers]
print(squared_numbers)  # Output: [1, 4, 9, 16, 25]


Regular Expressions
They are sequences of characters that define a search pattern. Python's re module enables operations like searching, matching, and substituting text based on these patterns.


import re
text = "The quick brown fox jumps over the lazy dog."
pattern = r"fox"
match = re.search(pattern, text)
if match:
    print("Pattern found:", match.group())  # Output: Pattern found: fox



Combining List Comprehension and Regular Expressions
List comprehensions can incorporate regular expressions to filter or modify list elements based on pattern matches.


import re
words = ["apple", "banana", "cherry", "date", "elderberry"]
pattern = r"^a"  # Words starting with "a"
filtered_words = [word for word in words if re.match(pattern, word)]
print(filtered_words)  # Output: ['apple']


Transforming with Regular Expressions

import re
log_entries = ["ERROR: File not found", "INFO: Operation successful", "WARNING: Disk space low"]
pattern = r"^(ERROR|WARNING): (.*)"
formatted_entries = [re.sub(pattern, r"\1 - \2", entry) for entry in log_entries]
print(formatted_entries)


##########################

Iterator
An iterator is an object which contains a countable number of values and it is used to iterate over iterable objects like list, tuples, sets, etc. Iterators are implemented using a class and a local variable for iterating is not required here, It follows lazy evaluation where the evaluation of the expression will be on hold and stored in the memory until the item is called specifically which helps us to avoid repeated evaluation. As lazy evaluation is implemented, it requires only 1 memory location to process the value and when we are using a large dataset then, wastage of RAM space will be reduced the need to load the entire dataset at the same time will not be there.


Using an iterator-

iter() function is used to create an iterator containing an iterable object.
next() function is used to call the next element in the iterable object.

iter_list = iter(['Geeks', 'For', 'Geeks'])
print(next(iter_list))
print(next(iter_list))
print(next(iter_list))



Generators
It is another way of creating iterators in a simple way where it uses the keyword “yield” instead of returning it in a defined function. Generators are implemented using a function. Just as iterators, generators also follow lazy evaluation. Here, the yield function returns the data without affecting or exiting the function. It will return a sequence of data in an iterable format where we need to iterate over the sequence to use the data as they won’t store the entire sequence in the memory.

def sq_numbers(n):
    for i in range(1, n+1):
        yield i*i


a = sq_numbers(3)

print("The square of numbers 1,2,3 are : ")
print(next(a))
print(next(a))
print(next(a))



Table of difference between Iterator vs Generators
Iterator	Generator
Class is used to implement an iterator

Function is used to implement a generator.

Local Variables aren't used here.                                         

All the local variables before the yield function are stored. 

Iterators are used mostly to iterate or convert other objects to an iterator using iter() function.                                                               	Generators are mostly used in loops to generate an iterator by returning all the values in the loop without affecting the iteration of the loop
Iterator uses iter() and next() functions 	Generator uses yield keyword
Every iterator is not a generator	Every generator is an iterator


#################3

asyncio in Python

Asyncio is a Python library that is used for concurrent programming, including the use of async iterator in Python. It is not multi-threading or multi-processing. Asyncio is used as a foundation for multiple Python asynchronous frameworks that provide high-performance network and web servers, database connection libraries, distributed task queues, etc

Asynchronous Programming with Asyncio in Python:


async def fn():
    print("hello")
    await asyncio.sleep(2)
    await fn2()
    print("hii : sb bdia??")
    await asyncio.sleep(3)
    print("bye ")

async def fn2():
    print("bbyyeeee")
    await asyncio.sleep(1)
    print("wru")
    await asyncio.sleep(3)
    print("hru:")

# asyncio.run(fn2())ṇnnnn
asyncio.run(fn())


I/O-bound tasks using asyncio.sleep():

import asyncio


async def func1():
    print("Function 1 started..")
    await asyncio.sleep(2)
    print("Function 1 Ended")


async def func2():
    print("Function 2 started..")
    await asyncio.sleep(3)
    print("Function 2 Ended")


async def func3():
    print("Function 3 started..")
    await asyncio.sleep(1)
    print("Function 3 Ended")


async def main():
    L = await asyncio.gather(
        func1(),
        func2(),
        func3(),
    )
    print("Main Ended..")


asyncio.run(main())



######################

PEP 8 
PEP 8 : Coding Style guide in Python


Indeed coding and applying logic is the foundation of any programming language but there's also another factor that every coder must keep in mind while coding and that is the coding style. Keeping this in mind, Python maintains a strict way of order and format of scripting.Following this sometimes mandatory and is a great help on the user's end, to understand. Making it easy for others to read code is always a good idea, and adopting a nice coding style helps tremendously for that. For Python, PEP 8 has emerged as the style guide that most projects adhere to; it promotes a very readable and eye-pleasing coding style. Every Python developer should read it at some point; here are the most important points extracted for you: 


1. Use 4-space indentation and no tabs.

grow = function_name(variable_one, variable_two,
                     variable_three, variable_four)



#########
def function_name(
        variable_one, variable_two, variable_three,
        variable_four):
    print(variable_one)


2. Use docstrings

 def exam():
    """This is single line docstring"""

    """This is
    a
    multiline comment"""

3. Wrap lines so that they don't exceed 79 characters :

 with open('/path/from/where/you/want/to/read/file') as file_one, \
     open('/path/where/you/want/the/file/to/be/written', 'w') as file_two:
 file_two.write(file_one.read())  

4. Use of regular and updated comments are valuable to both the coders and users:

 geek = geek + 1                 # Increment

 5. Use of trailing commas : 
tup = ("geek",)

6. Use spaces around operators and after commas, but not directly inside bracketing constructs:
a = f(1, 2) + g(3, 4)


7. Naming Conventions :

b (single lowercase letter)

B (single upper case letter)

lowercase

lower_case_with_underscores

UPPERCASE

UPPER_CASE_WITH_UNDERSCORES

CapitalizedWords (or CamelCase). This is also sometimes known as StudlyCaps.
Note: While using abbreviations in CapWords, capitalize all the letters 
of the abbreviation. Thus HTTPServerError is better than HttpServerError.

mixedCase (differs from CapitalizedWords by initial lowercase character!)

Capitalized_Words_With_Underscores


8. Characters that should not be used for identifiers : 'l' (lowercase letter el), 'O' (uppercase letter oh), or 'I' (uppercase letter eye) as single character variable names as these are similar to the numerals one and zero.

9.  Don’t use non-ASCII characters in identifiers if there is only the slightest chance people speaking a different language will read or maintain the code.

10.  Name your classes and functions consistently : The convention is to use CamelCase for classes and lower_case_with_underscores for functions and methods. Always use self as the name for the first method argument.

 11. While naming of function of methods always use self for the first argument to instance methods and cls for the first argument to class methods.If a functions argument name matches with reserved words then it can be written with a trailing comma.

 # Python program to find the
# factorial of a number provided by the user. 

# change the value for a different result 
num = 7

# uncomment to take input from the user 
#num = int(input("Enter a number: ")) 

factorial = 1

# check if the number is negative, positive or zero 
if num < 0: 
    print("Sorry, factorial does not exist for negative numbers") 
elif num == 0: 
    print("The factorial of 0 is 1") 
else: 
    for i in range(1,num + 1): 
        factorial = factorial*i 
        
print("The factorial of",num,"is",factorial)

##########3

# Import needed package
from collections import defaultdict

# Define our data
list_data = [1, 2, 3, 4, 2, 4, 1, 2]


# Helper Function
def list_to_dict(input_list):
    """Convert list to DefaultDict"""
    d = defaultdict(int)
    for i in input_list:
        d[i] += 1
    return d


# Output
print(ltd(list_data))


################

Closures And Decorators In Python

Closures and decorators are powerful features in Python that allow for more advanced and flexible code patterns. Understanding these concepts can greatly enhance your ability to write clean, efficient, and reusable code.


Closures in Python
A closure in Python occurs when a nested function captures the local variables from its enclosing scope. This allows the nested function to access these variables even after the outer function has finished executing.

How Closures Work
Closures are created when:

There is a nested function.
The nested function references a value in its enclosing scope.
The enclosing function returns the nested function.


# code
def outer_function(msg):
    message = msg
    
    def inner_function():
        print(message)
    
    return inner_function

closure = outer_function("Hello, World!")
closure()  # Output: Hello, World!



Decorators in Python
Python Decorators are a powerful and expressive tool in Python that allows you to modify the behavior of a function or method. They are often used to add "wrapping" functionality to existing functions in a clean and readable way.

How Decorators Work
A decorator is a function that takes another function as an argument, adds some kind of functionality, and returns a new function. 

# code
def simple_decorator(func):
    def wrapper():
        print("Something is happening before the function is called.")
        func()
        print("Something is happening after the function is called.")
    return wrapper

@simple_decorator
def say_hello():
    print("Hello!")

say_hello()


Combining Closures and Decorators

# code
def count_calls(func):
    def wrapper(*args, **kwargs):
        wrapper.calls += 1
        print(f"Call {wrapper.calls} of {func.__name__}")
        return func(*args, **kwargs)
    wrapper.calls = 0
    return wrapper

@count_calls
def say_hello():
    print("Hello!")

say_hello()
say_hello()

#######################


Memory Management in Python

Understanding Memory allocation is important to any software developer as writing efficient code means writing a memory-efficient code. Memory allocation can be defined as allocating a block of space in the computer memory to a program. In Python memory allocation and deallocation method is automatic as the Python developers created a garbage collector for Python so that the user does not have to do manual garbage collection.


Garbage Collection

Garbage collection is a process in which the interpreter frees up the memory when not in use to make it available for other objects. Assume a case where no reference is pointing to an object in memory i.e. it is not in use so, the virtual machine has a garbage collector that automatically deletes that object from the heap memory.

Memory Allocation in Python
There are two parts of memory:
stack memory
heap memory


Work of Stack Memory

def func(): 
      
    # All these variables get memory  
    # allocated on stack  
    a = 20
    b = [] 
    c = ""


Work of Heap Memory

# This memory for 10 integers  
# is allocated on heap.  
a = [0]*10


###################

Multithreading in Python

This article covers the basics of multithreading in Python programming language. Just like multiprocessing , multithreading is a way of achieving multitasking. In multithreading, the concept of threads is used.


An Intro to Python Threading
A thread is an entity within a process that can be scheduled for execution. Also, it is the smallest unit of processing that can be performed in an OS (Operating System). In simple words, a thread is a sequence of such instructions within a program that can be executed independently of other code. 


An Intro to Threading in Python
Multithreading is defined as the ability of a processor to execute multiple threads concurrently. In a simple, single-core CPU, it is achieved using frequent switching between threads. This is termed context switching . In context switching, the state of a thread is saved and the state of another thread is loaded whenever any interrupt (due to I/O or manually set) takes place. Context switching takes place so frequently that all the threads appear to be running parallelly (this is termed multitasking ).

Multithreading in Python

Step 1: Import Module

First, import the threading module.

import threading

Step 2: Create a Thread

To create a new thread, we create an object of the Thread class. It takes the 'target' and 'args' as the parameters. The target is the function to be executed by the thread whereas the args is the arguments to be passed to the target function.

t1 = threading.Thread(target, args)
t2 = threading.Thread(target, args)


Step 3: Start a Thread

To start a thread, we use the start() method of the Thread class.

t1.start()
t2.start()


Step 4: End the thread Execution

Once the threads start, the current program (you can think of it like a main thread) also keeps on executing. In order to stop the execution of the current program until a thread is complete, we use the join() method.

t1.join()
t2.join()


import threading


def print_cube(num):
    print("Cube: {}" .format(num * num * num))


def print_square(num):
    print("Square: {}" .format(num * num))


if __name__ =="__main__":
    t1 = threading.Thread(target=print_square, args=(10,))
    t2 = threading.Thread(target=print_cube, args=(10,))

    t1.start()
    t2.start()

    t1.join()
    t2.join()
    print("Done!")

################



import threading
import os

def task1():
    print("Task 1 assigned to thread: {}".format(threading.current_thread().name))
    print("ID of process running task 1: {}".format(os.getpid()))

def task2():
    print("Task 2 assigned to thread: {}".format(threading.current_thread().name))
    print("ID of process running task 2: {}".format(os.getpid()))

if __name__ == "__main__":

    print("ID of process running main program: {}".format(os.getpid()))

    print("Main thread name: {}".format(threading.current_thread().name))

    t1 = threading.Thread(target=task1, name='t1')
    t2 = threading.Thread(target=task2, name='t2')

    t1.start()
    t2.start()

    t1.join()
    t2.join()



Python ThreadPool
A thread pool is a collection of threads that are created in advance and can be reused to execute multiple tasks. The concurrent.futures module in Python provides a ThreadPoolExecutor class that makes it easy to create and manage a thread pool.


import concurrent.futures

def worker():
    print("Worker thread running")

pool = concurrent.futures.ThreadPoolExecutor(max_workers=2)

pool.submit(worker)
pool.submit(worker)

pool.shutdown(wait=True)

print("Main thread continuing to run")

#########################

DAY 4  15 MAY

Testing (PieTests, UnitTests)

Pytest and Unittest are two popular options when it comes to Python testing frameworks. Pytest provides versatility and simplicity, enabling strong fixtures and succinct test code. However, Python's built-in testing framework, Unittest, offers a more conventional method with an object-oriented structure. For testing to be efficient and productive in Python projects, it is essential to understand the benefits and differences of each framework.


unittest (or PyUnit):
                    This is Python's built-in testing framework, inspired by Java's JUnit. It allows you to write test cases using classes and methods, and provides assertion methods for checking expected outcomes.

                    
pytest: 
        This is a popular third-party testing framework that simplifies writing and running tests. It offers powerful features like fixtures (for setting up test environments), parameterized testing, and plugins for extending functionality.
 
What is Pytest?

                Pytest is a powerful and popular testing framework for Python that simplifies the process of writing and executing tests. It offers a more concise and readable syntax compared to Python's built-in unittest framework, making it easier for developers to write tests effectively. Pytest supports a wide range of test types, including unit tests, functional tests, and integration tests, allowing developers to test various aspects of their codebase. One of the key features of Pytest is its fixture mechanism, which enables the setup and teardown of test environments, data, and dependencies. This makes it easier to create and manage complex test scenarios.


Features of Pytest

Readability and Simplicity:
                       It provides a more straightforward syntax than Unittest, which results in more readable and succinct test code. Tests are frequently written in a more organic, Python-like manner.
Robust Features: 
              It boasts an extensive feature set that includes robust assertion introspection, parameterization, and fixtures. Writing adaptable and maintainable test suites is facilitated by these capabilities.
Third-party Plugins: 
                Its capability is expanded by a wide range of third-party plugins. This enables developers to alter their testing procedures to suit their requirements.
Automatic Test Discovery:
                     Test Functions and Methods are automatically found and executed by Pytest, eliminating the need for explicit test discovery scripts. This reduces boilerplate code and streamlines the organization of tests.

Advantages of Pytest

Extensions: 
         It can be made more functional by a large community of third-party plugins. This enables developers to alter their testing procedures to suit their requirements.
Robust Features:
             Pytest boasts an extensive feature set that includes robust assertion introspection, parameterization, and fixtures. Developers can create flexible and manageable test code with these features.
Integration: 
          Pytest easily interfaces with Jenkins and Travis CI continuous integration tools, as well as with other testing frameworks like Unittest and Nose.

Disadvantages of Pytest

Learning Curve: 
             While Pytest is simple to use, developers who are new to the framework may find it difficult to keep up with its vast feature set. It could take some initial study to fully comprehend and utilize all of Pytest's features.
Effort Required for Migration:
                            It could take some work to convert test suites from other frameworks to Pytest, especially if the tests mostly rely on framework-specific features or standards.
Dependency on External Libraries:
                               Certain sophisticated capabilities, such as fixtures and parameterization, depend on external libraries. These libraries offer capabilities to Pytest, but they also introduce new dependencies that might need to be handled.



What is Unittest?
 
Unittest is a testing framework that comes with the standard Python library and is mostly utilized for unit testing. It offers a collection of classes and functions for arranging test suites, writing test cases, and executing tests. By subclassing unittest, developers can specify test cases with unittest.To make assertions and confirm expected behavior, use TestCase and methods like assertEqual, assertTrue, and assertRaises. The unittest test runner facilitates the automation of test execution and discovery,


Features of Unittest

Built-in to Python: 
                    It is easily accessible without requiring any other dependencies because it is a part of the Python standard library. For applications with limited external dependencies, this may be helpful.
Test Isolation: 
                Generating distinct test cases for every unit being tested, promotes test isolation. Test cases and test suite organization may improve as a result.
Assertion Methods:
                It comes with a large number of built-in assertion methods that let developers make different kinds of assertions without the need for further libraries.
Compatibility: 
                It is a good option for projects where familiarity and consistency with common Python modules are important since it is extensively used and understood.
                
Advantages of Unittest

Integration with IDEs: 
                    It has built-in support in several integrated development environments (IDEs), including PyCharm and Visual Studio Code, which allows for the execution, discovery, and visualization of test results right within the IDE.
Versatility:
            It is a flexible testing framework that may be used to create functional, integration, and unit tests, among other test kinds. Due to its adaptability, developers can create tests for smaller functions and classes as well as larger components and modules at various stages of the software stack.
Test Discovery: 
                Test cases within Python modules and packages are automatically found and run by Unittest's built-in test discovery mechanism.
                
Disadvantages of Unittest

Less Community Support: 
                    Compared to other testing frameworks, it might have fewer third-party plugins and less community support, while being widely used. This can restrict developers who use Unittest in their applications from accessing extra functionality or support materials.
Limited Flexibility: 
                In comparison to some other testing frameworks, such as Pytest, it has fewer built-in capabilities and flexibility. Developers may find it more difficult to design sophisticated testing scenarios or modify testing procedures without using third-party libraries or workarounds as a result.
Boilerplate Code:
                Compared to other testing frameworks like Pytest, it necessitates writing more boilerplate code. This may result in repetitious and verbose test code, which would raise maintenance costs and make the code harder to read.

#########################

Django - Intro and Features

What is Django?
Django is a Python framework that makes it easier to create web sites using Python.

Django takes care of the difficult stuff so that you can concentrate on building your web applications.

Django emphasizes reusability of components, also referred to as DRY (Don't Repeat Yourself), and comes with ready-to-use features like login system, database connection and CRUD operations (Create Read Update Delete).

Django is especially helpful for database driven websites.


How does Django Work?
Django follows the MVT design pattern (Model View Template).

Model - The data you want to present, usually data from a database.
View - A request handler that returns the relevant template and content - based on the request from the user.
Template - A text file (like an HTML file) containing the layout of the web page, with logic on how to display the data.


Model
The model provides data from the database.

In Django, the data is delivered as an Object Relational Mapping (ORM), which is a technique designed to make it easier to work with databases.

The most common way to extract data from a database is SQL. One problem with SQL is that you have to have a pretty good understanding of the database structure to be able to work with it.

Django, with ORM, makes it easier to communicate with the database, without having to write complex SQL statements.

The models are usually located in a file called models.py.

View
A view is a function or method that takes http requests as arguments, imports the relevant model(s), and finds out what data to send to the template, and returns the final result.

The views are usually located in a file called views.py.

Template
A template is a file where you describe how the result should be represented.

Templates are often .html files, with HTML code describing the layout of a web page, but it can also be in other file formats to present other results, but we will concentrate on .html files.

Django uses standard HTML to describe the layout, but uses Django tags to add logic:

<h1>My Homepage</h1>

<p>My name is {{ firstname }}.</p>
The templates of an application is located in a folder named templates.


URLs
Django also provides a way to navigate around the different pages in a website.

When a user requests a URL, Django decides which view it will send it to.

This is done in a file called urls.py.


So, What is Going On?

Django receives the URL, checks the urls.py file, and calls the view that matches the URL.
The view, located in views.py, checks for relevant models.
The models are imported from the models.py file.
The view then sends the data to a specified template in the template folder.
The template contains HTML and Django tags, and with the data it returns finished HTML content back to the browser.


Django Create Project

My First Project
django-admin startproject my_tennis_club

Run the Django Project
python manage.py runserver


Django Create App

Create App
python manage.py startapp members

##############
Django Views

Views

Django views are Python functions that take http requests and return http response, like HTML documents.

A web page that uses Django is full of views with different tasks and missions.

Views are usually put in a file called views.py located on your app's folder.

from django.shortcuts import render

# Create your views here.

from django.shortcuts import render
from django.http import HttpResponse

def members(request):
    return HttpResponse("Hello world!")


###############

Django URLs

URLs
Create a file named urls.py in the same folder as the views.py file, and type this code in it:

from django.urls import path
from . import views

urlpatterns = [
    path('members/', views.members, name='members'),
]


from django.contrib import admin
from django.urls import include, path

urlpatterns = [
    path('', include('members.urls')),
    path('admin/', admin.site.urls),
]


python manage.py runserver

#################3

Templates
In the Django Intro page, we learned that the result should be in HTML, and it should be created in a template, so let's do that.

Create a templates folder inside the members folder, and create a HTML file named myfirst.html.

<!DOCTYPE html>
<html>
<body>

<h1>Hello World!</h1>
<p>Welcome to my first Django project!</p>

</body>
</html>


Modify the View
Open the views.py file in the members folder, and replace its content with this:

my_tennis_club/members/views.py:

from django.http import HttpResponse
from django.template import loader

def members(request):
  template = loader.get_template('myfirst.html')
  return HttpResponse(template.render())


Change Settings

INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'members'
]

python manage.py migrate #run cmd

python manage.py runserver #run server
#########3


Django Models

A Django model is a table in your database.

Django Models
Up until now in this tutorial, output has been static data from Python or HTML templates.

Now we will see how Django allows us to work with data, without having to change or upload files in the process.

In Django, data is created in objects, called Models, and is actually tables in a database.

Create Table (Model)

from django.db import models

class Member(models.Model):
  firstname = models.CharField(max_length=255)
  lastname = models.CharField(max_length=255)

Migrate

python manage.py makemigrations members


from django.db import migrations, models


class Migration(migrations.Migration):

    initial = True

    dependencies = [
    ]

    operations = [
        migrations.CreateModel(
            name='Member',
            fields=[
                ('id', models.BigAutoField(auto_created=True, primary_key=True, serialize=False, verbose_name='ID')),
                ('firstname', models.CharField(max_length=255)),
                ('lastname', models.CharField(max_length=255)),
            ],
        ),
    ]


Run the migrate command:

python manage.py migrate

###########
View SQL

python manage.py sqlmigrate members 0001

  
