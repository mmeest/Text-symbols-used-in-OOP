# Text-symbols-used-in-OOP
Different text symbols used in object oriented programming.

## Contents
- [Punctuation and Delimiters](#punctuation-and-delimiters)
- [Operators](#Operators)
- [String literals](#string-literals)

## Punctuation and Delimiters

<h1><p align="center";>: - Colon</p></h1>
The colon (:) is a punctuation symbol used in programming for several different purposes, 
depending on the context and the programming language. Here are some of the main uses of the colon in programming:
Variable Declaration and Type Annotation: In statically-typed programming languages, 
such as Python with type hints, the colon is used to annotate variables with their data types. 
This helps improve code readability and can provide type checking benefits. For example:
In Python (with type hints):

```
age: int = 25
name: str = "Alice"
```
Dictionary (Map) Literal Initialization: In some programming languages like Python and JavaScript, 
colons are used to define key-value pairs within dictionaries (Python) or objects (JavaScript). 
This notation is used when creating or initializing data structures. For example:
In Python:

```
person = {"name": "Alice", "age": 30}
```
Case Labels (Switch Statements): In languages like C, C++, and Python (with libraries like matchlib), 
the colon is used to separate case labels in a switch statement. Case labels indicate 
the code block to execute when a particular value matches a given case. For example:
In C:

```
switch (day) {
    case 1:
        printf("Sunday");
        break;
    case 2:
        printf("Monday");
        break;
    // ...
}
```

Labeling Statements: In languages like Python and JavaScript, colons can be used 
to label certain statements or code blocks. This is often used with loops or control flow constructs.
    In Python:
```
for i in range(5):
    if i == 2:
        print("Found it!")
        break
```
Slice Notation: In Python and some other languages, colons are used to define 
slice notation when working with sequences like strings, lists, and arrays. 
The slice notation allows you to extract a portion of the sequence. 
    In Python:
```
my_string = "Hello, World!"
substring = my_string[0:5]  # Extracting the substring "Hello"
```    

<h1><p align="center";>; - Semicolon</p></h1>
Semicolon is a punctuation symbol commonly used in many programming languages. 
Its primary purpose is to terminate statements or separate multiple statements 
on a single line. Here's a breakdown of its usage in programming:

```
int x = 5; // Semicolon terminates the variable assignment statement
printf("Hello, world!"); // Semicolon terminates the print statement
int a = 10; int b = 20; int sum = a + b; // Multiple statements on one line
```
In JavaScript: JavaScript uses semicolons to terminate statements as well. However, 
JavaScript also has automatic semicolon insertion (ASI) rules, which means that in some cases, 
you can omit semicolons, and the JavaScript engine will insert them automatically. 
Despite this, it's considered a good practice to include semicolons explicitly 
to avoid potential issues with ASI. For example:
```
let x = 5; // Semicolon can be included (recommended)
let y = 10  // Semicolon omitted (but automatically inserted by ASI)
```
Python does not use semicolons to terminate statements. Instead, 
Python relies on indentation to determine the structure of the code. 
Statements are separated by newlines and the level of indentation.

In some programming languages, semicolons can be used as separators 
in certain collection or data structure literals, primarily for initializing 
arrays, sets, or dictionaries. 

Arrays (JavaScript and ASI Languages): In JavaScript, you can use semicolons 
as separators when initializing an array. While you typically use commas 
to separate array elements, JavaScript's Automatic Semicolon Insertion (ASI) 
allows semicolons to be used as separators as well. For example:
```
const myArray = [1; 2; 3]; // Semicolons used as separators (ASIs insert commas)
```
However, using semicolons in this way is not common practice, and commas are preferred for separating array elements.

Tuples (Python): In Python, semicolons can be used to separate elements in a tuple, although this usage is not very common:
```
my_tuple = (1; 2; 3)
```
In practice, Python developers usually use commas to define tuples:
```
my_tuple = (1, 2, 3)
```

<h1><p align="center";>' - Single quote</p></h1>
In many programming languages, single quotes are used to define character literals. 
A character literal represents a single character and is enclosed within single quotes.
In C and C++:

```
char myChar = 'A';
```
In Python:
```
my_char = 'B'
```
In Java:
```
char myChar = 'X';
```
Some programming languages use single quotes to define string literals, 
although it's less common than using double quotes ("). For example, 
in SQL (Structured Query Language), single quotes are used to denote string literals:
```
SELECT * FROM employees WHERE last_name = 'Smith';
```

<h1><p align="center";>" - Double quote</p></h1>
Double quotes (") are widely used in programming languages for a variety of purposes, 
primarily related to representing strings and text.
A string literal is a sequence of characters enclosed within double quotes. For example:
    In Python:
    
```
my_string = "Hello, World!"
```

Escaping: Single quotes are often used when you need to include 
double quotes within a string without terminating the string prematurely. For example:
    In Python:   
    
```
my_string = 'He said, "Hello!"'
```

<h1><p align="center";>( and ) - Parentheses</p></h1>

Parentheses in programming are used for a variety of purposes, and their primary role 
is to control the order of operations, group expressions, and pass arguments to functions.
Here are some common uses of parentheses in programming:
Function Calls: One of the most common uses of parentheses is to call functions or methods. 
When you call a function, you enclose the arguments (if any) within parentheses.
In Python:
```
result = my_function(arg1, arg2)
```
Grouping: Parentheses are used to group elements in expressions to clarify 
the intended order of evaluation. 
In conditional statements (if statements):
```
if (x > 5) {
    // Code to execute when x is greater than 5
}
```
In regular expressions (for grouping patterns):
```
import re
match = re.search("(a|b)+", "abbaab")
```
Tuples and Lists: In Python, parentheses are used to create tuples, 
while square brackets are used to create lists. For example:
```
my_tuple = (1, 2, 3)
my_list = [4, 5, 6]
```
Method Calls on Objects: In object-oriented programming, 
parentheses are used to call methods on objects. For instance, in Java:
```
String myString = "Hello, World!";
int length = myString.length(); // Calling the length() method on the string
```

<h1><p align="center";>{ and } - Curly braces</p></h1>

Code Blocks: Curly braces are most commonly used to enclose a block of code. 
A code block is a group of statements that are treated as a single unit. 
This is used in various control structures such as loops, conditional statements, 
and function definitions. For example:
    In C++ and C#:
```
for (int i = 0; i < 5; i++) {
    // Code inside the loop block
    cout << i << endl;
}
```

Dictionaries (Associative Arrays): In languages like Python and JavaScript, 
curly braces are commonly used to define dictionaries (Python) or objects (JavaScript), 
which are collections of key-value pairs. For example:
    In Python:
```
my_dict = {"key1": "value1", "key2": "value2"}
```
    In JavaScript:
```
const myObj = {"key1": "value1", "key2": "value2"};
```
Sets: In some programming languages like Python and JavaScript,
curly braces can be used to define sets, which are collections of unique elements. For example:
    In Python:
```
my_set = {1, 2, 3, 4}
```
    In JavaScript (using ES6 Set):
```
const mySet = new Set([1, 2, 3, 4]);
```
JSON (JavaScript Object Notation): JSON data is often defined using curly braces 
to create objects and nested structures. JSON is used for data interchange 
between systems and is a widely accepted data format in web development.
```
{
    "name": "John",
    "age": 30,
    "address": {
        "street": "123 Main St",
        "city": "Anytown"
    }
}
```

<h1><p align="center";>[ and ] - Square braces</p></h1>
Square brackets ([]) in programming are used primarily for defining and working 
with arrays, lists, and similar data structures. Here's how square brackets are commonly used in programming:
Array and List Initialization: Square brackets are used to define and initialize arrays or lists. 
Arrays are collections of elements, each identified by an index or position. 
Lists, which are similar, may have additional features such as dynamic sizing. For example:
In Python (List):

```
my_list = [1, 2, 3, 4]
```
Accessing Elements: Square brackets are used to access elements in an array or list by their index. 
Indexing typically starts at 0 in most programming languages. For example:
    In C++:
```
int myArray[3] = {10, 20, 30};
int value = myArray[1]; // Accessing the second element (20)
```
Indexing and Iteration: Square brackets are used to iterate through elements 
in an array or list using loops or other iteration mechanisms. For example:
    In C#:
```
int[] numbers = {1, 2, 3, 4};
foreach (int num in numbers) {
    // Access each element using square brackets
    Console.WriteLine(num);
}
```

<h1><p align="center";>, - Comma</p></h1>

In programming, the comma (,) is a punctuation symbol with several different uses, 
depending on the context and programming language. Here are the main ways in which commas are used in programming:
Separator in Lists and Arrays: Commas are commonly used to separate elements 
in lists, arrays, and tuples. These elements can be variables, literals, or expressions. For example:
    In Python (list):
```
my_list = [1, 2, 3, 4]
```
Function Arguments: Commas are used to separate arguments when calling functions or methods. 
Each argument corresponds to a parameter defined in the function's declaration or definition. For example:
    In Python:
```
result = my_function(arg1, arg2, arg3)
```
Variable Declarations: Commas can be used to declare multiple variables in a single statement.
This is particularly useful when declaring variables of the same type. For example:
    In JavaScript (with var, let, or const):
```
let a, b, c;
let x = 5, y = 10; // Combining variable declarations
```
Function Definitions: In some languages like C and C++, commas are 
used to define multiple parameters in function declarations. For example:
```
int add(int a, int b) {
    return a + b;
}
```

<h1><p align="center";>. - Dot</p></h1>
In programming, the dot (.) is a commonly used punctuation symbol that serves various purposes, 
depending on the context and programming language. Here are some of the primary uses of the dot in programming:
Member Access Operator: The dot is frequently used as the member access operator 
to access members (variables or methods) of objects or structures. 
It allows you to navigate the hierarchy of properties and methods within an object or data structure. 
In Python:
    
```
person = {"name": "Alice", "age": 30}
name = person["name"]  # Accessing the "name" property using square brackets
age = person.age      # Accessing the "age" property using the dot operator
```
Method Invocation: When you have an object with associated methods, 
the dot operator is used to call those methods. For example:
    In Java:
```
String greeting = "Hello, World!";
int length = greeting.length();  // Calling the `length` method using the dot operator
```
Object Property Assignment: In JavaScript, you can use the dot operator 
to add or modify properties of objects. For example:
```
const person = {};
person.name = "David";  // Adding the "name" property using the dot operator
person.age = 28;        // Adding the "age" property using the dot operator
```

## Operators

    |: Pipe is used as a bitwise OR or logical OR operator in some languages.
    +: Plus sign is used for addition.
    ++ and --: Increment and decrement operators.
    ==, <=, >=: Comparison operators for equality, less than or equal to, and greater than or equal to, respectively.
    !: Logical NOT operator.
    !=: Not equal operator.

<h1><p align="center";>+ and ++ - hyphen or minus</p></h1>    

In programming, the plus sign (+) and the double plus sign (++) are two distinct operators with different purposes. 
    Plus Sign (+):
        Addition Operator: The plus sign (+) is primarily used as an addition operator in most programming languages. It performs arithmetic addition, adding two or more numeric values together. For example:
            In Python:    
```
result = 5 + 3  # result is 8
```

String Concatenation: In some programming languages, such as JavaScript, the plus sign can also be used for string concatenation, which involves combining two or more strings together. For example:
```
let greeting = "Hello, ";
let name = "Alice";
let message = greeting + name;  // message is "Hello, Alice"
```
Double Plus Sign (++) - Increment Operator:
    The double plus sign (++) is used as an increment operator. It is used to increase the value of a variable by 1. The increment operation can be applied to numeric variables, including integers and floating-point numbers. For example:
        In C++:
```
int x = 5;
x++;  // Increment x by 1, x is now 6
```

The ++ operator can be used in both prefix and postfix forms, depending on whether you want to increment the variable before or after its current value is used in an expression:
    Prefix Increment (++x or ++variable) increments the variable and then returns its updated value.
    Postfix Increment (x++ or variable++) returns the current value of the variable and then increments it.
For example, in C++:     
```
int x = 5;
int y = ++x;  // Prefix increment: x is incremented to 6, y is assigned 6
int z = x++;  // Postfix increment: z is assigned 6, then x is incremented to 7
```
The plus sign (+) is a basic arithmetic operator used for addition and string concatenation, while the double plus sign (++) is specifically used for incrementing numeric variables. The behavior and availability of these operators may vary slightly between programming languages, so it's important to refer to the documentation of the language you are working with for precise details.

<h1><p align="center";>- and -- - hyphen or minus</p></h1>
The hyphen or minus sign (-) is a common symbol in programming languages with several important uses. Here are some of the primary ways the minus sign is used in programming:
    Subtraction: The most fundamental use of the minus sign is for arithmetic subtraction. It is used to subtract one numeric value from another. For example:
        In Python:
        
```
result = 10 - 5  # result is 5
```

Decrement: In C-like languages (e.g., C, C++, C#), the minus sign is used as the decrement operator (--). It decreases the value of a variable by one. For example:
```
int x = 10;
x--;  // x is now 9
```
Subtraction Assignment: In many programming languages, the minus sign can be used in combination with the assignment operator (=) to subtract a value from a variable and assign the result back to the variable. For example:
    In Python:
```
x = 10
x -= 3  # x is now 7
```
String Concatenation (in some languages): In some scripting languages like JavaScript, the minus sign can be used for string concatenation if one or both operands are strings. However, the plus sign (+) is more commonly used for string concatenation.
    In JavaScript:
```
let result = "Hello, " - "World!";  // result is NaN (Not-a-Number)
```

<h1><p align="center";>* and ** - asterisk and double asterisk</p></h1>
The asterisk (*) and double asterisk (**) symbols have different meanings and usages in programming, depending on the context and programming language. Here's an overview of their common uses:

Asterisk (*) symbol:
    Multiplication Operator: The asterisk (*) is primarily used as the multiplication operator in most programming languages. It is used to perform arithmetic multiplication between two or more numeric values. For example:
        In Python:
```
result = 5 * 3  # result is 15
```
Pointer Declaration and Dereferencing: In languages like C and C++, the asterisk is used to declare and dereference pointers. It allows you to work with memory addresses and manipulate data indirectly through pointers. For example:
    Pointer Declaration:
```
int* ptr;  // Declare a pointer to an integer
```    
Pointer Dereferencing:
```
int value = 10;
int* ptr = &value;  // Assign the address of 'value' to 'ptr'
int result = *ptr;  // Dereference 'ptr' to get the value, result is 10
```
String Repetition: In some programming languages, such as Python, the asterisk can be used for string repetition. It allows you to repeat a string multiple times. For example:
    In Python:
```
repeated_string = "abc" * 3  # repeated_string is "abcabcabc"
```
Double Asterisk () symbol:**
    Exponentiation Operator: The double asterisk (**) is used as an exponentiation operator in some programming languages. It raises a base number to the power of an exponent. For example:
        In Python:
```
result = 2 ** 3  # result is 8 (2 raised to the power of 3)
```
Keyword Arguments (Python): In Python, the double asterisk (**) is used in function definitions to capture keyword arguments in the form of a dictionary. This allows functions to accept a variable number of named arguments. For example:
```
def print_info(**kwargs):
    for key, value in kwargs.items():
        print(f"{key}: {value}")

print_info(name="Alice", age=30, city="Anytown")
```
   In this example, **kwargs captures the keyword arguments as a dictionary.
The specific usage and behavior of the asterisk (*) and double asterisk (**) symbols may vary from one programming language to another, so it's essential to consult the documentation of the programming language you are working with to understand their precise meanings and usages in that language.

<h1><p align="center";>/ and // - forward slash and double forward slash</p></h1>

In programming, the forward slash (/) and double forward slash (//) symbols have different meanings and usages, primarily related to division and comments, respectively. 
Forward Slash (/) symbol:
    Division Operator: The forward slash (/) is primarily used as the division operator in most programming languages. It is used to perform arithmetic division between two numeric values. For example:
        In Python:
```
result = 10 / 2  # result is 5.0 (floating-point division)
```
Path Separation (File Paths and URLs): In file systems and web development, the forward slash is commonly used as a path separator to separate directory or folder names in file paths and URLs. For example:
    In file paths (Windows):
```
C:\Users\Username\Documents\file.txt
```
In URLs:
```
https://www.example.com/page.html
```
Regular Expressions: In some programming languages, the forward slash may be used as a delimiter in regular expressions to indicate the beginning and end of a pattern. For example:
    In JavaScript:
```
const regex = /pattern/;
```
Double Forward Slash (//) symbol:
    Single-Line Comments: The double forward slash (//) is commonly used to denote single-line comments in many programming languages. Comments are used to provide explanatory notes within the code that are ignored by the compiler or interpreter. For example:
        In JavaScript:
```
// This is a single-line comment in JavaScript
```
Floor Division (//):
In Python, the double forward slash (//) is used as the floor division operator. Floor division divides two numbers and rounds down to the nearest integer, resulting in an integer quotient. This means that the fractional part of the division is discarded, and the result is always an integer or integer-like value.
Example:
```
result = 10 // 3  # result is 3
```
In this example, 10 // 3 performs floor division, resulting in 3 because the division of 10 by 3 equals 3.333..., which is rounded down to the nearest integer.
It's important to note that not all programming languages use // for floor division. The behavior of the division operator may vary between languages, so it's essential to consult the documentation of the specific programming language you are using to understand how division and floor division are handled.

URLs (Web Development): In web development, the double forward slash (//) is used to indicate a URL that is relative to the current protocol (HTTP or HTTPS). For example:
```
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
```
Preprocessor Directives (C/C++): In C and C++ programming, the double forward slash (//) is sometimes used as part of preprocessor directives, such as #define, to indicate that a line is a comment. For example:
```
#define MAX_VALUE 100 // This is a comment
```

<h1><p align="center";>% - percend or modulo</p></h1>
In programming, the percent symbol (%) is primarily used as the modulo operator, which calculates the remainder of a division operation between two numeric values. 
Modulo Operator (%):
    Modulo Operation: The percent symbol (%) is used to perform a modulo operation, which calculates the remainder when one number is divided by another. It returns the remainder as the result. For example:
        In Python:
        
```
result = 10 % 3  # result is 1 (10 divided by 3 has a remainder of 1)
```
Checking for Even or Odd: The modulo operator is often used to determine whether a number is even or odd. If a number modulo 2 equals 0, it's even; otherwise, it's odd.
    In Python:
```
is_even = 12 % 2 == 0  # is_even is True (12 is even)
is_odd = 7 % 2 == 1    # is_odd is True (7 is odd)
```
Wrapping Values: The modulo operator can be used to create cyclical or wrapping behavior for values within a certain range. For example, you can use modulo to cycle through a list of items or to wrap an angle measurement around a circle (e.g., degrees from 0 to 360).
    In Python (cycling through a list):
```
items = ["A", "B", "C", "D"]
index = 9 % len(items)  # index is 1 (cycling back to the beginning of the list)
```
Calendar Operations: The modulo operator is sometimes used in date and time calculations, especially when dealing with periodic events or repeating patterns.
    In Python (calculating the day of the week for a date):
```
day_of_week = (5 + 31) % 7  # day_of_week is 5 (0 is Sunday, 5 is Friday)
```

## String literals

<h1><p align="center";>f-strings</p></h1>

The letter "f" in programming languages is often associated with "f-strings," which are a feature found in some programming languages for creating formatted strings in a concise and readable manner. F-strings are a way to embed expressions inside string literals by prefixing the string with an "f" or "F." The expressions within the string are enclosed in curly braces {} and evaluated at runtime. Here's how f-strings work in a few programming languages:

Python (3.6 and later): In Python, f-strings allow you to embed expressions and variables directly into string literals. You create an f-string by prefixing a string with an "f" or "F," and you can include expressions inside curly braces {} within the string. For example:

```
name = "Alice"
age = 30
formatted_string = f"My name is {name} and I am {age} years old."
```
In this example, the values of name and age are interpolated into the string.

JavaScript (Template Literals): While not called f-strings, JavaScript has a similar feature called "template literals." You create a template literal by enclosing a string in backticks (`) instead of single or double quotes. You can then embed expressions within ${} placeholders. For example:
```
const name = "Bob";
const age = 25;
const formattedString = `My name is ${name} and I am ${age} years old.`;
```
Ruby (String Interpolation): Ruby allows for string interpolation using the #{} syntax within double-quoted strings. Although not exactly the same as f-strings, it achieves a similar result:
```
name = "Charlie"
age = 35
formatted_string = "My name is #{name} and I am #{age} years old."
```

F-strings, template literals, and string interpolation are powerful features that simplify the process of creating formatted strings in a way that makes code more readable and concise. These features are particularly useful when you need to combine text with variable values or expressions within strings. The "f" in f-strings generally stands for "formatted" or "formatted string," indicating that they are designed for creating strings with specific formatting needs.
