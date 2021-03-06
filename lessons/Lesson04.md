# Lesson 4

## Operations

We can perform operations on data such as addition, and subtraction to form new
data, we can do this using operations.

## Mathematics

We can perform many operations with integers and floats lets try addition:
```python3
my_number = 3 + 2
```
This will assign the name `my_number` to the result of the operation `3 + 2`, so
this is the same as `my_number = 5`

just as we can add we can **subtract** with `3 - 2`,  
**multiply** with `3 * 2`,
and **divide** with `3 / 2`.

There are more mathematical operations such as **floor**, **modulus**, and
**exponential**, these are less commonly used but can still be very helpful.

When doing operations the **operands** can be variables, like so:
```python3
first_number = 3
second_number = 2

third_number = first_number + second_number
```
> An **operand** is the data the operation acts upon, in the above example
> `first_number` and `second_number` are operands to the addition (+)
> operation.

## Concatenation

A useful operation that we can do with strings is called **concatenation**,
which is where two strings are combined into one "hello " concatenated with
"programmer" makes the string "hello programmer".

Since strings can't be added together like numbers can, we can instead use the
"+" symbol for concatenation.
```python3
first_half = "this "
second_half = "is concatenated"
full_string = first_half + second_half
```
> A common mistake is to forget that when concatenating two strings which are
> whole words we need a space to separate them in the operation.
> ```python3
> wrong = "this is" + "wrong"
> print(wrong)
>```
> The above will print `this iswrong`, lets correct this with a space:
>```python3
> correct = "this is " + "correct"
> print(correct)
>```
> Now we will get `this is correct`.

## Mixing data types

So what happens when we add a string to an integer or float?
don't know?
Well neither does python!
If we try to add a string and a number we get an error message:

`TypeError: unsupported operand type(s) for +: 'int' and 'str'`

This means that there is no such thing as integer + string, this makes a lot of
sense actually, what does it mean to "+" a number and a string, what would
`"chocolate" - 7` actually result in - nothing that makes any sense!

## Operations inside functions

We can do operations inside functions too `print(2 + 4)` will print out 6.

## Casting

So as far as a computer is concerned "4", 4, and 4.0 are all completely
different but we know they all mean the same thing, we can use casting to "turn"
one data type into another (if it would make sense to).

**`str()`** is a function that turns what is given to it into a string.
**`int()`** is a function that turns what is given to it into an integer.
**`float()`** is a function that turns what is given to it into a float.

So to turn the string "4" into the integer 4 we need to do this `int("4")`,
this is especially useful when dealing with user input since the **input()**
function always gives us a string, even if we want something else.

But what happens when we try `int("fred")`?

`ValueError: invalid literal for int() with base 10: 'fred'`

There is no value of integer for the string "fred", so we get an error.

> Forgetting to cast something or accidentally adding a string to a number are
> quite common mistakes, don't be worried about getting error messages like
> those seen here, understanding error messages is a big part of becoming a good
> programmer.

---
**[Example01 - add_two_numbers_wrong.py](../examples/add_two_numbers_wrong.py)**  
**[Example02 - add_two_numbers.py](../examples/add_two_numbers.py)**  
**[Example03 - parrot.py](../examples/parrot.py)**  
**[Exercise03 - hello_someone.py](../exercises/hello_someone.py)**  

---
**[previous lesson](./Lesson03.md)**  
**[next lesson](./Lesson05.md)**  
