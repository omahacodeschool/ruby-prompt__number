---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

Integers, or whole numbers, and floats, or decimals.

# What are some common operations and comparisons you would perform on numbers?

You can use operations such as +, -, *, /, **, %. Also compare numbers with >, <, =, <=, >=.

# What is the difference between the `+` operation on a number versus on a String?

The '+' operation with numbers will add the numbers togethers to form a total (1+1=2) while with strings it will bring the to strings together, side by side, ('abc' + 'def' = 'abcdef')

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

It will not work because strings are not treated as numbers. You would have to use the .to_i method to take the string and turn it to an integer first.

# What is the purpose of the `times` operation? Is that the same as `*`?

times is use to tell a function how many times to run, while '*' only performs multiplication for numbers.
