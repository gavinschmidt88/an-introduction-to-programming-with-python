# Lesson2

## Variables

A variable is a way to store a refrence to a particular value.
If we say `my_favourite_number = 6` we have created a variable, so everytime we
mention `my_favourite_number` we are actually talking about the number `6`.

## Creating variables in Python

To create a variable in python we just need to supply a name and a value,
like this:
```python
my_variable = "my value"
```
This is an __assignment statement__, It's as simple as that!

## Data types

So what things exactly can we store a refrence to?

* __Strings__
  A String is a sequence of letters or characters such as "hello world", we
  enclose strings in quotations to make it clear to python that we are talking
  about the string hello world rather than something else with the same name.

  > Strings in quotation marks are often refered to as string literals (we 
  > literally mean "hello world").

* __integers__
  An integer is a whole number, like 3, 0, or -247.

* __floats__
  A float (or floating point decimal) is a decimal number, like 3.14, -126.123,
  or 0.0, notice that a float may have the same value as an integer but may not
  always be considered the same thing (python tends to hide this problem).

* __and more...__
  Refrences can be made to things called functions, and objects, but lets look
  at those another time.

## Variable names

There are some rules for naming variables in python:

1. A variable name can only begin with a letter or underscore "_".
2. A variable may contain letters, numbers, or underscores.
3. Variable names are __case sensitive__.
4. A variable cannot have the same name as one of pythons keywords.
  Keywords are special words reserved by python, and include:
  | and        | del        | from       | not        | while      |     
  | as         | elif       | global     | or         | with       |      
  | assert     | else       | if         | pass       | yield      |    
  | break      | except     | import     | print      |            |  
  | class      | exec       | in         | raise      |            |  
  | continue   | finally    | is         | return     |            | 
  | def        | for        | lambda     | try        |            |

> although it's not a rule variables should have names that refect what they are
> for.

## Hello variable

Let's have a go at printing some variables.

```python
my_first_variable="just a simple string"

print(my_first_variable)
```
Since we are refering to the variable `my_first_variable` not the litteral
string "my_first_variable", we dont use quotes when using print.

---
Exercise002 - variable_questions.md