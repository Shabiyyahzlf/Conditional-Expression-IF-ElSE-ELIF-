# Learn Pyhthon for Data Analyst
This repository provides an overview of various data types and data structures available in Python. Understanding these concepts is essential for effective programming and data manipulation in Python.

## Data Types
### Numbers
Python supports various numeric data types:
- **Integer(int)**: Integers are whole numbers, without any decimal points. They can be positive, negative, or zero. For example: -5, 0, 42.
- **Float(float)**: Floats are decimal numbers, represented with a decimal point. They can also be positive, negative, or zero. For example: 3.14, -0.5, 2.71828.
- **Complex(complex)**: Complex numbers are a combination of a real part and an imaginary part. They are represented in the form of x + yj, where x is the real part, y is the imaginary part, and j represents the square root of -1. For example: 3 + 4j, -2 - 6j.

### String
A string is a sequence of characters, enclosed within either single quotes (`'`) or double quotes (`"`), allowing manipulation and processing of textual data.

### Boolean
Boolean data type represents truth values, typically denoted as `True` or `False`, and is used in conditional expressions and logical operations.

## Data Structures

### List
A list is a versatile and mutable data structure in Python, capable of holding an ordered collection of items of different data types.

### Tuple
Similar to lists, tuples are ordered collections of items, but they are immutable, meaning their elements cannot be modified after creation.

### Set
A set is an unordered collection of unique elements, useful for performing mathematical set operations such as union and intersection.

   - **Union**: Combines elements from two or more sets, removing duplicates.
   - **Intersection**: Retrieves common elements shared by two or more sets.

### Dictionary
Dictionary in Python is an unordered collection of key-value pairs. Dictionaries can be used to store small to large amounts of data. To access the data, we need to know its key. In Python, dictionaries are defined with curly braces and the following additional definitions:
- Each key-value pair is separated by a comma.
- Key and value are separated by a colon.
- Key and value can be of any variable/object type.

## Python Arithmetic Operators
This repository provides an overview of Python arithmetic operators, including addition, subtraction, multiplication, division, modulus, exponentiation, and floor division.

## Arithmetic Operators
### Addition ( + )
- Adds two operands together.

### Subtraction ( - )
- Subtracts the right-hand operand from the left-hand operand.

### Multiplication ( * )
- Multiplies two operands together.

### Division ( / )
- Divides the left-hand operand by the right-hand operand, always resulting in a floating-point number.

### Modulus ( % )
- Returns the remainder of the division of the left-hand operand by the right-hand operand.

### Exponentiation ( ** )
- Raises the left-hand operand to the power of the right-hand operand.

### Floor Division ( // )
- Performs division where the result is rounded down to the nearest whole number.

## Variable
A variable is a container or storage location in a computer's memory that holds a value with a specific data type. It provides a way for programs to store and manipulate data during execution.
To assign a value to a variable, we use an assignment operator, typically the equal sign (=), to bind the variable name to the desired value.

## String Formatting-Argument Specifiers
String formatting involves taking a set of variables and, using an expression, formatting them into a provided string that contains placeholders for those variables. This can be achieved using the "%" operator combined with "argument specifiers." 
Common argument specifiers include:
- %s - String
- %d - Integers
- %f - Decimal numbers

## Input and Output
The print() function allows you to present output in different formats, while the input() function facilitates user interaction by collecting input while the program is running.
### Output: print
This function allows us to display text, variables, and expressions on the console.
### Input: input()
To enable user input in your program, utilize the input() function. Within parentheses (), provide the text to be displayed (prompt), and assign a variable preceding the equal sign (=) to store the user's input. By default, the input() function in Python is utilized for accepting user input, capturing it as a string.

## Control Flow
### Conditional Expressions 
Conditional expressions, commonly known as the ternary operator in Python, provide a succinct method for creating conditional statements. These expressions enable you to make decisions within a single line of code, enhancing the efficiency and readability of your programs.

#### IF
In Python, expressions are positioned after the if keyword.
Decisions are determined based on the truth value of the expression.
If the expression evaluates to True, the block of statements within the if statement is executed.
Following convention, this block is indented after the colon (:).
If the expression evaluates to False, the next block (after the if statement) is executed.
#### ELSE
The else statement can be combined with the if statement to provide an alternative pathway when the condition/evaluation result is False. 
The else statement is optional and singular.
#### ELIF
Elif is short for else if.
Elif serves as an alternative to nested if statements.
An if statement can be followed by one or more elif statements (optional & unlimited).

### Looping
This repository provides an overview of looping constructs in Python, including for loops, while loops, for-else loops, break statements, continue statements, and list comprehensions.
#### For
- The `for` loop in Python is used to iterate over a sequence (e.g., lists, tuples, strings) or any other iterable object.
- It executes a block of code for each item in the sequence.

#### While
- The `while` loop in Python is used to execute a block of code repeatedly as long as a specified condition is true.
- It continues iterating until the condition becomes false.
#### For Else
- The `for-else` loop in Python is used to execute a block of code after the for loop finishes its iteration.
- It is executed if the loop completes without encountering a `break` statement.
#### Break
- The `break` statement in Python is used to exit the loop prematurely.
- It terminates the loop immediately when encountered, regardless of the loop's condition.
#### Continue
- The `continue` statement in Python is used to skip the rest of the code inside a loop for the current iteration.
- It allows the loop to continue to the next iteration without executing the remaining code.
#### List Comprehension
- List comprehension in Python provides a concise way to create lists.
- It allows you to generate a new list by applying an expression to each item in an existing iterable.






