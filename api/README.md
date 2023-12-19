# API Learning!


# General Questions:



## What Bash scripting should not be used for?
Bash scripting is a powerful tool for automating tasks in Unix-like operating systems. However, there are several scenarios where it
may not be the best choice:

1. **Complex Applications**: Bash is not suitable for building complex applications. It lacks many features that are standard in other
programming languages, such as data types and object-oriented programming.

2. **Heavy Computational Tasks**: Bash is not designed for heavy computational tasks. It's not efficient for mathematical operations
compared to languages like Python or C.

3. **Cross-Platform Compatibility**: Bash scripts are not ideal for tasks that need to be cross-platform compatible. They work best in
Unix-like environments and may not work correctly, if at all, on other systems like Windows.

4. **Large Data Processing**: Bash is not efficient for processing large amounts of data. It reads files line by line, which can be
very slow for large files.

5. **Web Development**: Bash is not suitable for web development tasks like handling HTTP requests, rendering HTML, or interacting with
databases.

Remember, while Bash scripting is powerful and flexible for certain tasks, it's important to choose the right tool for the job.




## What is an API?
An API, or Application Programming Interface, is a set of rules and protocols for building and interacting with software applications.
It defines the methods and data formats that a program can use to communicate with other software or components. APIs can be used to
enable interaction between different software systems, allowing them to share data and functionalities. They are used in a wide variety
of programming contexts, from web development to operating systems.




## What is a REST API?
A REST API (Representational State Transfer API) is an architectural style for an application program interface (API) that uses HTTP
requests to access and use data. It is stateless, meaning that each HTTP request happens independently and should contain all the
information necessary to perform the request.

REST APIs are designed to take advantage of existing protocols, and often use HTTP methods explicitly (like GET, POST, PUT, DELETE) to
perform operations. They can return data in different formats, but JSON (JavaScript Object Notation) is the most common.




## What are microservices?
Microservices, in terms of APIs, refer to a specific architectural style of building applications. Instead of building a single,
monolithic application, the application is broken down into smaller, independent services. Each of these services corresponds to a
specific business functionality and can be developed, deployed, and scaled independently.

Each microservice typically has its own API, which defines the interface for interacting with that service. These APIs allow the
microservices to communicate with each other, typically over HTTP/HTTPS using methods like GET, POST, PUT, DELETE, etc. The data
exchanged is often in the form of JSON or XML.




## What is the CSV format?
The CSV (Comma-Separated Values) format is a simple file format used to store tabular data, such as a spreadsheet or database. Each
line of the file is a data record and each record consists of one or more fields, separated by commas.

The CSV format is very simple and does not have a standard schema, meaning it does not require a specific structure of the data.
However, the typical interpretation is that the first line of the file represents the column headers, and the subsequent lines are the
data records.




## What is JSON format?
The JSON (JavaScript Object Notation) format is a lightweight data-interchange format that is easy for humans to read and write and
easy for machines to parse and generate. It is based on a subset of the JavaScript Programming Language, Standard ECMA-262 3rd Edition
- December 1999.

JSON is a text format that is completely language independent but uses conventions that are familiar to programmers of the C-family of
languages, including C, C++, C#, Java, JavaScript, Perl, Python, and many others. These properties make JSON an ideal data-interchange
language.




## What is a Pythonic Package and module name style?
Python packages and modules should have short, all-lowercase names, and they can include underscores if it improves readability. This
is according to PEP 8, the official Python style guide.





## What is Pythonic Class name style, Variable name style, Function name style, and Constant name style?
According to PEP 8, the official Python style guide:

1. **Class Names**: Class names should normally use the CapWords (or CamelCase) convention. For example, `MyClass`.

2. **Variable Names**: Variable names should be lowercase, with words separated by underscores as necessary to improve readability. For
example, `my_variable`.

3. **Function Names**: Function names should be lowercase, with words separated by underscores as necessary to improve readability. For
example, `my_function()`.

4. **Constant Names**: Constants are usually defined on a module level and written in all capital letters with underscores separating
words. For example, `MY_CONSTANT`.




## Significance of CapWords or CamelCase in Python?
In Python, the CapWords or CamelCase convention is significant because it is used to name classes. This is a convention outlined in PEP
8, the official Python style guide.

Using CamelCase for class names helps to differentiate them from functions and variables, which are typically named using lowercase
letters and underscores. This makes the code easier to read and understand, as you can quickly identify classes at a glance.


