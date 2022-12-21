# Development Environment Setup
- Download Python interpreter
- Download Visual Studio Code

# Variables

A variable is a named location in memory where you can store a value.

In Python, you can create a variable by assigning a value to it using the assignment operator (`=`).

For example:
```py
x = 10
message = "hello"
pi = 3.14
```

Here, we have created three variables: x, message, and pi. The variable `x` has an integer value of `10`, `message` has a string value of `"hello"`, and `z` has a float value of `3.14`.


# Data Types

In Python, there are several built-in data types, including integers (`int`), floating-point numbers (`float`), and strings (`str`).

You can use the `type()` function to find out the data type of a variable. 

For example:

```py
print(type(x))          # prints "int"
print(type(message))    # prints "str"
print(type(pi))         # prints "float"
```


# Arrays

An array is a collection of values that are all of the same data type. In Python, you can create an array using the `list` data type. 

For example:

```py
my_list = [1, 2, 3, 4, 5]  # creates a list of integers
my_string_list = ["hello", "world"]  # creates a list of strings
my_mixed_list = [1, "hello", 3.14]  # creates a list with mixed data types
```

You can access individual elements in a list using their index, which starts at 0. For example:

```py
print(my_list[0])  # prints 1
print(my_string_list[1])  # prints "world"
```

You can also modify elements in a list by assigning a new value to them using their index:

```py
my_list[0] = 10
print(my_list[0])  # prints 10
```


# For Loops

A for loop is a way to iterate over a sequence of elements, such as a list. 

For example:

```py
for i in my_list:
    print(i)
```

This for loop will print each element in my_list on a separate line.

# While Loops

A while loop is a way to repeat a block of code until a certain condition is met. 

For example:

```py
i = 0
while i < 5:
    print(i)
    i += 1
```

This while loop will print the values 0 through 4 on separate lines.

# If Statements

An if statement is a way to execute a block of code only if a certain condition is met. For example:

```py
x = 10
if x > 5:
    print("x is greater than 5")
```

This if statement will print "x is greater than 5" because the condition x > 5 is true.

```py
x = 10
if x > 10:
    print("x is greater than 10")
elif x < 10:
    print("x is less than 10") 
else:
    print("x is 10")
```

This statement will print `x is 10`.


# Basic Input/Output

To get input from the user, you can use the `input()` function.

This function takes a string as an argument, which is used as a prompt to ask the user for input. 

For example:

```py
name = input("What is your name? ")
print("Hello, " + name)
```

# Functions

A function is a block of code that performs a specific task and can be called by name. Functions are useful for organizing and reusing code, and can help you break down a larger program into smaller, more manageable pieces.

## Defining a Function

To define a function in Python, you use the `def` keyword followed by the function name and a set of parentheses `()`. 

Inside the parentheses, you can specify any parameters that the function takes. The function body is indented and contains the code that is executed when the function is called.

```py
def double(x):
  return x * 2
```

## Calling Functions

To call a function, you use its name followed by a set of parentheses `()` and any required arguments. The function will execute the code in its body and return a result (if it has a return statement).

```py
result = double(10)
print(result)  # Output: 20
```

That's all for today.