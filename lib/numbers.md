---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

Fixnum for integers and Float for decimal numbers.

# What are some common operations and comparisons you would perform on numbers?

+, -, *, /, ** and % for addition, substraction, multiplication, division, exponential multiplication and modular division.  The most common comparisons are ==, !=, >, <, >= and <= for equals, does not equal, greater than, less than, greater than or equal to and less than or equal to.

# What is the difference between the `+` operation on a number versus on a String?

The '+' operator produces the sum of two numbers, while it concatenates two strings.

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

It will not work unless you convert it to another data type.  "20".to_i will convert the string to an integer.

# What is the purpose of the `times` operation? Is that the same as `*`?

'times' is a function that can be used on an integer to run a block of code as many times as the integer.
