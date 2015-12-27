---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

In Ruby there are integers and floats.  An integer is any whole number, i.e. 1, 99, 0, -7.  A float is any number with a decimal, i.e. 1.875, 0.0, -3.33.

# What are some common operations and comparisons you would perform on numbers?

Most common operations would be to: add, subtract, multiply and divide.  The most common comparisons would be less than, greater than, equal to, not equal to,
less than or equal to, and greater than or equal to.

# What is the difference between the `+` operation on a number versus on a String?

When working with numbers '+' will add two numbers together and return thier sum.  When working with strings, '+' will add two strings togeter - i.e. "Hello" + "World" would
return "HelloWorld".

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

No, it would not work.  In order for a mathematical operation to work on a string, the string must first be transformed into an integer using '.to_i'.

# What is the purpose of the `times` operation? Is that the same as `*`?

The '.times'method is not the same as '*'.  While '*' can be used to multiply strings, it will return the result as one long string.  The '.times' method will execute
a command x number of times and will return the result each as its own string.  
