---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

Ruby has integers and floating-point numbers, which include decimals.  Performing math on integers will get integer results.  If at least one number in the expression is a float, the result will be a float.

# What are some common operations and comparisons you would perform on numbers?

You can do basic arithmetic operations: addition, subtraction, multiplication, division, exponents.  You can also compare whether numbers are equal or not, or whether one number is greater than (optionally "or equal to") or less than (also optionally "or equal to") the other.

# What is the difference between the `+` operation on a number versus on a String?

With numbers, that operator performs addition.  With strings, it concatenates, or joins them together.

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

Trying to do this will result in an error or, in the case of multiplication, an unexpected result.  You can use the "to_i" method on the string to convert the 20 to an integer, or "to_f" to create a float, and then perform the arithmetic.

# What is the purpose of the `times` operation? Is that the same as `*`?

That is an iterator, and does not perform arithmetic.  By using, for example, "3.times { }" you can repeat a block of code three times.