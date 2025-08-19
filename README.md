# Text-symbols-used-in-OOP
Different text symbols used in object oriented programming.

## Contents
- [Example Code](#example-code)
- [Punctuation and Delimiters](#punctuation-and-delimiters)
- [Arrow Function](#arrow-function)
- [Arithmetic Operators](#arithmetic-operators)
- [Comparsion Operators](#comparsion-operators)
- [Logical Operators](#logical-operators)
- [Iterating Variables](#iterating-variables)
- [Assignement Operators](#assignement-operators)
- [Bitwise Operators](#bitwise-operators)
- [String Literals](#string-literals)
- [Template Literals](#template-literals)
- [Separator](#separator)
- [Escape characters](#escape-characters)
- [Ternary Conditional](#ternary-conditional)
- [Comments](#comments)

## Example Code
Example of Python code that uses different symbols used in programming:
```
# Define a list with some numbers
numbers = [1, 2, 3, 4, 5]

# Iterate through the list using a for loop
for number in numbers:
    # Check if the number is even
    if number % 2 == 0:
        # If even, square the number and print it
        squared = number ** 2
        print(f"The square of {number} is {squared}.")
    else:
        # If odd, increment the number and print it
        incremented = number + 1
        print(f"The incremented value of {number} is {incremented}.")

# Define a dictionary with some key-value pairs
info = {
    'name': 'Alice',
    'age': 30,
    'city': 'Wonderland',
}

# Access and print values from the dictionary
print(f"{info['name']} lives in {info['city']}.")

# Define a function that takes two arguments and returns their sum
def add(x, y):
    return x + y

# Call the function with some values and print the result
result = add(10, 20)
print(f"The sum is: {result}")

# Define a class with a constructor and a method
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def introduce(self):
        print(f"My name is {self.name}, and I am {self.age} years old.")

# Create an instance of the Person class and call the method
alice = Person('Alice', 30)
alice.introduce()

# Use some logical operators
x = 5
y = 10
if x < y and y != 0:
    print("x is less than y, and y is not equal to 0.")

# Use a ternary conditional expression
result = "even" if x % 2 == 0 else "odd"
print(f"x is {result}.")

# Define a multiline string with triple quotes
multiline_string = """
This is a multiline string.
It can span multiple lines.
"""

# Use escape sequences for special characters
escaped_string = "This is an escaped newline: \nAnd a tab character: \t"

# Use string formatting with placeholders
name = "Bob"
age = 25
formatted_string = f"Hello, my name is {name}, and I am {age} years old."

# Define and use a variable with a global scope
global_var = 100

# Define and use a variable with a local scope
def local_variable_example():
    local_var = 50
    print(f"Local variable: {local_var}")

local_variable_example()

# Use a list comprehension to create a new list
original_list = [1, 2, 3, 4, 5]
squared_list = [x ** 2 for x in original_list]

# Use bitwise operators
bitwise_and = 3 & 5
bitwise_or = 3 | 5
bitwise_xor = 3 ^ 5
bitwise_not = ~3

# Print the results
print(f"Bitwise AND: {bitwise_and}")
print(f"Bitwise OR: {bitwise_or}")
print(f"Bitwise XOR: {bitwise_xor}")
print(f"Bitwise NOT: {bitwise_not}")

# Use a while loop
count = 0
while count < 5:
    print(f"Count: {count}")
    count += 1

# Use the "in" operator to check for membership in a list
fruits = ['apple', 'banana', 'cherry']
if 'banana' in fruits:
    print("Banana is in the list of fruits.")

# Use the "not in" operator
if 'pear' not in fruits:
    print("Pear is not in the list of fruits.")
```

## Punctuation and Delimiters

<h1><p align="center";>: and :: - Colon and double colon</p></h1>
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

 In CSS, the colon (:) is used to define and apply pseudo-elements and pseudo-classes. Pseudo-elements allow you to style parts of an element, such as the first line of text or the first letter of a paragraph, while pseudo-classes allow you to apply styles to elements based on their state or position, such as when a link is hovered over.
     Pseudo-classes:
        :hover is used to apply styles to an element when the mouse pointer is over it.
        :active is used to apply styles to an element when it is being clicked.
        :nth-child() is used to select elements based on their position within a parent element.

Example:
```
a:hover {
    color: red;
}

li:nth-child(odd) {
    background-color: lightgray;
}
```

CSS Pseudo-elements:
        ::before is used to insert content before the content of an element.
        ::after is used to insert content after the content of an element.
        ::first-line is used to style the first line of text within an element.
        ::first-letter is used to style the first letter of text within an element.

Example:
```
p::first-line {
    font-weight: bold;
}

a::after {
    content: " (link)";
}
```

In programming, the "::" symbol has different meanings and usages in various programming languages. Its usage can vary significantly depending on the context and the language in which it is used. Here are a few common uses of "::" in programming:

1. Scope Resolution Operator (C++):
        In C++, the "::" operator is known as the scope resolution operator. It is used to access members (such as variables and functions) of a class or namespace.
        For example, to access a static member variable x of a class MyClass, you would use MyClass::x.

2. Method Reference Operator (Java):
        In Java, "::" is used for method references, which are a way to refer to methods without invoking them.
        For instance, you can use ClassName::methodName to refer to a static method or objectName::methodName to refer to an instance method.

```
list.forEach(System.out::println);
```

4. Type Casting (C#):
        In C#, the "::" symbol is used for type casting, especially in cases involving the as operator, to cast an object to a specific type.
        For example: objectOfTypeB as TypeA would cast objectOfTypeB to TypeA.

5. Nested Class Separator (C++ and C#):
        In both C++ and C#, "::" is used as a separator to access nested classes within a class.
        For example, if you have a nested class InnerClass within an outer class OuterClass, you can access it using OuterClass::InnerClass in C++ or OuterClass.InnerClass in C#.

6. Scope Operator (PHP):
        In PHP, "::" is used as the scope operator to access static properties, methods, and constants of a class without needing to create an instance of the class.
        For example, ClassName::staticMethod() is used to call a static method.

7. Method Resolution Operator (Python - Notation in Django):
        In Python, "::" is used in the context of Django, a Python web framework, to refer to the method resolution order of classes.
        For example, MyModel::some_method can be used in Django models to refer to the method some_method.

8. Alternative Syntax (JavaScript):
        In JavaScript, "::" is not a standard operator, but it may be used in some transpilers or preprocessors as an alternative syntax for certain purposes. For example, some JavaScript compilers use "::" to define static methods in classes.

9. Namespace or Constant action in Ruby:

```
Math::PI       # => 3.1415926535
EisBilling::Invoice  # => viitab klassile Invoice moodulis EisBilling
```   


<h1><p align="center";>; and ;; - Semicolon and double semicolon</p></h1>
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

;; - double semicolon
In Bash/Shell scripting it is used as ending for cause-sentence 

```
case "$fruit" in
    apple)
        echo "Apple";;
    banana)
        echo "Banana";;
esac
```

OCaml/F#

```
let x = 5;;
let y = x + 2;;
```

Theoretically it can be used in Ruby to put multiple commands on one line

```
puts "Hello";; puts "World"
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

<h1><p align="center";>( , ) and (( , )) - Parentheses and double parentheses</p></h1>

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

The use of double parentheses (( and )) in programming is not common and is not part of the standard syntax of most programming languages. However, there are some specific contexts where you might encounter double parentheses:

1. Shell Scripting: In Unix shell scripting (e.g., Bash), double parentheses can be used for arithmetic operations in conditional statements or loops. For example:
```
if ((x > y)); then
    # Do something
fi
```
Here, double parentheses are used to perform arithmetic comparisons.

2. Regular Expressions: Some regular expression engines, like Perl's, support double parentheses as a way to capture subgroups within a regular expression pattern. For example:
```
if ($text =~ /((pattern))/) {
    my $captured_text = $1;
    # Do something with captured_text
}
```
In this case, the double parentheses are used for capturing a subgroup within the regular expression.


<h1><p align="center";>{ , } and {{ , }} - Curly braces and double curly braces</p></h1>

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

Double curly braces {{ and }} are often used in programming, but their usage can vary depending on the programming language and context. In many programming languages, double curly braces are used for template or string interpolation.
    Web Templates (e.g., HTML templates, JavaScript templates): In web development, double curly braces are often used to insert dynamic content into templates. 1. For example, in the popular JavaScript library Handlebars.js, you might see code like this:
```
<p>{{user.name}}</p>
```
In this case, {{user.name}} would be replaced with the actual name of the user when rendering the template.

2. Python (e.g., f-strings): In Python, double curly braces can be used within f-strings for string formatting. For example:
```
name = "Alice"
greeting = f"Hello, {{name}}"
print(greeting)
```
This would print: "Hello, {name}"

3. Configuration Files: Some configuration file formats, like YAML, use double curly braces for variable substitution. For example:
```
database:
  username: {{db_username}}
  password: {{db_password}}
```
In this case, {{db_username}} and {{db_password}} would be replaced with actual values during configuration processing.


<h1><p align="center";>[ , ] and [[ , ]] - Square braces and double square braces</p></h1>
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

The use of double square brackets [[ and ]] is not a common feature in most programming languages, and it is not part of the standard syntax of popular programming languages. However, there are some contexts where you might encounter double square brackets:

1. Bash Shell: In Bash, a popular Unix shell, double square brackets [[ and ]] are often used for conditional expressions. Bash supports extended conditional tests with [[ and ]] that allow for more complex conditional logic compared to single square brackets [ and ]. For example:
```
if [[ $x -eq $y ]]; then
    # Do something
fi
```
In this case, double square brackets are used for conditional testing.

2. Lua Programming Language: In the Lua programming language, double square brackets are used to define multi-line string literals, known as long strings. For example:
```
local myString = [[
This is a
multi-line
string.
]]
```
In Lua, double square brackets indicate the start and end of a long string literal.

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
To point out structured hierarchy. For example Java packet names:
```
com.example.myapp
```
Object Property Assignment: In JavaScript, you can use the dot operator 
to add or modify properties of objects. For example:
```
const person = {};
person.name = "David";  // Adding the "name" property using the dot operator
person.age = 28;        // Adding the "age" property using the dot operator
```

## Arrow Function

<h1><p align="center";>=> and -> - arrow function and hash rocket</p></h1>    

The symbol "=>" in programming is typically used in the context of anonymous functions or lambda expressions, especially in languages that support functional programming features. It is most commonly associated with languages like JavaScript, Python, Ruby, and C#, among others.
JavaScript:
In JavaScript, the "=>" symbol is used to define arrow functions, also known as fat arrow functions. Arrow functions provide a more concise way to write anonymous functions. Example:
```
// Traditional function expression
const add = function (a, b) {
  return a + b;
};

// Arrow function
const addArrow = (a, b) => a + b;
```
Arrow functions have a shorter syntax and lexically bind the this value, which can be particularly useful in certain contexts.

C#:
In C#, the "=>" symbol is used to define lambda expressions. Lambda expressions are used in LINQ (Language-Integrated Query) and functional programming constructs. C# example:
```
List<int> numbers = new List<int> { 1, 2, 3, 4, 5 };
List<int> evenNumbers = numbers.Where(x => x % 2 == 0).ToList();
```
In this example, the x => x % 2 == 0 is a lambda expression that defines a predicate to filter even numbers from the list.

Ruby:
In Ruby, the "=>" symbol is used in hash literals to define key-value pairs. For example:
```
person = { name: "John", age: 30 }
```
In this case, name: and age: are symbols used as keys, and "John" and 30 are their corresponding values.

Python (PEP 3107):
Python doesn't use "=>" for lambda expressions; instead, it uses the lambda keyword. However, Python 3 introduced a similar syntax for specifying function annotations, which uses "=>" for defining type hints in function signatures. For example:
```
def add(a: int, b: int) -> int:
    return a + b
```

Here, a: int and b: int use the "=>" symbol to indicate that a and b are of type int, and -> int specifies the return type.

In Ruby => symbol is called hash rocket and it's used in hashes to join key value pairs 

```
numbers = {
  :one => 1,
  :two => "two",
  :three => 3,
}
```


## Arithmetic Operators

<h1><p align="center";>+ and ++ - plus and double plus</p></h1>    

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
In CSS, the plus sign (+) is used as a selector to target elements that are immediately preceded by a specified element. This is called the adjacent sibling combinator.

For example, if you have the following HTML:
```
<p>Paragraph 1</p>
<div>Div 1</div>
<p>Paragraph 2</p>
```
You can use the adjacent sibling combinator to select the <div> element that directly follows a <p> element like this:
```
p + div {
    /* CSS rules for div immediately following a p */
}
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
Kebab-case is a variable naming convention where each word is in lower case, and separated by dashes. It is also known as dash-case, list-case, or spinal-case. Used in HTML and CSS:
```
my-method, calculate-sum
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

<h1><p align="center";>% and %% - percent and double percent or modulo or mod</p></h1>
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

The "%%" symbol does not have a standard or widely recognized usage in mainstream programming languages. Its meaning and usage can vary greatly depending on the specific context and the programming language or tool in which it is used.

1. String Formatting (Custom Usage):
        In some custom string formatting or templating systems, "%%" might be used to represent a literal "%" character when you want to include a "%" symbol in the formatted output. This is often used when "%" has a special meaning for string interpolation or formatting.
    Example (hypothetical custom format): "Your discount is 20%% off!"
2. Special Syntax (Custom Usage):
        In specific programming environments or libraries, "%%" might be used as part of a special syntax or pattern matching feature, but this usage would be specific to that environment or library and not widely recognized.
3. Mathematical or Computational Usage (Custom Usage):
        In some mathematical or computational contexts, "%%" might be used as a placeholder or delimiter for specific operations or calculations, but this would depend on the specific problem domain or application.
4. In many programming languages, especially those used for scripting and data analysis, the "%%" symbol (often pronounced as "modulo" or "mod") is used to determine whether a given number (usually an iteration count) is evenly divisible by another number. This is commonly used in loops to perform certain actions every nth iteration, such as displaying a progress indicator, updating a counter, or executing specific code.

   Here's how it works in pseudocode or some programming languages:
```
for i in range(1, N + 1):
    if i %% M == 0:
        # Code to execute every Mth iteration
```
In this example:
    "i" represents the current iteration.
    "N" is the total number of iterations.
    "M" is the desired interval at which you want to perform a specific action.
The condition i %% M == 0 checks whether "i" is evenly divisible by "M." If it is, the code inside the if statement is executed on every Mth iteration.

For example, if you want to print a progress update every 10th iteration in a loop, you would use if i %% 10 == 0, as you mentioned. This is a common technique for controlling and monitoring the progress of loops and batch processes.

The "%%" operator is often used in this context because it provides a straightforward way to determine whether an iteration is a multiple of a specific number, making it easy to perform actions at regular intervals during the loop execution.


## Iterating variables

<h1><p align="center";>i and j - iterating variables</p></h1>

In programming, the letter "i" (and sometimes "j") is commonly used as a variable name in loops, especially for iterating over sequences like arrays, lists, or ranges. This practice has its roots in mathematics and programming conventions.
    Iterating Variable:
        The variable "i" is often used as a shorthand for "index" or "iteration" in loops. It's used in for, while, and similar loop constructs to keep track of the current position or iteration count.
        Example, in Python:
```
for i in range(5):
    print(i)
```

In this loop, "i" takes on values from 0 to 4 in each iteration.
Nested Loops:
    When you have nested loops (loops within loops), "i" is often used for the outer loop, and "j" for the inner loop, and so on. This convention helps in keeping track of multiple levels of iteration.
    For example, in C++:
```
for (int i = 0; i < 3; i++) {
    for (int j = 0; j < 2; j++) {
        cout << "i: " << i << ", j: " << j << endl;
    }
}
```
 Here, "i" is used for the outer loop, and "j" is used for the inner loop.
Mathematical Influence:
    The use of "i" and "j" in programming is influenced by mathematical conventions, where these letters are commonly used as indices or variables in mathematical equations.
Readability:
    Using "i" and "j" for loop variables is a widely accepted practice that can enhance code readability, as it makes it clear that these variables are used for iteration purposes.
Other Usage:
    In some programming contexts, "i" or "j" might be used for other purposes, such as as abbreviations for "input" or "integer." However, their most common usage is for loop variables.

<h1><p align="center";>i++ and ++i - Post-increment and Pre-increment</p></h1>

i++ and ++i are both increment operators used in various programming languages, such as C++, Java, and C#. They are used to increase the value of a variable by 1, but they have different behaviors in terms of when the increment takes place:
    i++ (Post-increment):
        i++ is a post-increment operator, which means it increments the value of i but returns the original value of i before the increment.
        After the value is returned, i is then incremented by 1.
        It is often used when you want to use the current value of i in an expression before incrementing it.
    Example in C++:
```
int i = 5;
int result = i++; // result will be 5, and i will become 6
```

++i (Pre-increment):
    ++i is a pre-increment operator, which means it increments the value of i and returns the updated value.
    It increments i by 1 first and then returns the incremented value.
    It is used when you want to use the updated value of i in an expression.
Example in C++:
```
int i = 5;
int result = ++i; // result will be 6, and i will become 6
```


## Assignement operators

<h1><p align="center";>= - equal sign or assignement</p></h1>
In programming, the single equal sign (=) is used as the assignment operator. Its primary purpose is to assign a value to a variable or a data structure. The assignment operator is fundamental to the process of storing and manipulating data in computer programs. Here's how it works:

Assignment Operator (=):
    Variable Assignment: The most common use of the = symbol is to assign a value to a variable. When you use =, you're essentially telling the computer to store the value on the right-hand side in the variable on the left-hand side.
    Example in Python:
```
x = 10  # Assigns the value 10 to the variable x
```
Example in JavaScript:
```
let name = "Alice";  // Assigns the string "Alice" to the variable name
```
Reassignment: You can also use = to reassign a new value to an existing variable, which overwrites the previous value.
Example in C++:
```
int count = 5;      // Assigns the value 5 to the variable count
count = count + 1;  // Reassigns count to 6
```
Data Structure Initialization: In some programming languages, = can be used to initialize data structures like arrays and dictionaries.
Example in Python:
```
my_list = [1, 2, 3]  # Initializes a list with values
```
Function Call Assignment: In some languages, like Python, you can use = to assign the result of a function call to a variable.
Example in Python:
```
result = add(3, 4)  # Assigns the result of the add function to result
```
The assignment operator is essential for managing data and controlling the flow of a program. It allows you to store, update, and manipulate data throughout your code. However, it's crucial to understand the difference between the assignment operator (=) and the equality operator (== or === in some languages). The equality operator is used to compare values for equality, whereas the assignment operator is used to assign values to variables.

For example, in Python:
```
    x = 5 assigns the value 5 to the variable x.
    x == 5 checks if the value of x is equal to 5.
```

<h1><p align="center";>+=, -=, *= and /= - compound assignement operators</p></h1>
The symbols +=, -= , *= , and /= are compound assignment operators used in programming languages to perform an operation (addition, subtraction, multiplication, or division) and assign the result to a variable in a more concise way. These operators combine an arithmetic operation with assignment.
    += (Addition Assignment):
        The += operator is used to add the value on the right-hand side to the current value of the variable on the left-hand side and then assign the result back to the variable on the left.
    Example in Python:
    
```
x = 5
x += 3  # Equivalent to x = x + 3
# Now, x is 8
```
-= (Subtraction Assignment):
    The -= operator is used to subtract the value on the right-hand side from the current value of the variable on the left-hand side and then assign the result back to the variable on the left.
Example in C++:
```
int a = 20;
a -= 7;  // Equivalent to a = a - 7
// Now, a is 13
```
*= (Multiplication Assignment):
    The *= operator is used to multiply the current value of the variable on the left-hand side by the value on the right-hand side and then assign the result back to the variable on the left.
Example in Python:
```
b = 3
b *= 4  // Equivalent to b = b * 4
// Now, b is 12
```
/= (Division Assignment):
    The /= operator is used to divide the current value of the variable on the left-hand side by the value on the right-hand side and then assign the result back to the variable on the left.
Example in JavaScript:
```
let d = 16;
d /= 4;  // Equivalent to d = d / 4
// Now, d is 4
```

<h1><p align="center";>%= - modulus assignement</p></h1>
Modulus Assignment (%=): Performs the modulus operation on the variable's current value and the value on the right-hand side, and then assigns the result back to the variable.

Example in Python:
```
x = 10
x %= 3  # Equivalent to x = x % 3
# Now, x is 1
```

<h1><p align="center";>//= - floor division assignement</p></h1>
The //= and **= symbols are assignment operators used in some programming languages for specific operations. Here's what each of them does:
    //= (Floor Division Assignment):
        The //= operator is used for floor division (integer division) and assignment. It divides the current value of the variable on the left-hand side by the value on the right-hand side using floor division and then assigns the result back to the variable on the left.
        Floor division means that the result is the largest integer that is less than or equal to the exact division result. It essentially truncates any decimal places, resulting in an integer quotient.
    Example in Python:
    
```
x = 20
x //= 3  # Equivalent to x = x // 3
# Now, x is 6 (integer division of 20 by 3)
```
Some languages, like Python, use // for floor division, and the //= operator follows the same convention.

<h1><p align="center";>**= - exponentiation assignement</p></h1>
**= (Exponentiation Assignment):
    The **= operator is used for exponentiation and assignment. It raises the current value of the variable on the left-hand side to the power of the value on the right-hand side and then assigns the result back to the variable on the left.
Example in Python:

```
y = 3
y **= 2  # Equivalent to y = y ** 2
# Now, y is 9 (3 raised to the power of 2)
```

<h1><p align="center";>&= , |= , ^= - bitwise assignements</p></h1>
Bitwise Assignment Operators (&=, |=, ^=): These operators perform bitwise AND, OR, and XOR operations, respectively, on the variable's current value and the value on the right-hand side, and then assign the result back to the variable.

Example in C++ (Bitwise AND Assignment):
```
int a = 12;     // Binary: 1100
a &= 6;          // Equivalent to a = a & 6 (Binary: 0110)
// Now, a is 4 (Binary: 0100)
```

<h1><p align="center";><<= and >>= - shift assignements</p></h1>
Shift Assignment Operators (<<=, >>=): These operators perform left or right bitwise shift operations on the variable's current value and the value on the right-hand side, and then assign the result back to the variable.

Example in Python (Left Shift Assignment):
```
b = 8
b <<= 2  # Equivalent to b = b << 2
# Now, b is 32
```

<h1><p align="center";>&&= and ||= - logical assignements</p></h1>
Logical Assignment (&&=, ||=): These operators perform logical AND and logical OR operations, respectively, on the variable's current value and the value on the right-hand side, and then assign the result back to the variable.

Note: These operators are less common and are not available in all programming languages.

||= assign if nil/false known as or-equals in Ruby:

```
name = nil
name ||= "Martin"
puts name  # => "Martin"

name ||= "John"
puts name  # => "Martin" (value will not change because of truthy)
```

&&= assign if true known as and-equals in Ruby:

```
age = 25
age &&= 30
puts age  # => 30 (because age is truthy)

age = nil
age &&= 40
puts age  # => nil (because age is nil, no change)
```


## Comparsion operators

<h1><p align="center";>== and != - equal and not equal</p></h1>
The == (double equals) and != (not equals) operators are comparison operators used in programming to compare two values and determine whether they are equal or not equal, respectively. These operators are commonly used for making decisions, controlling program flow, and implementing conditional logic. Here's an explanation of how they work:

== (Double Equals Operator):

The == operator is used to compare two values for equality. It returns true if the values are equal and false if they are not. The comparison is based on the values themselves, without considering their data types (i.e., type coercion may occur in some languages). For example:
    In Python:
```
x = 5
y = 5
result = x == y  # result is True
```

In JavaScript:
```
let a = 10;
let b = "10";
let isEqual = a == b;  // isEqual is true (type coercion)
```

!= (Not Equals Operator):

The != operator is used to check if two values are not equal. It returns true if the values are not equal and false if they are equal. Like the == operator, it may perform type coercion in some languages. For example:
    In Python:
```
a = 5
b = 10
notEqual = a != b  # notEqual is True
```
<h1><p align="center";>=== and !== - strict equal and not strict equal</p></h1>
If you want to perform strict equality or inequality checks that consider both value and data type, you can use the === (strict equality) and !== (strict inequality) operators in languages like JavaScript:
    In JavaScript (strict equality):
    
```
let a = 10;
let b = "10";
let isStrictlyEqual = a === b;  // isStrictlyEqual is false
```

In JavaScript (strict inequality):

```
let x = 5;
let y = "5";
let isStrictlyNotEqual = x !== y;  // isStrictlyNotEqual is true
```
These strict comparison operators ensure that both the values and data types of the operands are considered in the comparison.

<h1><p align="center";><> and >< - not equal operators</p></h1>

SQL:

```
SELECT * FROM users
WHERE age <> 30;
```

Pascal:

```
if x <> y then
  writeln('Not equal');
```

VBA/Excel macro

```
If Cells(1,1).Value <> 10 Then
    MsgBox "Value is not 10"
End If
```

In some older SQL dialects >< is used for not equal comparsion:

```
SELECT * FROM table WHERE column >< 10;
```

<h1><p align="center";>< and > - less than and greater than</p></h1>
In programming, the less-than (<) and greater-than (>) symbols are comparison operators used to perform relational comparisons between values or expressions. These operators are fundamental for making decisions, implementing conditional logic, and ordering elements in various programming contexts.
    < (Less-Than Operator):
The < operator is used to check if the value on the left is less than the value on the right. It returns true if the left operand is smaller than the right operand and false otherwise. For example:

In Python:
```
x = 5
y = 10
isLessThan = x < y  # isLessThan is True
```

> (Greater-Than Operator):
The > operator is used to check if the value on the left is greater than the value on the right. It returns true if the left operand is larger than the right operand and false otherwise. For example:
    In Python:
```
a = 15
b = 10
isGreaterThan = a > b  # isGreaterThan is True
```
Common Use Cases:
    Conditional Statements: These operators are commonly used in conditional statements (e.g., if, else if, while, for) to control the flow of a program based on the relationships between values.
```
if (x < y) {
    // Do something when x is less than y
} else if (x > y) {
    // Do something when x is greater than y
} else {
    // Do something when x is equal to y
}
```
Angle brackets < and > are used to enclose and define HTML elements. HTML elements are structured using opening and closing tags, and these tags are essentially used like parentheses to define the start and end of elements. Here's an example of how angle brackets are used in HTML:
```
<p>This is a paragraph element.</p>
```
In the example above, <p> is the opening tag, and </p> is the closing tag. Together, they define a paragraph element, and the content "This is a paragraph element." is enclosed within the tags.

HTML uses a markup language syntax, and angle brackets are a fundamental part of this syntax for creating and structuring web content. In HTML, tags serve to group and define elements, and their use is similar to how parentheses are used to group expressions in programming languages.

So, in HTML, angle brackets < and > are used as a form of "parentheses" for defining and structuring HTML elements.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

CSS uses the greater-than symbol (>) for the child combinator selector. This selector is used to target elements that are direct children of a specified parent element.
For example, if you have the following HTML structure:
```
<div class="parent">
    <p>Child paragraph 1</p>
    <p>Child paragraph 2</p>
</div>
```
You can use the child combinator selector to target the p elements that are direct children of the .parent element like this:
```
.parent > p {
    /* CSS rules for direct child paragraphs of .parent */
}
```

<h1><p align="center";>&lt;/&gt; - closing tag</p></h1>
&lt;/&gt; does not have any meaningful use but it represents a closing tag in XML, HTML and XTHTML
It can be used as a logo for HTML or web development.

```
<p>This is a paragraph.</p>
```

In computer science, &lt;/&gt; is a symbol used to represent code or programming. It is often used in online forums, chat rooms, or messaging apps to indicate that the following text or code is a computer program. The &lt;/&gt; symbol is meant to resemble HTML code tags, which are used to mark up text and indicate that it should be interpreted as HTML code.

The &lt;/&gt; symbol can be used in a variety of contexts, such as:
- In programming forums or chat rooms, users might use </> to indicate that they are posting code or asking for help with a coding problem.
- In social media or messaging apps, users might use </> to share code snippets or programming-related content with others.
- In code editors or integrated development environments (IDEs), the </> symbol might be used to represent a button or menu option for inserting code snippets or formatting code.

Overall, the &lt;/&gt; symbol has become a popular shorthand for representing programming and coding in online contexts.


<h1><p align="center";><= and >= - less than or equal to AND greater than or equal to</p></h1>
The <= (less than or equal to) and >= (greater than or equal to) operators are comparison operators used in programming to check if a value is less than or equal to or greater than or equal to another value, respectively. These operators are commonly used in conditional statements, loop control, and comparisons involving numeric and non-numeric data types. Here's how they work:


<= (Less Than or Equal To Operator):

The <= operator checks if the value on the left is less than or equal to the value on the right. It returns true if the left operand is smaller than or equal to the right operand and false otherwise. For example:
    In Python:
```
x = 5
y = 10
isLessThanOrEqualTo = x <= y  # isLessThanOrEqualTo is True
```

\>= (Greater Than or Equal To Operator):
The >= operator checks if the value on the left is greater than or equal to the value on the right. It returns true if the left operand is larger than or equal to the right operand and false otherwise. For example:
    In Python:
```
a = 15
b = 10
isGreaterThanOrEqualTo = a >= b  # isGreaterThanOrEqualTo is True
```

Common Use Cases:
    Conditional Statements: These operators are frequently used in conditional statements (if, else if, while, for) to make decisions based on whether values meet certain conditions.
```
if (x <= y) {
    // Do something when x is less than or equal to y
} else {
    // Do something else
}
```
Loop Control: In loop conditions, these operators determine when a loop should continue or terminate based on the relationship between values.
Data Validation: When validating input data, these operators are used to check if the input meets certain requirements or constraints.
Sorting: In sorting algorithms, these operators are used to compare elements and arrange them in ascending or descending order.
Data Structures: In data structures like trees, heaps, and priority queues, these operators are used to maintain hierarchical structures and order elements accordingly.

These operators are versatile and can be used with various data types, including numeric, string, and custom data types, depending on the programming language and context. They are essential tools for implementing logic that depends on the relationships between values.

<h1><p align="center";><=> - combined comparsion operator or spaceship operator</p></h1>
Used in Ruby, Perl, PHP 7+ and C++20
It returns 0 if the first operand (item to be compared) equals the second, 1 if the first operand is greater than the second, and -1 if the first operand is less than the second.

```
print 5 <=> 10; # -1
print 10 <=> 10; # 0
print 15 <=> 10; # 1
```

In old Python (2.x) had similar method cmp()

```
cmp(5, 10)  # -1
cmp(10, 10) # 0
cmp(15, 10) # 1
```

## Logical operators

<h1><p align="center";>| and || - vertical bar and double vertical bar or pipe</p></h1>
The vertical bar | symbol is used in programming languages for various purposes, depending on the context and programming language. 
Logical OR Operator:
In some programming languages, including Python and JavaScript, the | symbol is also used as a logical OR operator. It returns true if at least one of the operands is true. For example:
    In Python:
    
```
x = True
y = False
result = x | y  # result is True
```
Double vertical bars || have specific usage in programming languages. They are typically used as the logical OR operator. The || operator performs a logical OR operation between two Boolean values or expressions and returns true if at least one of the operands is true. Here's how it works:

Logical OR Operator (||):
    In JavaScript:
```
let x = true;
let y = false;
let result = x || y;  // result is true
```

The logical OR operator is commonly used in conditional statements, such as if and while, to control program flow based on whether at least one of the conditions is true. It's a fundamental part of boolean logic in programming and is used for making decisions and implementing branching logic in code.

Here's an example of using || in an if statement:
```
let age = 18;
let hasLicense = true;

if (age >= 18 || hasLicense) {
    console.log("You can drive.");
} else {
    console.log("You cannot drive.");
}
```

In this example, the || operator is used to check if the person's age is 18 or older or if they have a driver's license. If either condition is true, the "You can drive." message is printed.

The logical OR operator is a valuable tool for creating flexible and expressive conditional logic in programming.

<h1><p align="center";>& and && - single and double ampersend</p></h1>
The & and && symbols are used in programming languages for different purposes, primarily related to bitwise operations and logical operations, respectively. 

& (Single Ampersand - Bitwise AND Operator):

The & symbol is used as a bitwise AND operator in many programming languages. It performs a bitwise AND operation between the individual bits of two binary numbers or binary representations of numbers. It returns a result where each bit is set to 1 if and only if the corresponding bits in both operands are 1. For example:
    In Python:
```
a = 5    # Binary: 0101
b = 3    # Binary: 0011
result = a & b  # result is 1 (Binary: 0001)
```

In C++:
```
int x = 6;    // Binary: 0110
int y = 3;    // Binary: 0011
int result = x & y;  // result is 2 (Binary: 0010)
```
&& (Double Ampersand - Logical AND Operator):

The && symbol is used as a logical AND operator in programming languages. It performs a logical AND operation between two Boolean values or expressions. It returns true if both operands are true and false otherwise. The logical AND operator is used for making decisions and controlling program flow based on multiple conditions. For example:
    In JavaScript:
```
let x = true;
let y = false;
let result = x && y;  // result is false
```
In Python:
```
a = True
b = False
result = a and b  # result is False
```
Common Use Cases:

 & (Bitwise AND) is used for low-level operations on individual bits within binary numbers, such as hardware-level programming, encryption, and data manipulation.

 && (Logical AND) is used for higher-level logical operations and decision-making, such as in conditional statements (if, while, for) to control program flow based on conditions.

the & symbol can be combined with other symbols to form compound operators or serve specific purposes. Here are some common examples:
Bitwise AND Assignment (&=): The &= operator combines the & (bitwise AND) operator with the assignment operator (=). It performs a bitwise AND operation between two values and assigns the result to the left operand. It is often used for manipulating and updating binary representations of values.
        In C++:
```
int x = 5;     // Binary: 0101
int mask = 3;  // Binary: 0011
x &= mask;     // Bitwise AND assignment
// Now, x is 1 (Binary: 0001)
```
Address-of Operator (& for References): In C and C++ (and some other languages), the & symbol is also used as the address-of operator. It is used to get the memory address of a variable or object, especially when working with pointers and references.
    In C++:
```
int number = 42;
int* ptr = &number;  // Assign the address of 'number' to 'ptr'
```
Logical AND (&&) vs. Bitwise AND (&): While && is the logical AND operator, & is the bitwise AND operator. It's essential to differentiate between them, as they have different behavior and use cases.
    In C++:
```
bool a = true;
bool b = false;
bool logicalResult = a && b;  // logicalResult is false (logical AND)
int x = 5;
int y = 3;
int bitwiseResult = x & y;   // bitwiseResult is 1 (bitwise AND)
```

<h1><p align="center";>! - exclamation mark</p></h1>
In programming, the exclamation mark (!) is commonly used as a symbol with various meanings and usages depending on the context and programming language. Here are some of the common uses of the exclamation mark in programming:
    Logical NOT Operator (!): The most common usage of ! is as the logical NOT operator. It negates a Boolean value, meaning it changes true to false and false to true. It's used to perform logical negation.
        In JavaScript:
```
let x = true;
let y = !x;  // y is false
```

Regular Expressions (Some Languages): In regular expressions, the ! symbol may be used as part of lookahead or lookbehind assertions to specify conditions for matching patterns without including them in the match itself.
    In Perl (lookahead assertion):
```
my $text = "apple orange";
if ($text =~ /apple(?! pie)/) {
    print "Matched 'apple' but not 'apple pie'.\n";
}
```

Bang Operator (Ruby): In Ruby, the exclamation mark (!) is sometimes used as a naming convention for methods that modify the object in place, indicating a potentially destructive operation.
    In Ruby:
```
array = [1, 2, 3]
array.map! { |x| x * 2 }  # Modifies the original array in place
```
Boolean Casting (Some Languages): In languages like JavaScript, ! can be used for implicit Boolean type casting or coercion.
    In JavaScript:
```
let value = "Hello";
let isFalsy = !value;  // isFalsy is false (implicit type coercion)
```

Example of reversing true/false for boolean in Ruby

```
def toggle(flag)
  !flag
end

puts toggle(true)   # => false
puts toggle(false)  # => true
```

## Bitwise operators

<h1><p align="center";>~ and ~~ - tilde and double tidle</p></h1>
The tilde symbol (~) is used in programming languages for various purposes, primarily related to bitwise operations and sometimes as a mathematical operator for negation or complementing values. 
Bitwise NOT Operator (~):
In many programming languages, the tilde (~) is used as a bitwise NOT operator. It performs a bitwise negation operation, which means it flips the bits of a binary number, changing each 0 to 1 and each 1 to 0.

For example:
    In Python:
```
x = 5      # Binary: 0101
result = ~x  # result is -6 (Binary: 1010)
```
The result of the bitwise NOT operation depends on the number of bits used to represent the values. In many programming languages, it assumes two's complement representation, so the result is a negative number when the original value is positive.

Mathematical Negation (Some Languages):

In some programming languages, particularly in mathematical contexts, the tilde (~) may be used as a symbol for negation or complementing values. However, this usage is not as common as the bitwise NOT operator.

Special Use Cases (Some Languages):

In certain programming languages, the tilde (~) may have specialized uses or meanings beyond its common bitwise NOT operation. For instance, in Perl, it can be used to represent filehandles, and in Ruby, it can be used in regular expressions for negative lookahead assertions.
Double Bitwise NOT ( ~~ ): 
When you use " ~~,"  it effectively applies the bitwise NOT operator twice, which cancels out the effect and returns the original value.
    For example, if you apply " ~~ " to 5, you get 5 back:
```
var x = 5;
var result = ~~x; // result is 5
```
This can be useful in some cases for converting floating-point numbers to integers by removing the decimal part, but it's not as common as other methods like Math.floor() or parseInt().

The "~~" symbol is not a standard operator in all programming languages, and its usage might be more prevalent in languages that heavily rely on bitwise operations, such as JavaScript for certain tricks or optimizations. However, it's generally considered less readable and less idiomatic than using more explicit methods for performing the same operations in code.

<h1><p align="center";>^ - caret</p></h1>
The caret symbol (^) is used in programming languages for various purposes, including bitwise XOR (exclusive OR) operations, exponentiation, and sometimes as a symbol for logical XOR. 
    Bitwise XOR Operator (^):
        In many programming languages, the caret (^) is used as a bitwise XOR operator. It performs a bitwise XOR operation between two binary numbers, where each bit in the result is set to 1 if the corresponding bits in the operands are different.
        Example in Python:
        
```
a = 5     # Binary: 0101
b = 3     # Binary: 0011
result = a ^ b  # result is 6 (Binary: 0110)
```
Exponentiation Operator (^):
    In some programming languages like Python, the caret (^) is used as an exponentiation operator to calculate the power of a number.
    Example in Python:
```
x = 2
y = 3
result = x ** y  # result is 8 (2 raised to the power of 3)
```
Logical XOR (Exclusive OR) Operator:
    In some programming languages, such as Perl and Ruby, the caret (^) can also be used as a symbol for the logical XOR operator, which returns true if one and only one of the operands is true.
    Example in Perl:
```
my $a = 1;
my $b = 0;
my $result = $a ^ $b;  # $result is true (logical XOR)
```

Escape Sequences (Regular Expressions):
    In regular expressions, the caret (^) is often used as a special character to indicate the start of a line or string.
    Example in JavaScript (regex):
```
let text = "Hello\nWorld";
let regex = /^Hello/;  // Matches "Hello" at the start of a line
```

<h1><p align="center";><< and >> - left shift and right shift</p></h1>
The << (left shift) and >> (right shift) symbols are used in programming languages for bitwise shift operations. These operations involve shifting the binary representation of a number to the left or right by a specified number of positions. These operations are commonly used in low-level programming, embedded systems, and situations where fine-grained control over binary data is necessary. Here's how they work:

<< (Left Shift Operator):

The << operator performs a left shift operation, which moves the bits of a binary number to the left by a specified number of positions. Each shift to the left effectively multiplies the number by 2 raised to the power of the shift amount. It's often used to perform fast multiplication or division by powers of 2.

Example in C++:
```
int x = 5;   // Binary: 0101
int result = x << 2;  // result is 20 (Binary: 10100)
```

In Ruby programming language you can add text to the existing string replacing original with two << symbols.

```
str = "Hello"
str << " World!"
puts str # => Hello World!
```

>> (Right Shift Operator):

The >> operator performs a right shift operation, which moves the bits of a binary number to the right by a specified number of positions. Each shift to the right effectively divides the number by 2 raised to the power of the shift amount. It's commonly used for fast division by powers of 2 or extracting individual bytes or bits from binary data.

Example in Python:
```
a = 16   # Binary: 10000
result = a >> 2   # result is 4 (Binary: 0010)
```
1. Bit Manipulation: Bitwise shift operations are used for manipulating individual bits or groups of bits within binary data, such as setting, clearing, or testing specific bits.

2. Fast Multiplication/Division: Left shifting by powers of 2 can be used as a faster alternative to multiplication, and right shifting by powers of 2 can be used as a faster alternative to division.

3. Working with Bit Flags: In embedded systems and hardware programming, bitwise shifts are often used to manipulate and check bit flags within registers or memory-mapped devices.

4. Data Serialization/Deserialization: Bitwise shift operations can be used in data serialization and deserialization to extract or pack binary data into specific fields.

5. Efficient Memory Allocation: In some memory allocation strategies, bitwise shifts are used to allocate memory blocks or manage memory efficiently.


<< is used in Ruby as concatenation operator and called as 'the Showel'
For strings:

```
str = "Hello"
str << " World"
puts str
# Output: "Hello World"
```

For arrays:

```
arr = [1, 2]
arr << 3
puts arr.inspect
# Output: [1, 2, 3]
```
   
<h1><p align="center";><<< and >>> - left shift and right shift</p></h1>
The "<<<" and ">>>" symbols are not commonly used operators in mainstream programming languages. However, they do have specific uses in a few programming contexts, notably in some assembly languages and hardware description languages:
    
1. Assembly Languages:
        In some assembly languages, "<<<" and ">>>" may be used as bitwise shift operators, similar to "<<" and ">>" respectively.
        "<<<" typically represents a left bitwise shift operator, which shifts the bits of a binary number to the left by a specified number of positions, filling the vacated positions with zeroes.
        ">>>" typically represents a logical right shift operator, which shifts the bits to the right, filling the vacated positions with zeroes.
    For example, in x86 assembly, the "SHL" (Shift Left) and "SHR" (Shift Right) instructions are used for these operations, but they do not use "<<<" and ">>>".
   
3. Hardware Description Languages (HDLs):
        In hardware description languages like VHDL and Verilog, "<<<" and ">>>" may be used as shift operators for modeling digital circuits and logic gates.
        Similar to assembly languages, "<<<" represents a left shift, and ">>>" represents a logical right shift in these contexts.
Here's an example of how these operators might be used in VHDL:
            
```
signal data_in : std_logic_vector(7 downto 0);
signal shifted_left : std_logic_vector(7 downto 0);
signal shifted_right : std_logic_vector(7 downto 0);

shifted_left <= data_in <<< 2;  -- Left shift data_in by 2 bits
shifted_right <= data_in >>> 3; -- Logical right shift data_in by 3 bits
```

## String literals

<h1><p align="center";>f-strings or F-strings</p></h1>

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

<h1><p align="center";>@ - at symbol</p></h1>
The "@" symbol (@) has various uses and meanings in programming languages, and its specific function can vary significantly depending on the language and context.
String Literals (C# and Verbatim Strings): In C#, the "@" symbol can be used to define verbatim string literals, which treat backslashes as literal characters and allow multi-line strings.
    C# Example (Verbatim String):
    
```
string filePath = @"C:\MyDocuments\file.txt";
```
Annotations and Decorators (Java, C#): In some programming languages like Java and C#, the "@" symbol is used to denote annotations or decorators. Annotations provide metadata about code elements, and they can affect how code is compiled or executed.
    Java Example:
```
@Override
public void someMethod() {
  // Code here
}
```
Email Addresses: In email-related applications and libraries, the "@" symbol is used to separate the username from the domain in email addresses. While not a programming language feature per se, email parsing and validation often involve handling "@"-separated email addresses.
    Email Address Example:
```
username@example.com
```
Instance Variables (Ruby): In Ruby, the "@" symbol is used to denote instance variables. Instance variables are associated with a particular instance of a class and are used to store object-specific data.
    Ruby Example (Instance Variable):
```
class MyClass
  def initialize
    @instance_var = 42
  end
end
```
Attribute Access (Python): In Python, the "@" symbol is used to access attributes of objects, particularly in the context of class decorators and metaclasses.
    Python Example (Class Decorator):
```
@property
def my_property(self):
    return self._my_property
```
Variable Assignment (Some Scripting Languages): In some scripting languages, such as PowerShell, the "@" symbol may be used for variable assignment or manipulation.
    PowerShell Example:
```
$myVariable = "Hello, World!"
```

## Template literals

<h1><p align="center";>$ and $$ - dollar and double dollar sign</p></h1>
In programming, the dollar symbol ($) is used for various purposes, and its meaning and usage can vary depending on the programming language and context. Here are some common uses of the dollar symbol in programming:
    String Interpolation and Template Literals: In some programming languages and scripting languages, the dollar symbol ($) is used to indicate string interpolation or template literals. It allows you to embed expressions or variables directly within string literals.
        JavaScript (ES6 and later):

```
const name = "Alice";
const greeting = `Hello, ${name}!`; // String interpolation using the dollar symbol
```
Shell Scripting and Unix-like Environments: In shell scripting and Unix-like operating systems, the dollar symbol ($) is used to denote environment variables. When followed by a variable name (e.g., $HOME), it represents the value of that environment variable.
    Bash (Unix shell):
```
echo $USER  # Prints the current user's username
```
Regular Expressions: In regular expressions, the dollar symbol ($) is used as a metacharacter to match the end of a line or string.
    Regular Expression Example (matches lines ending with "end"):
```
/end$/
```
Variable Naming: In some programming languages, such as PHP, Perl, and JavaScript (when using jQuery), the dollar symbol ($) is used as part of variable names to denote scalar variables.
    PHP:
```
$count = 5; // Declaring a variable named $count
```
Interpolation in Template Engines: In certain template engines, like PHP, the dollar symbol ($) is used to interpolate variables and expressions within templates.
    PHP (in a template file):
```
<h1>Welcome, <?php echo $user; ?>!</h1>
```

The "$$" symbol does not have a widely recognized or standardized usage in mainstream programming languages. Its meaning and usage can vary greatly depending on the specific context and the programming language or tool in which it is used.
1. Shell Scripting (Unix/Linux):
        In Unix and Linux shell scripting, "$$" is often used to represent the process ID (PID) of the current running script or shell. For example, you might see it used in a script to create a unique temporary file or directory name.
        Here's an example in a shell script:
```
# Get the PID of the current script
my_pid=$$

# Use it to create a unique temporary file
temp_file="/tmp/my_temp_file_${my_pid}.txt"
```
2. Makefiles (GNU Make):
    In GNU Make, a build automation tool, "" is used to escape a single dollar sign. Since "$" is a special character in Makefiles, "" is used to represent a literal "$" character.
    For example, to output a single "$" character in a Makefile, you would use "$$".
3. Regular Expressions (Some Text Processing Tools):
    In some text processing tools and regular expression engines, "$$" might be used to represent the end of a line or the end of input.
4. Custom or Non-Standard Usage:
    In some programming or scripting contexts, developers might use "$$" for their own custom purposes, but this usage would not be widely recognized or standardized.
5. The "$$" symbol is sometimes used in SQL, particularly in certain SQL database systems, as an alternative delimiter for specifying string literals. Its usage is not standard SQL and is typically found in specific database systems that support it.
For example, in some database systems like PostgreSQL, you can use "$$" to delimit string literals, especially in cases where the standard single quotes might conflict with the content of the string. This can be particularly useful when dealing with SQL queries that contain a lot of single quotes within the string.
Here's an example of using "$$" to delimit a string in PostgreSQL:
```
SELECT $$This is a string with 'single quotes'$$;
```
In this example, the text within the "$$" symbols is treated as a string literal, and any single quotes within it are not interpreted as string delimiters.

It's important to note that the usage of "$$" as a string delimiter is not part of the SQL standard, and it may not be supported in all SQL database systems. It's specific to databases that have chosen to implement this feature for improved compatibility with certain use cases.


<h1><p align="center";>` - accent grave</p></h1>
Template Literals (JavaScript and Others): In JavaScript and similar languages, the accent grave is used to create template literals. Template literals allow for string interpolation, making it easy to embed expressions within string literals.
Example in JavaScript (ES6 and later):

```
const name = "Alice";
const greeting = `Hello, ${name}!`; // String interpolation using the accent grave
```
Character Literals (C, C++, and Others): In some programming languages like C and C++, the accent grave is used to define character literals. It allows you to represent characters using their ASCII or Unicode values.
Example in C:
```
char myChar = `A`; // Represents the character 'A'
```
Raw Strings (Python): In Python, the accent grave is not used as a standalone symbol but can be part of the syntax for creating raw string literals. Raw strings treat backslashes as literal characters, making them useful for regular expressions and file paths.
Example in Python:
```
path = r'C:\Program Files'  # This is a raw string
```

## Separator

<h1><p align="center";>_ - separator or underscore</p></h1>
In programming, the underscore symbol (_) is used for various purposes, and its specific meaning and usage can differ depending on the programming language. 
    Variable Naming Conventions:
        As a Placeholder: In many programming languages, the underscore is used as a placeholder or throwaway variable name when you need to ignore or discard a variable. It's often used in situations where a variable is required for syntactic reasons but its value is not needed.
        Example in Python:
        
```
_, value = get_key_value_pair()
# Here, we only care about 'value' and ignore the key
```

Separating Words in Identifiers: Some programming languages, like Python and Ruby, allow underscores in variable and function names to improve readability. This is often referred to as "snake_case."

Example in Python:
```
user_name = "Alice"
```

Numeric Separators:
    In some modern programming languages, including Python and JavaScript, underscores can be used as numeric separators within numeric literals to make large numbers more readable.
    Example in Python (PEP 515):
```
billion = 1_000_000_000
```
Import and Namespace Usage:
    In some languages, such as Python, the underscore can be used to indicate that a module or variable should be treated as "private" or not part of the public interface.
    Example in Python:
```
from my_module import _private_function
```
Pattern Matching and Wildcards:
    In some contexts, such as pattern matching and regular expressions, the underscore may be used as a wildcard character to match any value or character.
    Example in SQL (wildcard character in a LIKE statement):
```
SELECT * FROM customers WHERE name LIKE 'John _mith';
```
Library-Specific Use:
    Some libraries or frameworks may use the underscore for specific purposes, such as naming conventions for private class members or placeholders in template languages.
Internationalization and Translation:
    In some software development contexts, the underscore may be used as a separator in file and directory names to facilitate internationalization and translation efforts.
    Example in file naming: my_app_en_US.properties

## Escape characters

<h1><p align="center";>\ - backslash</p></h1>
The backslash (\) symbol is used in programming languages for various purposes, and its meaning and usage can vary significantly depending on the language and context. Escape Sequences in Strings:
   Escape Characters: In many programming languages, the backslash is used as an escape character. It is followed by another character to represent special characters, control characters, or Unicode characters within string literals. Common escape sequences include \n for a newline, \t for a tab, and \" to escape double quotes within a string.
   Example in C++:

```
    std::cout << "Hello, \nWorld!\n";
```
Unicode Escapes: In some languages, like Java and Python, you can use backslashes followed by Unicode hexadecimal values to represent Unicode characters.
Example in Java:
```
String smiley = "\u263A"; // Represents a smiley face (☺)
```
File Paths and Directories:
    File Paths: In many programming contexts, especially on Windows and Unix-like systems, the backslash is used as a directory separator in file paths. For example, C:\Program Files\ is a file path on Windows.
    Escape in File Paths: In some languages, like Python, you may need to use double backslashes (\\) or a raw string (preceded by r or R) to represent file paths that contain backslashes.
    Example in Python:
```
path = "C:\\Program Files\\MyApp"
```
Regular Expressions:
    Escape Special Characters: In regular expressions, the backslash is used to escape special characters, allowing you to search for those characters in a text pattern.
    Example in JavaScript:
```
const regex = /\./; // Matches a literal period (.)
```
Escape Sequences: It's also used to define escape sequences in regular expressions for special characters like \n (newline) or \d (digit).
Line Continuation:
    In some programming languages, you can use a backslash at the end of a line to indicate that the statement continues on the next line. This is often used for long lines of code to improve readability.
    Example in Python:
```
long_text = "This is a very long piece of text that \
             continues on the next line for better readability."
```
Regular Characters:
    In some contexts, especially when a character is part of a regular expression pattern or a string literal, the backslash can be used to indicate that a character should be treated as a regular character and not as a special symbol.
    Example in Python (escaping a backslash):
```
text = "This is a backslash: \\"
```

1. Backslash (\): The backslash is the most commonly used escape character in programming languages. It is used to escape special characters or to introduce escape sequences.
        \n: Represents a newline character.
        \t: Represents a tab character.
        \\: Represents a literal backslash character.
        \": Represents a double quote character within a string.
        \': Represents a single quote or apostrophe character within a string.
        \xHH or \uHHHH: Represents a character with a specific hexadecimal Unicode value.

2. Carriage Return (\r): Represents a carriage return character. Used in some languages for text formatting and moving the cursor to the beginning of a line.

3. Line Feed (\n): Represents a newline character. Used to start a new line of text.

4. Tab (\t): Represents a tab character. Used for creating horizontal indentation.

5. Unicode Escape (\u or \U): Represents a Unicode character using its hexadecimal Unicode code point. \u is commonly used for a 16-bit Unicode character, while \U is used for a 32-bit Unicode character.

6. Octal Escape (\nnn): Represents a character using its octal ASCII value. The nnn is a sequence of up to three octal digits.

7. Hexadecimal Escape (\xHH): Represents a character using its hexadecimal ASCII value. The HH is a two-digit hexadecimal number.

8. Alert or Bell (\a): Produces an audible or visible alert, depending on the context.

9. Vertical Tab (\v): Represents a vertical tab character, which can be used for formatting text.

10. Form Feed (\f): Represents a form feed character, which can be used for page breaks or text formatting.

11. Null (\0 or \00): Represents the null character, often used to terminate strings or mark the end of a text.

12. Control Characters (\cX): Represents control characters, where X is an uppercase letter, such as \cA for Ctrl+A.

## Ternary conditional

<h1><p align="center";>? - question mark</p></h1>
In programming, the question mark (?) symbol is used for various purposes, and its meaning and usage can vary depending on the programming language and context. Here are some common uses of the question mark symbol in programming:
    Ternary Conditional Operator: In many programming languages, the question mark (?) is used as part of the ternary conditional operator, also known as the conditional expression. It allows you to create conditional expressions with a compact syntax.
        C/C++/C#:

```
int x = 10;
int y = (x > 5) ? 20 : 30; // If x > 5, y is assigned 20; otherwise, y is assigned 30
```
Null Conditional Operator (?.): In some programming languages like C#, the ?. operator is used to safely access properties or methods of an object, checking for null values along the way. It's known as the null conditional operator or null propagation operator.
    C#:
```
string name = person?.Name; // Access the 'Name' property if 'person' is not null; otherwise, 'name' is null
```
Optional Parameters: In some languages, like TypeScript and some modern JavaScript versions (using Babel or TypeScript), the question mark (?) can be used to denote optional function parameters.
    TypeScript:
```
function greet(name?: string) {
  if (name) {
    console.log(`Hello, ${name}!`);
  } else {
    console.log(`Hello, World!`);
  }
}
```
Regular Expressions: In regular expressions, the question mark (?) is used to denote quantifiers, indicating that the preceding character or group is optional (appearing zero or one time).
    Regular Expression Example (matches "color" or "colour"):
```
/colou?r/
```
Nullable Types (SQL): In SQL, the question mark can be used as a placeholder for parameters in prepared statements. It allows you to provide values for placeholders when executing queries.
    SQL Example (with a prepared statement):
```
SELECT * FROM users WHERE age > ?;
```
Generic Type Parameters (C#): In C#, the question mark (?) can be used to define nullable value types when declaring generic type parameters.
    C# Example (Nullable Generic Type Parameter):
```
List<int?> numbers = new List<int?>();
```
    
## Comments

<h1><p align="center";># - hash</p></h1>
In programming, the # symbol is commonly used for comments and preprocessor directives in various programming languages. The specific usage of # can vary depending on the language, so I'll explain its primary uses:
    Comments: In most programming languages, # is used to indicate the beginning of a comment. Comments are not executed as part of the program but are added for human-readable explanations or annotations within the code. Comments are ignored by the compiler or interpreter.
        Python:
```
# This is a Python comment
```

Preprocessor Directives (C/C++): In C and C++ programming, # is used to indicate preprocessor directives. These are instructions to a preprocessor, which is a tool that runs before compilation. Preprocessor directives are used for including header files, defining macros, conditional compilation, and other tasks.
    C/C++:
```
#include <stdio.h>  // Include a standard library header
#define PI 3.14159   // Define a macro
```
Hashtags or Pound Signs in Strings: In some programming languages, # may be used as part of a string or character literal. In this context, it's treated as a regular character and not as a special symbol.
    Ruby (using # in a string):
```
message = "This is a # symbol in a string."
```

Hexadecimal Notation (Assembly Languages): In assembly languages, # can be used to indicate immediate values or constants in hexadecimal notation.
    x86 Assembly:
```
MOV AL, #0x0A ; Move the value 10 (in hexadecimal) into AL
```
Numeric Keypad (Assembly Languages): In some assembly languages, # is used to represent keys on a numeric keypad for input processing.
    ARM Assembly (Keycode for Number 1):
```
LDR R0, =#1 ; Load register R0 with the value 1
```

<h1><p align="center";>/* ... */ and /** ... */ - delimiters</p></h1>
Multi-Line Comments:
    Delimited by Symbols (/* */): Commonly used in languages like C, C++, and Java. Multi-line comments are enclosed within /* and */.
    Example in Java:
    
```
/*
 * This is a multi-line comment.
 * It can span multiple lines.
 */
```
Documentation Comments:
    Some languages provide a special syntax for documentation comments that can be used to generate documentation from the code. For example, Java uses Javadoc comments, and C# uses XML comments.
    Example in Java (Javadoc comment):

```
/**
 * This is a Javadoc comment used for documentation generation.
 * It includes information about classes, methods, and parameters.
 */
```
<h1><p align="center";>&lt;!-- and --&gt; - enclosing tag comments</p></h1>
HTML (Hypertext Markup Language) comments are used to add explanatory or descriptive text within an HTML document. Comments in HTML are not displayed in the browser and do not affect the rendering of the web page. Instead, they serve as documentation, notes for developers, or reminders about the structure and purpose of the HTML code.

HTML comments are enclosed within <!-- and --> tags and can be placed anywhere in the HTML document. Here's the basic syntax for an HTML comment:
```
<!-- This is an HTML comment -->
```
Key points about HTML comments:
    Invisibility: HTML comments are not visible to users when they view a web page in a web browser. They are purely for developers' reference and documentation.
    Placement: You can place HTML comments within the <html>, <head>, <body>, or any other HTML element. They can also span multiple lines.
    Nested Comments: HTML comments cannot be nested. If you try to nest comments, the first closing --> encountered will close the entire comment block.
```
<!-- This is a valid comment -->
<!-- This <!-- is not --> a valid comment -->
```
Use Cases: HTML comments are commonly used for the following purposes:
        Adding notes or explanations about specific sections of code.
        Temporarily removing or "commenting out" code without deleting it.
        Providing attribution for the code or indicating the author.
        Documenting changes, bug fixes, or TODOs.

Example of HTML comments in an HTML document:
```
<!DOCTYPE html>
<html>
<head>
    <title>My Web Page</title>
    <!-- This is a comment in the head section -->
</head>
<body>
    <h1>Welcome to My Web Page</h1>
    <p>This is some content on the page.</p>
    
    <!--
    This is a multi-line comment.
    It provides additional information about the page structure.
    -->

    <footer>
        <p>&copy; 2023 My Company</p>
        <!-- Author: John Doe -->
    </footer>
</body>
</html>
```

<h1><p align="center";>/*+ ... */ - inline comment</p></h1>
Inline Comments (Database-Specific): Some database systems, like Oracle, support inline comments using /*+ ... */. These comments can affect query optimization.

```
SELECT /*+ INDEX(employees idx_emp_id) */ * FROM employees;
```

<h1><p align="center";>''' ''' or """ """ - triple quotes</p></h1>
Triple Double Quotes (''' ''' or """ """): Commonly used in Python for multi-line comments. Text enclosed in triple double quotes serves as a multi-line comment.
Example in Python:

```
"""
This is a multi-line comment.
It can span multiple lines.
"""
```
