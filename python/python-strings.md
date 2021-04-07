# Strings
Strings in python is anything surrounded by either single quotation marks`''` or double quotation marks`" "`.`'hello'` is the same as `"hello"`. You can display a string literal with the print() function.
```
print("Hello")
print('Hello')
print(type("Hello"))
print(type('Hello'))
```

## Assign String to a Variable
Assigning a string to a variable is done with the variable name followed by an equal sign and the string
```
a = "Hello"
print(a)
```
## Multiline Strings
You can assign a multiline string to a variable by using three quotes.
```
a = ```Chryz-Hub is a Git-Hub community, where your ideas and contributions
are valued and appreciated.We teach programming and also believe in opensource```
print(a)
```
Note: in the result, the line breaks are inserted at the same position as in the code.

## Strings are Arrays
Like many other popular programming languages, strings in Python are arrays of bytes representing unicode characters. However, Python does not have a character data type, a single character is simply a string with a length of 1.

Square brackets can be used to access elements of the string.
```
# Get the character at position 1 (remember that the first character has the position 0):

a = "Hello, World!"
print(a[1])
```

## Looping Through a String
Since strings are arrays, we can loop through the characters in a string, with a for loop.

```
# Loop through the letters in the word "Chryz-Hub":

for a in "banana":
  print(x)
```
Note: the iteration value which is `a` can be changed. You can use any letter or word.

Learn more about For Loops in our Python For Loops chapter.

## String Length
To get the length of a string, use the len() function. The len() function returns the length of a string:
```
a = "Hello, World!"
print(len(a))
```
Note: The space between the two words is counted.

## Check String
To check if a certain phrase or character is present in a string, we can use the word we need to look for and define it by using the single quotation marks`''` or double quotation marks`" "` and also using the `in` python keyword.
```
# Check if "free" is present in the following text

txt = 'Chryz-Hub is a GitHub community!'
print( 'GitHub' in txt)
```
and to also check if is it not there, using both the **not** and **in** python keywords
```
txt = 'Chryz-Hub is a GitHub community!'
print('Python' not in txt)
```
It is going to give you a boolean as an answer. Either **True** or **False** depending on your words/sentences
and what you tend to look for.

You can also do this better by using an **if** statement or keyword.
```
txt = 'Chry-Hub is a GitHub community!'
if 'GitHub' in txt:
  print('Yes, it is there')
```
```
txt = 'Chry-Hub is a GitHub community!'
if 'Python' not in txt:
  print('It is not there')
```
Learn more about If statements in our Python If...Else chapter.
