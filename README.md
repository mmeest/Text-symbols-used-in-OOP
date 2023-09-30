# Text-symbols-used-in-OOP
Different text symbols used in object oriented programming.

## Contents
- [Punctuation and Delimiters](#punctuation-and-delimiters)
- [Operators](#Operators)

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
