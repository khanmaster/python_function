# This lesson covers Python Functions
## What are functions and why are they useful
### How to create a function
### function best practices

**What are functions and why**

**DRY DON'T REPEAT YOURSELF**

- How to create a function

Syntax: ```def name_of_function():```

- Let's create a greeting function



- each function has a block of code to execute to ideally run one task
```
def greeting(name):
     print("Welcome on board " + name)

# # if we execute this program now it would display nothing as we have not call this function

# Syntax to call the function

greeting("shahrukh")
# calling our greeting function
# this will execute code inside our function
```
- create a new function that takes 2 arguments as ints and adds the value of the to args

```
def add(num1, num2):
- creating an add function that takes 2 arguments
    print(num1 + num2)
# Displaying the sum of args received

add(4, 8)
```
- Creating a subtract function
```
def subtract(num1, num2):
# creating a function to subtract 2 arg provided

    return num1 - num2
# We use return statement which is key to python functions which means return the result of any function

# calling the function and passing 2 values with return statement
print(subtract(3, 2))
```

**Task**
```
create a function to *
create a function to /
create a function to %
research return statement and use it instead of print in your functions
```
### Best Practice 
- Best practice is to have small block of in any function that does one job
- pseudo coding - one line of explanation 
- HINTs: create hints in simple bullet points or pointer
- comments regarding you function results