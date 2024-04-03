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
CSV
There is a CSV file that we are going to be working with and this is 10_02_us.csv. This is derived from a dataset from geonames.org which provides millions of place names in geographical data sets spanning the globe. You can also see that the first row that gets printed out here is the header. And if you want to skip the header, the CSV reader also has a neat function you can use called next. So all we have to do is call next reader, and then that header gets skipped over.
Filtering Data
Now you are in the market for prime real estate and interested in finding postal codes that are only divisible by one in themselves. You know, prime. Now borrow the code that we wrote previously that gets all the prime numbers between 2 and 99,999. 
JSON
Loading JSON
Previously, we focused on reading and writing files to and from the disk. JSON files with the .json extension are common, and you might regularly be working with them.Let's make a JSON string, a is apple, b is bear, c is cat. Something to keep in mind, JSON is not Python. This JSON-formatted string looks a lot like a Python dictionary, but it's not. Notice that this is called loads plural and not load singular. Another common mistake. Now we have a Python dictionary. You can copy this Python dictionary and add a trailing comma, and that is just fine, but if you add a trailing comma to this JSON string, we get a JSON decode error. It is very common if you are working with JSON from a potentially untrustworthy source to surround this json.loads with a try except JSONDecodeError:print Could not parse JSON. And because this JSONDecodeError comes from the JSON module, we need to specifically import it as well.
Dumping JSON
Notice that this is dumps plural. You usually would not add any exception handling in this case because if you have a valid Python dictionary, there is not a lot that could go wrong when you are formatting it as a JSON string. However, there is one exception to this rule where an exception could be thrown.
Custom JSON Decoders
To demonstrate that, let's create an animal class real quick, class Animal init self, name, self.name equals name, and modify the dictionary to use this Animal class.Obviously, an apple is not an animal, so replace this with an aardvark and just put that in there. Animal bear and Animal cat. Now let's dump this dictionary. We get a TypeError, Object of type Animal is not JSON serializable. 
Week summary
Now that you have a strong foundation in Python, your next steps will depend on the skills you want to acquire. If you want to improve your Python skills, choose a project that interests you and attempt to build it. Take it as a learning experience and see what you can achieve. To showcase your work and track your progress, consider hosting your project on GitHub.
Remember, the key to mastering Python is practice and hands-on experience. So, choose your path and keep exploring the exciting possibilities that Python has to offer.

# Python week 3 
Finding Inspiration
When you embark on a new programming endeavor for enjoyment or practice, the initial puzzle to solve is: What should the program accomplish? It may seem like a simple question, but its open-ended nature can sometimes present a challenge. 
User Stories
Having the general idea for the next Python project - a daily email digest generator - I can now begin the planning process to determine specific details. Starting with user stories, which depict small scenarios from a user's perspective, these stories should emphasize the user's goal and motivation rather than the application itself.Remember, when writing user stories, focus on the user's goals and reasons, rather than specific interface details or implementation methods. Take a moment to write your own set of user stories for your Python project before proceeding with this course. 
Use Cases
Apart from user stories, another useful planning tool for applications is called a use case. Use cases typically include a title, an actor (a user or system), and a scenario that describes how a goal is achieved.While user stories and use cases may seem similar, they capture different information. User stories focus on the who, what, and why of a task or goal, while use cases cover the who, what, and how of achieving that goal. They complement each other rather than compete. 
Project Requirements
Besides user stories and use cases, it's helpful to write traditional requirements to formally capture the capabilities and limitations of an application.These requirements are kept at a high level, omitting specific details such as the forecast duration or temperature unit. For personal projects, this level of detail suffices, and elaboration can be left for implementation. Additional functional requirements related to the admin include configuring content sources, adding and removing recipients, scheduling the email digest, and setting email account credentials.
Architecture
Now that the requirements are captured, it's time to organize and structure the code for the application. With Python being an object-oriented programming language, considering objects and classes is essential. Looking at the requirements, use cases, and user stories, identifying nouns helps determine potential objects. For instance, in the functional requirements, words like quote, forecast, location, trends, article, content, email, and recipients stand out as potential objects.
Stub Code
It's time to start coding, and to provide a structure for the design, stub code has been created for the entire program using three Python modules: dd_content.py, dd_email.py, and dd_gui.py. The dd_email.py module contains the skeleton for the daily digest email class, with placeholder methods using the pass statement.Moving on to the dd_content module, a similar if name equals main section is included for test code. Unlike the daily digest email module, the dd_content module does not define a daily digest content class. 
Daily Inspirational Quotes
Now that a plan is in place and the program structure is outlined, it is time to implement the code. In the upcoming section, four functions will be implemented in the "dd_content.py" module.To implement the "get_random_quote" function, the source of random quotes needs to be determined. While web scraping libraries like Beautiful Soup or Scrapy could be used, after exploring options, a decision is made to curate a personal list of inspirational quotes. Storing the quotes and their authors can be done using different file formats like CSV, JSON, or XML. In this case, the CSV format is chosen for simplicity, with each line containing the author and quote separated by a vertical pipe symbol.
Weather Forecasting with OpenWeatherMap
Now that you have finished implementing the get_random_quote function, let's use the editor's code folding feature to hide that code. Next, we will work on implementing the next content function, get_weather_forecast, which is defined at line 19. Since the weather forecast data needs to be current, we can't store it in a local CSV file like we did for the quotes.OpenWeatherMap offers various callable APIs for accessing current and forecast weather information. To use the service, you must register with OpenWeatherMap and obtain an API key.When accessing the forecast API, the default format for the returned data is JSON. An example of this JSON response can be found in the documentation. However, since the JSON contains more weather information than necessary for the email, only use a select few fields that are relevant. OpenWeatherMap offers various callable APIs for accessing current and forecast weather information. To use the service, you must register with OpenWeatherMap and obtain an API key. The good news is that they offer a free access tier that is more than sufficient for this project. To obtain an API key for your own projects, simply click on the provided link and follow the registration process.
Trending Social Media Content (Twitter)
During the development of the DD content module, a way was needed to fetch current Twitter trends. Luckily, Twitter offers an API for developers to access this information. To use the API, I had to register a Twitter account, request API access, and obtain an API key. Although there were over 3,000 Python projects related to Twitter listed on PyPI, going through all of them and their documentation would have been time-consuming and inefficient. Instead, change the approach and turn to Google. Searching for "Python Twitter trends" led to various blog posts and tutorials where people had already solved similar problems.
Importing Articles
To implement the fourth content retrieval function, it was necessary to fetch a random Wikipedia article. The availability of a Wikipedia API was checked to fulfill this requirement. A search on Google for Wikipedia API documentation led to finding the desired information. Conveniently, Wikipedia offers a REST API that allows access to their content.After expanding the page content section and scrolling towards the bottom, there is a description that seems to provide content for a random page. This is exactly what is required.The updated get Wikipedia article function utilizes the request module's URL open function at line 65 to access the URL for a random page summary. Subsequently, the response is passed to the JSON module's load function for parsing. Only specific information from the response is necessary, namely the page title, summary extract, and URL.
Writing and Formatting Email Messages
Now that the application can retrieve different types of content, let's shift our focus to the email section, which will be implemented in the DD email Python module. You can find the stubbed methods for the Daily Digest email class here. If you want some extra programming practice, you can pause the course and try implementing these methods before checking out the approach.Before we can send an email, we need something to send, so the next method we'll tackle is the format message. Initially, when planning the class requirements, there was a method called format message that was meant to format various content into the email's message body. However, during implementation, it became clear that the specifics of email message formatting were a bit uncertain. To find a solution, a search was conducted on how to format an email message with Python.
Sending an Email
to send it as an email. Luckily, Python has a convenient library called 'email' in its standard package, which helps manage email messages. This package has various modules, but for this project, focus on the 'email.message' module to handle the email message itself.The core of this module revolves around a class known as "Email Message." It is the main tool used to put together different components of the daily digest email, like the subject line, recipient list, and, of course, the message content. Moving up a level to the email package, as the documentation explains, this package can assist in handling email messages, but it isn't meant for actually sending them.
Task Scheduling
Looking back at the original outline for a daily digest email class created earlier in this course, we have made progress. The format message and send email methods have been successfully implemented. In the process, we added a recipient email address list and a few unexpected instance variables that were not initially part of the plan. That leaves us with one final task: implementing the ability to send the daily digest at a specific time every day.
GUI Design Planning
Having completed the implementation of the four content generation functions, an email class for formatting and sending the daily digest, and a scheduler, most of my functional requirements are now checked off. These three modules are the core components of my application. However, I also included a non-functional requirement, which is to create a graphical user interface (GUI) for the admin's use. So, let's focus on that now. In this lesson, we will cover how to create a graphical user interface (GUI) using Python's Tkinter module. Now, to be honest, this lesson will not dive deep into fancy UX design principles, but it will get the job done! 
Exploring Python Tkinter GUI
Now that the plan for the GUI has been introduced, let's delve into the code that was written to implement it. The GUI module, called "dd GUI," consists of 250 lines.In addition to importing Python's TKinter module, the daily digest email and scheduler modules are also imported since the GUI interacts with instances of both.Instead of instantiating variables within their respective builders, all variables are instantiated within the initialization method to easily initialize their values in one place. This structure allows for easy modification of field initialization without searching through the variable builder methods. 
Iterative Enhancements
Save Configuration Settings: Modify your program to store configuration settings in a file or a database. When the program starts, it can read the settings from the storage and apply them, ensuring that the changes made by the admin are retained across program restarts.
Customizable Content for Recipients: Allow recipients to individually customize the content they want to receive in their digest. This could involve creating a settings section for recipients, where they can select their preferred content categories or topics.
Personalized Weather Forecast: Enhance the weather forecast by customizing it for each recipient's location. You can include an additional field in the recipient's information to store their location, and then use an appropriate weather API to fetch location-specific forecasts.
Timezone-based Email Sending: Adjust the sending time of the email digest based on each recipient's timezone. This way, all recipients receive the digest at a time that's relative to their day.
Notifying Admin of Unavailable Content Sources: Implement a mechanism to notify the admin when a content source becomes unavailable or encounters an issue. This could involve periodically checking the availability of content sources and sending notifications or generating error logs when issues arise.
Persistent Application as a Scheduled Service: Modify your application to run as a scheduled service rather than requiring the Python interpreter to be left running continuously. You can use operating system-specific mechanisms (e.g., cron jobs on Unix-like systems) to schedule the program's execution at the desired time.
Secure Storage of Sensitive Information: Improve the security of your application by finding a more secure way to store sensitive information like sender credentials and API keys. Consider using encryption or storing the credentials in a separate configuration file with restricted access.
GUI Improvements:  Enhance the visual appeal and usability of your GUI. This could involve refining the layout, adding icons, using color schemes, or incorporating user-friendly features like tooltips or keyboard shortcuts.
Preserving Configuration Settings
Let’s look at a new feature to the program. It is about saving and restoring configuration settings when I exit and restart the application.To save the information between program runs, se JSON as the file format. The JSON module was imported at the beginning. Moving down, two new methods were added to the GUI class: a save config method at line 259 and a load config method at line 276.To integrate these methods into the program's flow, make two calls. First, add a try-except block in the shutdown method (lines 250-253) to save the current configuration when closing the program. Second, in the classes and init method, where initial values for GUI variables are set, add a try clause at line 68 to load the configuration from the JSON file. If loading fails, the application will use the default settings.
Distributing Python Projects
Adding new features to your Python project can go on forever, as long as you are having fun and still learning.For example, let's say your mom wants to send out her own daily email digest to friends and family. After tweaking the app to suit her needs, package it in a way that she can use. Since most moms think Python is just a snake, you cannot hand her a bunch of .py files.Once PyInstaller is installed, navigate to your project directory in the terminal. You can turn your app into an executable using the command "pyinstaller -w -F" followed by the top-level Python script (in this case, "dd_gui.py").Keep in mind that PyInstaller offers many more features and capabilities than what we covered here. If you are interested in distributing your Python apps as executables, I recommend checking out the PyInstaller documentation for further details.

Module Summary
Great job, you have made it to the end of this course! Throughout this journey, the process of creating Python projects was shared, and we hope it has sparked your creativity and motivation to start or keep working on your own Python creations.

Remember, there is always more to learn from various other Python courses. You will find a handy list of those courses in the exercise files, so you can refer to them whenever you want to continue expanding your knowledge. There is no pressure to complete all of these though! Simply pick the topics that pique your interest the most

#Python Week 4 
Professionals, including established ones, have many reasons to pursue Python Institute certification. The IT industry is always changing, and what's important today may not be tomorrow. Since Python is a dynamic language, it is crucial to stay updated on the latest advancements. The PCAP™ and PCPP1™ certifications not only show that you are up to date, but also demonstrate your ability to handle Python challenges proficiently. By getting certified, you keep your skills current and let others know you're up to speed. Additionally, the Python Institute offers access to a vast network of Python professionals who can help you solve programming problems and come up with innovative solutions. For employees, certifications like PCAT™ and PCAD™ prove expertise in specific fields and signal dedication to their work, which employers recognize. Certified employees are more likely to be promoted and given interesting projects and prestigious roles. Certifications also play a crucial role in the hiring process as they act as a tool for selection and screening. IT executives and managers highly value certification portfolios, which can give your resume an advantage and increase your chances of landing desired job opportunities. According to the 2021 Value of IT Certification Report, 66% of hiring managers consider candidates with IT certifications more suitable for interviews. Certificates strengthen your position in the job market by providing evidence of your skills and programming knowledge, ultimately leading to more interview invitations.
