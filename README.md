# 2-Variables

In programming, a variable is a slot in the computer's memory that we can give a name and a value to. It is the way we store and manipulate information to do the work of the program.

To create a variable, use an equal sign like this:
```myVarName = value```
Variable names cannot have spaces or punctuation, just letters and numbers.

For this activity, we are going to learn about the three most basic types of variables.

## String Variables (str)
Strings are used when we want the computer to treat the value as characters - the symbols that we call letters, numbers, and punctuation. The computer with store all the characters together as one unit. To define a new string or set a value to one, we use quotation marks around the value like this:
```
myStringVar = "Hello World!"
```

## Integer & Float Variables (int / float)
Integer and float variables are used when we want the computer to treat the value as a number - not the characters that make the number, the actual number. Integer variables are for whole numbers, while float variables are for decimals. Both can be positive or negative. To define these types, do no use quotation marks:
```
myIntVar = 31
myFloatVar = 365.25
```

The actual difference between these three variable types has to do with the way computer memory works, but for now all you need to know is that if you want to do math with them, you have to have your values in an INT or FLOAT type variable.

## Your Task
1.  Define a variable of each type described above
2.  Print your variables using the `print()` function we learned previously


## Bonus
We can use the `format()` function to fill-in values when we print strings:
```
print("We are the {} who say '{}'!".format('knights', 'Ni'))
```
The squiggly brackets ("{}") are used to mark a place for `format()` to drop in the values. 

These can be variables too:
```
myAge = "31"
print("I am {} years old.".format( myAge ))
```
We can even re-order the things to be filled in:
```
print('{0} and {1}'.format('spam', 'eggs'))
>spam and eggs

print('{1} and {0}'.format('spam', 'eggs'))
>eggs and spam
```
Bonus Task: Use `format()` for some of your outputs 
