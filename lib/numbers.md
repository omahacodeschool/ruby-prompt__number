---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?
There are two primary types of numbers: 'fixnum', which are integers (whole numbers without decimal points), and 'float', which is a number with a decimal point.


# What are some common operations and comparisons you would perform on numbers?

operations: + (addition), - (subtraction), * (multiplication), / (division), ** (exponents), % (modulo)
comparisons: < (less than), > (greater than), == (equal to)

# What is the difference between the `+` operation on a number versus on a String?

On a string, the + operation will combine strings, returning a composite of the strings entered.
On a number, the + operation will perform addition, returning the resulting calculation.

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

It will not work. It is not possible to perform mathematical operations on strings. 
To perform a mathematical operation, the string would first need to be converted to either a fixnum (using .to_i) or a float (using .to_f).


# What is the purpose of the `times` operation? Is that the same as `*`?
The times method simply allows us to repeat a specified block of code the prescribed number of "times".

This is very different than the * operation.
Used with the number classes, the * operation performs multiplication.
Used with strings, * will repeat the preceding string the number of times indicated after the *.
