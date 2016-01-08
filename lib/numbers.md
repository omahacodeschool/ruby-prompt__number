---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

In Ruby there are Fixnum (or Integer) numbers as well as Float numbers. 

# What are some common operations and comparisons you would perform on numbers?

Common operations you would perform on numbers would include your usual PEMDAS math operations as well as the modulus operation. Comparisons would include "greater than >", "less than <" as well "equals to =="

# What is the difference between the `+` operation on a number versus on a String?

With the "+" operation on a number, ruby interprets that as the addition operation. So "2+4" ruby would return "6". However, with Strings the "+" operation servers as a concatenator, thus literally appending one string to the other.

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

A mathematical operation can be used on a string, however, not with the expected results. For example the string "20" multiplied by 5 would return 2020202020. In order to make the previous example return the expected answer, you would need to convert the string to an integer using the ".to_i" command.

# What is the purpose of the `times` operation? Is that the same as `*`?

From what I've gathered from my research, the "times" command can be used as alternative to looping and can be used to repeat a specific operation multiple times. It is not the same as the "*" operation which is multiplication. 
