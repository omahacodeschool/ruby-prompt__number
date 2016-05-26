---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

Numbers like whole numbers and decimals are defined as fixnum or float numbers.
For cases involving imaginary or other cases in math, Ruby handles them as seperate
units as part of the fixnums or floats.

# What are some common operations and comparisons you would perform on numbers?

PEMDAS appears to work as normal in Ruby as it would in any other math setting. 
There are some commands that can be put into an equation to return a value with 
or without a decimal.

# What is the difference between the `+` operation on a number versus on a String?

adding strings together will "smoosh" the strings into one string. Adding numbers 
will return the sum.

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

Ruby can turn a string into an integer by using .to_i. Without that command, no
string can be operated with numbers to produce a number.

# What is the purpose of the `times` operation? Is that the same as `*`?

'times' appears to be used in loop coding to specify a number of loops requested.
The * is used as a multiplication operator for numbers in ruby.
