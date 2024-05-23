# PYTHON STRING METHODS: center(), rjust() and ljust().
In this Playground tutorial we are going to look at three Python built-in functions, which are part of Python's String Methods.

The three functions we're going to look at are the ```center()```, ```rjust()``` and ```ljust``` functions.
All three are useful for alignment of strings in output.

## String Method 1: ```center()```
The ```center()``` function is a useful for centering a text or string with spaces on either side.

```python
# Syntax:
string.center(integer)
```

Let's see this function in action:
```python runnable
string = "Text"

print(string.center(20)) # The result will be the string "Yellow" with 7 spaces on either side.
```

## String Method 2: ```rjust()```
The ```rjust``` function is useful for aligning a text or string to the right with spaces to the left.

```python
# Syntax:
string.rjust(integer)
```

Let's see an example of this function:
```python runnable
string = "Text"

print(string.rjust(20))
```

## String Method 3: ```ljust()```
The ```ljust``` function is useful for aligning a text or string to the left with spaces to the right.

```python
# Syntax:
string.ljust(integer)
```

Let's see an example of this function:
```python runnable
string = "Text"

print(string.ljust(20))
```

## Experiment: All three Functions
Now have a go with all three functions in the interactive editior below:

```python runnable
string = "Text"

print(string.rjust(10))
print(string.center(10))
print(string.ljust(10))
```

### Conclusion
There we go, a brief introduction to three of Python's String Methods.

As always, I hope you've found this playground tutorial helpful.

If you'd like to see more String Methods, then here is a good link:
 - https://www.w3schools.com/python/python_ref_string.asp

Happy Coding, Code-Parser