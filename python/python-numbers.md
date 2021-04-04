# Python Numbers
There are three numeric types in Python, they are:

- int
- float
- complex
Variables of numeric types are created when you assign a value to them.
```
x = 1    # int
y = 2.8  # float
z = 1j   # complex
# To verify the type of any object in Python, use the type() function
print(type(x))
print(type(y))
print(type(z))
```

## Integar(int)
Int or integer is a whole number, positive or negative, without decimals, of unlimited length.
```
x = 1
y = 35656222554887711
z = -3255522
# Use the type() function to verify the type
print(type(x))
print(type(y))
print(type(z))
```

## Float
Float, or "floating point number" is a number, positive or negative, containing one or more decimals.
```
x = 1.10
y = 1.0
z = -35.59
# Use the type() function to verify the type
print(type(x))
print(type(y))
print(type(z))
```
## Complex
Complex numbers are written with a "j" as the imaginary part:
```
x = 3+5j
y = 5j
z = -5j
# Use the type() function to verify the type
print(type(x))
print(type(y))
print(type(z))
```
## Type Conversion
You can convert from one type to another with the int(), float(), and complex() methods:

```
# Convert from one type to another:

x = 1    # int
y = 2.8  # float
z = 1j   # complex

#convert from int to float:
a = float(x)

#convert from float to int:
b = int(y)

#convert from int to complex:
c = complex(x)

print(a)
print(b)
print(c)

print(type(a))
print(type(b))
print(type(c))
```
