---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

Integers (whole numbers) and floating-point numbers (decimal points)

# What are some common operations and comparisons you would perform on numbers?

Addition, subtraction, multiplication, division, greater than, less than ...

# What is the difference between the `+` operation on a number versus on a String?

The '+' operation works as a sum for numbers.  For Strings it simply adds the text to the previous text.

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

No it wont work. Ruby doesn't know how to add a number to a string.  You have to tell Ruby that the string is an actual number with the .to_i operation first. So it would be '20' .to_i / 4

# What is the purpose of the `times` operation? Is that the same as `*`?

The times operation runs a line of code multiple times.  4.times do  puts cat end would give you cat cat cat cat.  the * operation multiplies numbers. 5*4 would give you 20.
