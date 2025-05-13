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

try:
    eh = open ('my text file',"w")
    eh.write("this is my expection handling file")
finally:
    print("going to the close file")
    eh.close()




Exception

Base class for all exceptions

2	
StopIteration

Raised when the next() method of an iterator does not point to any object.

3	
SystemExit

Raised by the sys.exit() function.

4	
StandardError

Base class for all built-in exceptions except StopIteration and SystemExit.

5	
ArithmeticError

Base class for all errors that occur for numeric calculation.

6	
OverflowError

Raised when a calculation exceeds maximum limit for a numeric type.

7	
FloatingPointError

Raised when a floating point calculation fails.

8	
ZeroDivisionError

Raised when division or modulo by zero takes place for all numeric types.

9	
AssertionError

Raised in case of failure of the Assert statement.

10	
AttributeError

Raised in case of failure of attribute reference or assignment.

11	
EOFError

Raised when there is no input from either the raw_input() or input() function and the end of file is reached.

12	
ImportError

Raised when an import statement fails.

13	
KeyboardInterrupt

Raised when the user interrupts program execution, usually by pressing Ctrl+c.

14	
LookupError

Base class for all lookup errors.

15	
IndexError

Raised when an index is not found in a sequence.

16	
KeyError

Raised when the specified key is not found in the dictionary.

17	
NameError

Raised when an identifier is not found in the local or global namespace.

18	
UnboundLocalError

Raised when trying to access a local variable in a function or method but no value has been assigned to it.

19	
EnvironmentError

Base class for all exceptions that occur outside the Python environment.

20	
IOError

Raised when an input/ output operation fails, such as the print statement or the open() function when trying to open a file that does not exist.

21	
IOError

Raised for operating system-related errors.

22	
SyntaxError

Raised when there is an error in Python syntax.

23	
IndentationError

Raised when indentation is not specified properly.

24	
SystemError

Raised when the interpreter finds an internal problem, but when this error is encountered the Python interpreter does not exit.

25	
SystemExit

Raised when Python interpreter is quit by using the sys.exit() function. If not handled in the code, causes the interpreter to exit.

26	
TypeError

Raised when an operation or function is attempted that is invalid for the specified data type.

27	
ValueError

Raised when the built-in function for a data type has the valid type of arguments, but the arguments have invalid values specified.

28	
RuntimeError

Raised when a generated error does not fall into any category.

29	
NotImplementedError

Raised when an abstract method that needs to be implemented in an inherited class is not actually implemented.


Raising Exceptions in Python
In Python, you can raise exceptions explicitly using the raise statement. Raising exceptions allows you to indicate that an error has occurred and to control the flow of your program by handling these exceptions appropriately.
In Python, you can raise built-in exceptions like ValueError or TypeError to indicate common error conditions. Additionally, you can create and raise custom exceptions.

Exception Chaining
Exception chaining is a technique of handling exceptions by re-throwing a caught exception after wrapping it inside a new exception. The original exception is saved as a property (such as cause) of the new exception.

Nested try Block in Python
In a Python program, if there is another try-except construct either inside either a try block or inside its except block, it is known as a nested-try block. This is needed when different blocks like outer and inner may cause different errors. To handle them, we need nested try blocks.

User-Defined Exceptions in Python
User-defined exceptions in Python are custom error classes that you create to handle specific error conditions in your code. They are derived from the built-in Exception class or any of its sub classes.

 Logging in Python
Logging is the process of recording messages during the execution of a program to provide runtime information that can be useful for monitoring, debugging, and auditing.


VIRTUAL ENVIORNMENT

Python Virtual Environment
Python virtual environments create a virtual installation of Python inside a project directory. Users can then install and manage Python packages for each project. This allows users to be able to install packages and modify their Python environment without fear of breaking packages installed in other environments.

What is Virtual Environment in Python?
A Python virtual environment is:

Considered as disposable.
Used to contain a specific Python interpreter and software libraries and binaries which are needed to support a project.
Contained in a directory, conventionally either named venv or .venv in the project directory.
Not considered as movable or copyable.
When you install Python software on your computer, it is available for use from anywhere in the filesystem. This is a system-wide installation.


TIME AND DATE

 Python program can handle date and time in several ways. Converting between date formats is a common chore for computers. Following modules in Python's standard library handle date and time related processing −

DateTime module

Time module

Calendar module


HERE--
import time
time = time.localtime(time.time())
print(time)

# exact time date show
import time
astime = time.asctime()
print(astime)


Function with Description
1	time.altzone
The offset of the local DST timezone, in seconds west of UTC, if one is defined. This is negative if the local DST timezone is east of UTC (as in Western Europe, including the UK). Only use this if daylight is nonzero.

2	time.asctime([tupletime])
Accepts a time-tuple and returns a readable 24-character string such as 'Tue Dec 11 18:07:14 2008'.

3	time.clock( )
Returns the current CPU time as a floating-point number of seconds. To measure computational costs of different approaches, the value of time.clock is more useful than that of time.time().

4	time.ctime([secs])
Like asctime(localtime(secs)) and without arguments is like asctime( )

5	time.gmtime([secs])
Accepts an instant expressed in seconds since the epoch and returns a time-tuple t with the UTC time. Note : t.tm_isdst is always 0

6	time.localtime([secs])
Accepts an instant expressed in seconds since the epoch and returns a time-tuple t with the local time (t.tm_isdst is 0 or 1, depending on whether DST applies to instant secs by local rules).

7	time.mktime(tupletime)
Accepts an instant expressed as a time-tuple in local time and returns a floating-point value with the instant expressed in seconds since the epoch.

8	time.sleep(secs)
Suspends the calling thread for secs seconds.

9	time.strftime(fmt[,tupletime])
Accepts an instant expressed as a time-tuple in local time and returns a string representing the instant as specified by string fmt.

10	time.strptime(str,fmt='%a %b %d %H:%M:%S %Y')
Parses str according to format string fmt and returns the instant in time-tuple format.

11	time.time( )
Returns the current time instant, a floating-point number of seconds since the epoch.

12	time.tzset()
Resets the time conversion rules used by the library routines. The environment variable TZ specifies how this is done.


The calendar Module
The calendar module supplies calendar-related functions, including functions to print a text calendar for a given month or year.

import calendar 

calc = calendar.month(2026,5)
print(calc)


The calendar Module
The calendar module supplies calendar-related functions, including functions to print a text calendar for a given month or year.

By default, calendar takes Monday as the first day of the week and Sunday as the last one. To change this, call the calendar.setfirstweekday() function.

Here is a list of functions available with the calendar module −

Sr.No.	Function with Description
1	
calendar.calendar()

Returns a multi-line string with a calendar for year year formatted into three columns separated by c spaces. w is the width in characters of each date; each line has length 21*w+18+2*c. l is the number of lines for each week.

2	
calendar.firstweekday()

Returns the current setting for the weekday that starts each week. By default, when calendar is first imported, this is 0, meaning Monday.

3	
calendar.isleap()

Returns True if year is a leap year; otherwise, False.

4	
calendar.leapdays()

Returns the total number of leap days in the years within range(y1,y2).

5	
calendar.month()

Returns a multi-line string with a calendar for month month of year year, one line per week plus two header lines. w is the width in characters of each date; each line has length 7*w+6. l is the number of lines for each week.

6	
calendar.monthcalendar()

Returns a list of lists of ints. Each sublist denotes a week. Days outside month month of year year are set to 0; days within the month are set to their day-of-month, 1 and up.

7	
calendar.monthrange()

Returns two integers. The first one is the code of the weekday for the first day of the month month in year year; the second one is the number of days in the month. Weekday codes are 0 (Monday) to 6 (Sunday); month numbers are 1 to 12.

8	
calendar.prcal()

Like print calendar.calendar(year,w,l,c).

9	
calendar.prmonth()

Like print calendar.month(year,month,w,l).

10	
calendar.setfirstweekday()

Sets the first day of each week to weekday code weekday. Weekday codes are 0 (Monday) to 6 (Sunday).

11	
calendar.timegm()

The inverse of time.gmtime: accepts a time instant in time-tuple form and returns the same instant as a floating-point number of seconds since the epoch.

12	
calendar.weekday()

Returns the weekday code for the given date. Weekday codes are 0 (Monday) to 6 (Sunday); month numbers are 1 (January) to 12 (December).


import calendar 

calc = calendar.month(2026,5)
# calc = calendar.calendar(2025)
calc = calendar.firstweekday()
calc = calendar.isleap(2002)
calc = calendar.month(2002,12)
calc = calendar.monthcalendar(2023,5)
calc = calendar.prcal(2002)
calc = calendar.prmonth(2004,11)

print(calc)



Python date Object
A date object represents a date with year, month, and day. The current Gregorian calendar is indefinitely extended in both directions.

import datetime
calci = datetime.date(2023, 4, 4)
print(calci)

date class attributes
date.min − The earliest representable date, date(MINYEAR, 1, 1).

date.max − The latest representable date, date(MAXYEAR, 12, 31).

date.resolution − The smallest possible difference between non-equal date objects.

date.year − Between MINYEAR and MAXYEAR inclusive.

date.month − Between 1 and 12 inclusive.

date.day − Between 1 and the number of days in the given month of the given year.

# PYTHON DATE OBJ
from datetime import date
# calci = datetime.date(2023, 4, 4)
calci = date.min
calci = date.max
calci = date.resolution
date1 = date(2002,12,26)
calci = date1.year
calci = date1.month
calci = date1.day
print(calci)


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
    def __init__(self):
        self.name = "palak"
        self.age = 22

p1 = student()
print("my self: {}".format(p1.name))
print("my age: {}".format(p1.age))



#####parametrized


class library:
    def __init__(self,dept,serialNo):
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
