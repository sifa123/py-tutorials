

# Python Variables
Variables are used storing data values.

## Creating a Variable
You do need any special function or method to create a variable. A variable is created as soon you assign a value to it

```
y = 13
x = chryzhub`
#both x and y are variables while 13 and chryzhu` are the data stored. You can go ahead to print it
print(x)
print(y)
```

## Variable Names
A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_cost).

### Rules for Python variables
- A variable name must start with a letter or the underscore character
```
my_name = 'Chryz'
_my_name = 'Chryz'
```
- A variable name cannot start with a number
- A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
- ```
# These are the wrong ways of creating a variable names
2myname = 'Chryz'
my-name = 'Chryz'
my name = 'Chryz'
```
## Many Values to Multiple Variables
Python allows you to assign values to multiple variables in one line.
```
x, y, z = 'python', 'chryzhub', 'opensource'
# You can go ahead to print it output
print(x)
print(y)
print(z)
```
Note: Make sure the number of variables matches the number of values, or else you will get an error.

## Output Variables
The Python print statement is often used to output variables. To combine both text and a variable, Python uses the + character. It's called
concatenation. This works for string!
```
x = "awesome"
print("Python is " + x)
```

For numbers, the + character works as a mathematical operator
```
x = 5
y = 10
print(x + y)
```
If you try to combine a string and a number, Python will give you an error
```
x = 5
y = "Chryz"
print(x + y)
```
