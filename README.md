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


