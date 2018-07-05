---
title       : Contol the flow!
description : Loop and If
---
## Loop

```yaml
type: NormalExercise
key: 4ecd287fb4
lang: python
xp: 100
skills: 2
```
There are two types of loops in Python, for and while.

For loops iterate over a given sequence. Here is an example:

`@hint`

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
primes = [2, 3, 5, 7]
for prime in primes:
    print(prime)

```

`@solution`
```{python}

```

`@sct`
```{python}

```



---
## For loop

```yaml
type: NormalExercise
key: e14199587b
lang: python
xp: 100
skills: 2
```
For loops can iterate over a sequence of numbers using the "range" and "xrange" functions. The difference between range and xrange is that the range function returns a new list with numbers of that specified range, whereas xrange returns an iterator, which is more efficient. (Python 3 uses the range function, which acts like xrange). Note that the range function is zero based.

`@instructions`

`@hint`

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# Prints out the numbers 0,1,2,3,4
for x in range(5):
    print(x)

# Prints out 3,4,5
for x in range(3, 6):
    print(x)

# Prints out 3,5,7
for x in range(3, 8, 2):
    print(x)
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
