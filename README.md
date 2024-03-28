# Python

# Python-Week-1
Setting up the PC and installing the correct software on it and got to learn abit more about the computers work. Learned that Python is one of the simply languages to learn unlike Java and JavaScript. Installed VS code and PyCharm to use throughout the year while working with Python. Learned what python comments symbol is. Sorted out Jupyter Notebook on my broswer. 
Variables
The basic unit of a program is called a variable,which is assigned a value.If a variable name begins with a number, it cannot be used, but a variable name can include upper and lower case letters, as well as underscores. Variable names traditionally begin with lowercase letters in Python. Learned that there are serveral types of variables in Python, including integers, which are whole numbers; floats, which are decimal numbers; complex numbers, which are used for complex mathematical calculations; and strings, which are collections of characters. Booleans, which are true or false values, are another type of variable in Python.
Data Structures
data structures allow for the storage of a list of values in a single variable.We learned about the diffrent data structure you can find in python(Lists and sets) 
data structures allow for the storage of a list of values in a single variable. The first data structure we learn about is a list, which can contain any data type, including a list within a list. 
order of elements in a set is not important, unlike in a list. Tuples are similar to lists, except they cannot be modified once declared.
Operators
Operators are instructions that perform operations on variables and values in Python. They are used to manipulate and perform actions on data. The most familiar type of operator is the arithmetic operator, which is used for mathematical calculations. 
Division can be performed using the forward slash operator, and it returns a floating-point value, even if the result is a whole number.
Comparison operators, logical operators, identity operators, and membership operators are another set of operators in Python. Comparison operators evaluate two variables or values and produce a Boolean result, either true or false. 
Control Flow
if statement is one of the three main types of control flow in programming, and it allows you to execute a block of code only if a certain condition is met. In Python, you use the if statement like this: "a = True, if a: print It is true." 
ou can use a while loop in Python like this: "a = 0, while a < 5: print a, a = a + 1." It's important to make sure that the condition in the while loop will eventually become false, otherwise, the loop will continue indefinitely.
Functions
A function is like a machine that takes inputs and produces outputs, just like a toaster that takes in bread and produces toast. Even if the input is not bread, the toaster can still apply its toasting function. 
functions can be defined using the "def" keyword followed by the function name and arguments in parentheses. 
contains the code that performs the desired operation on the inputs, and the "return" keyword is used to specify the output. 
Classes and Objects
As a classic example to demonstrate classes in programming, we can create a class called Dog, as it has multiple functions and attributes, such as legs, a name, and bark. When we define a class, we use an uppercase letter for the class name, and we start defining all the functions and attributes inside the class definition. 
Ints and Floats
two fundamental number types in Python,
One pitfall of floats is that they are approximations, which can result in rounding errors. For instance, 1.2 minus 1.0 equals 0.19999999999999996 instead of 0.2. Floats are stored as binary ones and zeros in memory, and due to limited memory, Python makes approximations, leading to these rounding errors.
Suppose we have 256.0 and want to convert it back to an int. We can use the int class, not function, to do this. Although it looks like a function, int is a built-in class in Python, along with other types like strings, floats, and lists.
Alternative Number Types
you pass a number as a string, the int class will convert it to an integer
if you pass a second argument as a number, it will convert the first argument from that base to base
first argument must always be a string, even if you want to convert it from a different base
Floats are great, but they have floating point errors that can be problematic in certain situations, such as when dealing with money  
With the decimal class, you can instantiate a decimal object with a number value. For instance, decimal 1 divided by decimal 3 returns 0.3333 with four decimal places. You can also pass in a float, but be aware that the decimal module will try to exactly replicate the float with all its digits, which may lead to floating point errors. 
Booleans
True and false, right?
I even have to check the Python terminal to make sure I'm using boolean logic correctly
Boolean true is true, of course, and anything other than an empty string is also true
Python easily casts integers to booleans
We can also cast data structures to booleans. An empty list or dictionary is false, but anything inside is true
booleans are usually used in if statements or loops, so we need to know how to evaluate their values.
Strings
Python involves a lot of work with strings, whether you're parsing them to extract data or constructing them to present information to the user.
Python has a few ways to create strings, including string concatenation and f-strings. F-strings allow us to insert variables or expressions inside curly braces in a string. 
if we have the string "My name is Iron-Man," we can get the first character by using name[0], 
Bytes
When Python loads that data, it knows what type it is - string, int, class, etc. But sometimes all you want is raw data, like a random sequence of ones and zeros.
let's create an empty bytes object that's four bytes long. This is represented as /x followed by two hexadecimal numbers. Each byte has eight bits. If you see a b in front of something printed out, it's a bytes object. 
Lists
We have covered strings in Python, which are similar to lists and use the same slicing syntax.
If we want to insert an item at a specific position in the list, we can use the insert() method. For instance, if we want to insert the value 10 at position 3 in myList, we can type myList.insert(3, 10) and then print myList.
There are two ways to remove items from a list. The first method is called remove(), which removes an item based on its value, not its index. For instance, if we want to remove the value 5 from myList, we can type myList.remove(5) and then print myList. However, if we try to remove a value that isn't in the list, we will get an error.
Tuples and Sets
Let's take a closer look at two data structures that we briefly covered before tuples and sets. First, let's talk about sets. A set is defined using curly brackets, like this: {'a', 'b', 'c'}, mySet. You can also define a set by passing any iterable object in the constructor of the set class, like this: mySet = set(('a', 'b', 'c')). 
You can also check if an element is in a set using the membership operator (in) and find the length of a set using the length() function. Lastly, sets have a pop() function that removes and returns an arbitrary element from the set.
Dictionaries
In Python, you will commonly work with two main data structures: lists and dictionaries. Combining lists and dictionaries can solve nearly 95% of your data structure needs. Let's take a look at some examples using a dictionary of animals. 
To access a specific key-value pair in the dictionary, you can simply type the name of the dictionary followed by the key in square brackets. To add a new key-value pair, you can use a similar syntax with the assignment operator.
List Comprehensions
List comprehension is a special feature in Python that sets it apart from other programming languages. The term "comprehension" here has nothing to do with understanding, but rather with the comprehensive listing of things. 
Using a list comprehension, we can multiply each item in the list by two, like this: two times item for item in my list. This is really cool, right? The list comprehension is enclosed in square brackets, and the syntax is similar to that of a for loop
Now, let's tweak the code a bit. Instead of selecting the items that are divisible by 10, we'll select the items whose remainder after division by 10 is less than 3. This means we will get a list containing the numbers that end in 0, 1, or 2. Pretty neat, huh?
Dictionaries and Comprehensions
In Python, you can use dictionary comprehensions to create a new dictionary from an iterable structure, much like how list comprehensions create a new list. To demonstrate, let's start with a list of tuples as our key-value pairs. We can use the syntax "animals = {item[0]: item[1] for item in animalList}" to create a dictionary from this list. Notice that we use a colon to separate the key and value, and surround the comprehension with curly braces.
There is actually a more concise way to write this dictionary comprehension using tuple unpacking. Instead of using "item[0]: item[1]", we can use "key: value" and replace "item" with "(key, value)". 
If and Else
If you are new to this topic, then you have come to the right place because they are essential for writing most programs. Although we previously covered if and else statements, we will introduce a new statement that can be added to these blocks, along with a new syntax for using the if statement.
Let's dive into the code! Here's a classic problem in programming: iterating through numbers one to 100 and printing "Fizz" if the number is divisible by three, "Buzz" if divisible by five, "FizzBuzz" if divisible by 15, and the number itself if none of the above conditions are met. We can write this in Python using if and else statements.
While
It's important to be careful when running code that has a while loop, because it can run forever. If you want to exit a loop early, you can use the break statement, which will exit the loop and move on to the next line of code outside of the loop. On the other hand, if you want to skip over certain lines within a loop, you can use the continue statement, which will skip over any lines that come after it and jump back to the top of the loop to start the next iteration.
For
With the for loop, you can declare a new variable, like "item," to hold the value of each element in your list as you iterate through it. It's short and sweet, and it's actually the most common loop you'll use when coding in Python. 
Week summary
Python is a highly popular dynamic programming language used by numerous large organizations, such as Google, Yahoo, and IBM. It is compatible with all major operating systems and often comes pre-installed on Macs, as well as most Linux and Unix-based systems.
Python is a widely popular introductory programming language due to its intuitive syntax, ease of use, and similarity to other programming languages. This course covered the foundations of Python and worked up the knowledge and skills that will give you a strong programming background

# Python-Week-2
Functions
Functions are composed of a name and parameters, which are denoted by the def statement. So, to create a function, let's call it performOperation and include num1, num2, and operation as parameters.
Named Parameters
If we remove this part, we'll end up with a total of five. However, we can also assign our own value. We use "operation equals multiply" to override it. When calling this function, there's no need to explicitly state "operation equals multiply". 
*args
There is a rule when using keyword arguments in Python i.e. they must come after the positional arguments. The order of the first two arguments is important and cannot be changed.
**kwargs
In order to handle keyword arguments, a method called kwargs can be used. Kwags is short for keyword arguments. Print kwargs to see that the keyword arguments are now 
stored as a dictionary instead of a tuple.
Function Scope
In our earlier section, *args and **kwargs were used to print out the arguments passed into a function. This allowed us to see a tuple and dictionary of the passed arguments. However, there's another method that allows us to access all the variables within a Python function without any asterisks.
locals()
Let's modify the original function definition to execute operation num1, num2, and operation, which defaults to addition. Afterwards, use the locals function in Python to print the output.
globals()
Running the code would result in so many items, some of which are Python's pre-built variables that will come in handy when working with classes and packages. However, Jupyter Notebooks also employ various variables to manage its data. 
Global and Local Scope
The plan is to create two functions: function one with variables A and B, and function two with variables C and B. Both functions will print out their local variables. We will call function one with arguments 1 and 2, and function two with arguments 3 and 4.
Variables and functions both have names and data associated with them. However, for functions, this data includes information about required parameters and the lines of instruction to be executed. In Python, a function is represented as an object.
Viewing Function Data With  __code__
The "code" attribute of Python function objects can be used to confirm that functions are just variables in Python. Print the variable names and the byte object of all the lines of instruction in a function using this attribute. However, this is not something you would typically need to use. 
Text Processing in Python
Here are familiar text and function names to illustrate a point. There are two text processing operations, and a function that can make the text lowercase, remove punctuation, new lines, and words that are three characters or less.
Lambda Functions
These are a way to represent a function without giving it a variable name. Just like how an expression like 5 or 2 + 3 can be written without assigning it to a variable, a small function can be defined using the lambda keyword.
Instance Attributes
The topic of classes can be overwhelming and hard to understand. We may not be sure what they are or how to determine which class a member belongs to. Despite this confusion, look at an example of a class created previously: the dog class.
Static Attributes
For now, change the way legs attribute are handled in the class. Instead of keeping it in the constructor, define it as a static variable outside of the constructor. This means that each instance of the class will have the same value for legs.
Instance and Static Methods
The clean text method is a static method because it does not belong to any particular class instance, whereas add text is an instance method that belongs to a particular instance of the class. Static variables like replace puncs can also be added to control which punctuations get replaced. Use either the class name or the class instance to refer to static variables, but cannot be done with instance methods.
Class Inheritance
In the world of computer science and Python programming, it is possible for one class to inherit all the methods and attributes of another class. The original class is referred to as the parent class, while the new class that extends it is known as the child class.
Extending Built-in Classes
We can also apply class extensions in Python's built-in classes. In Python, creating a new list can be done by instantiating it as "list". Although it appears as a function, "list" is actually a class. 
Handling Errors and Exceptions
In any case, they all function in a similar manner. Here is a controversial opinion: errors and exceptions are basically the same thing. All Python errors and exceptions ultimately stem from a class called the base exception. For instance, the division by zero error is a type of arithmetic error, which is a type of exception, which in turn extends the base exception class.
Try/Except 
This is a zero division error. We have caught this exception and it will not be raised anymore. It is simply a class, it has attributes, you can create them, and they can even be returned. 
Managing and Handling Exceptions
Exceptions are not to be feared but they do need to be reigned in. We saw a little bit about how to do this previously with the Try / Except statement.
Finally
Finally statements can be useful because they will always execute no matter what happens inside this try block. You do not even need any except statements! This error is thrown, but still printed out. Even if no exception is raised at all, that still executes. Often this is used when timing how long a function takes to execute.
Catching Exceptions by Type
Notice that you are always catching this exception class. You could add another except statement above this and chain these together just fine. 
We are going to catch the zero division specifically. There was a zero division error, and now that prints out. A type error statement can also be added, except type error and printed. But of course, there was a zero division error, not a type error. 
Reading Files
Watching output being printed to the screen is all well and great, but often as programmers, we are asked to produce something real, something tangible, usually for those management types that want to see a physical file they can attach to email or open in Excel or whatever it is they do with files.
Writing Files
We're going to open this file in the read mode and if we print f at this point, we get a file object. And there are a couple of ways to get the actual text inside the file. And the first is readline, so f.readline. 
Appending Files
Let's look at writing files. We are going to do something similar to this but instead of an R, use a W for write. We are also going to call this output.txt, which does not exist yet, but when we run this, it will create the file for us which is a pretty nice feature. 
