---
title       : 1/5
description : 1/5
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
## Numbers(1/2)

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
## Numbers(2/2)

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
