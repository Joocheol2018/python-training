---
title       : Let's start!
description : Simple
---
## Hello, World!

```yaml
type: NormalExercise
key: 4ecd287fb4
lang: python
xp: 100
skills: 2
```
Python is a very simple language, and has a very straightforward syntax. It encourages programmers to program without prepared code. The simplest directive in Python is the "print" directive - it simply prints out a line (and also includes a newline, unlike in C).

There are two major Python versions, Python 2 and Python 3. Python 2 and 3 are quite different. This tutorial uses Python 3, because it more semantically correct and supports newer features.

For example, one difference between Python 2 and 3 is the print statement. In Python 2, the "print" statement is not a function, and therefore it is invoked without parentheses. However, in Python 3, it is a function, and must be invoked with parentheses.


To print a string in Python 3, just write:

`@hint`

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
print("This line will be printed.")

```

`@solution`
```{python}

```

`@sct`
```{python}

```




---
## Comments

```yaml
type: NormalExercise
key: f3b5cadb49
lang: python
xp: 100
skills: 2
```

Many of the examples in this manual, even those entered at the interactive prompt, include comments. Comments in Python start with the hash character, #, and extend to the end of the physical line. A comment may appear at the start of a line or following whitespace or code, but not within a string literal. A hash character within a string literal is just a hash character. Since comments are to clarify code and are not interpreted by Python, they may be omitted when typing in examples.

`@instructions`

`@hint`

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# this is the first comment
spam = 1  # and this is the second comment
          # ... and now a third!
text = "# This is not a comment because it's inside quotes."

print(spam)
print(text)
```

`@solution`
```{python}

```

`@sct`
```{python}

```
---
## Indentation

```yaml
type: NormalExercise
key: e14199587b
lang: python
xp: 100
skills: 2
```
Python uses indentation for blocks, instead of curly braces. Both tabs and spaces are supported, but the standard indentation requires standard Python code to use four spaces. For example:

`@instructions`

`@hint`

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
x = 1
if x == 1:
    # indented four spaces
    print("x is 1.")
```

`@solution`
```{python}

```

`@sct`
```{python}

```


---
## Exercise

```yaml
type: NormalExercise
key: 5485a53dc2
lang: python
xp: 100
skills: 2
```
Use the "print" command to print the line "Hello, World!".

`@instructions`

`@hint`

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
print("Goodbye, World!")
```

`@solution`
```{python}

```

`@sct`
```{python}

```


---
## Numbers - Integers

```yaml
type: NormalExercise
key: e8c4db2521
lang: python
xp: 100
skills: 2
```

Python supports two types of numbers - integers and floating point numbers. (It also supports complex numbers, which will not be explained in this tutorial).

To define an integer, use the following syntax:


`@instructions`

`@hint`

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
myint = 7
print(myint)
```

`@solution`
```{python}

```

`@sct`
```{python}

```


---
## Numbers - Floating Point Numbers

```yaml
type: NormalExercise
key: 4d80a90feb
lang: python
xp: 100
skills: 2
```

To define a floating point number, you may use one of the following notations:
`@instructions`

`@hint`

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
myfloat = 7.0
print(myfloat)
myfloat = float(7)
print(myfloat)
```

`@solution`
```{python}

```

`@sct`
```{python}

```



---
## Strings (1/2)

```yaml
type: NormalExercise
key: 87d6d4f393
lang: python
xp: 100
skills: 2
```
Strings are defined either with a single quote or a double quotes.

The difference between the two is that using double quotes makes it easy to include apostrophes (whereas these would terminate the string if using single quotes)


`@instructions`

`@hint`

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
mystring = 'hello'
print(mystring)
mystring = "hello"
print(mystring)

mystring = "Don't worry about apostrophes"
print(mystring)
```

`@solution`
```{python}

```

`@sct`
```{python}

```



---
## Strings (2/2)

```yaml
type: NormalExercise
key: 3bfc4978fb
lang: python
xp: 100
skills: 2
```
There are additional variations on defining strings that make it easier to include things such as carriage returns, backslashes and Unicode characters. These are beyond the scope of this tutorial, but are covered in the Python documentation.

Simple operators can be executed on numbers and strings:

`@instructions`

`@hint`

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
one = 1
two = 2
three = one + two
print(three)

hello = "hello"
world = "world"
helloworld = hello + " " + world
print(helloworld)
```

`@solution`
```{python}

```

`@sct`
```{python}

```

---
## Exercise

```yaml
type: NormalExercise
key: 4d9d31b565
lang: python
xp: 100
skills: 2
```
The target of this exercise is to create a string, an integer, and a floating point number. The string should be named mystring and should contain the word "hello". The floating point number should be named myfloat and should contain the number 10.0, and the integer should be named myint and should contain the number 20.

`@instructions`

`@hint`

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# change this code
mystring = None
myfloat = None
myint = None

# testing code
if mystring == "hello":
    print("String: %s" % mystring)
if isinstance(myfloat, float) and myfloat == 10.0:
    print("Float: %f" % myfloat)
if isinstance(myint, int) and myint == 20:
    print("Integer: %d" % myint)

```

`@solution`
```{python}

```

`@sct`
```{python}

```

---
## Arithmetic Operators

```yaml
type: NormalExercise
key: 84dd9f5bfd
lang: python
xp: 100
skills: 2
```
Just as any other programming languages, the addition, subtraction, multiplication, and division operators can be used with numbers.

Try to predict what the answer will be. Does python follow order of operations?

`@instructions`

`@hint`

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
number = 1 + 2 * 3 / 4.0
print(number)
```



`@solution`
```{python}

```

`@sct`
```{python}

```

---
## Modulo

```yaml
type: NormalExercise
key: 16154e14c6
lang: python
xp: 100
skills: 2
```
Another operator available is the modulo (%) operator, which returns the integer remainder of the division. dividend % divisor = remainder.


`@instructions`


`@hint`

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
remainder = 11 % 3
print(remainder)
```

`@solution`
```{python}

```

`@sct`
```{python}

```

---
## Power

```yaml
type: NormalExercise
key: 44fa64a236
lang: python
xp: 100
skills: 2
```
Using two multiplication symbols makes a power relationship.

`@instructions`

`@hint`

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
squared = 7 ** 2
cubed = 2 ** 3
print(squared)
print(cubed)
```

`@solution`
```{python}

```

`@sct`
```{python}

```
