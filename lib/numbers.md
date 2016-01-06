---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

In ruby, there are Fixnum and Float numbers. Fixnum numbers are basically integers, whole numbers, numbers like 5, 23, -9, etc... Float numbers 
are numbers that contain decimals, such as 3.14, 98.6, 45.5, and so on. 

# What are some common operations and comparisons you would perform on numbers?

The operations in ruby are very similar to that of regular math operators that most of us are familiar with from school. ("+" for addition, "-" for subtraction, 
"*" for multiplication, "/" for division, "**" for exponential/"to the power of." More uncommon to non-programmers would be the modulo ("%'), which finds he remainder of given numbers.

Most of the common comparisons should be familiar to most people. For instance: ">" and "<" check to see if the number on the left is greater or lesser than the number on the right, "==" checks for equality while "!=" checks
for inequality. In addition to this, ">=" and <"= check to see if the number on the left is greater than or equal to (or less than or equality to) the number on the right.

# What is the difference between the `+` operation on a number versus on a String?

When using the "+" operation with numbers, the results are what we'd expect: it serves as the addition operation and adds numbers together. However, when using the "+" operation
with strings, no actual math is performed. Instead, the strings on either side of the "+" operator would be combined, or "concatenated."
A simple example would be the following:
"Hello" + "world" would give us a new string: "Hello world"

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

If left alone, we would not be able to perform mathematical operationis on numbers that are strings. That said, Ruby has ways of allowing us to take numbers in strings 
and convert them to numbers. We can use the following methods to convert "20" into 20 so that mathematical opersations could then be used.
If we wanted to convert "20" to an integer, we could do this by calling the "to_i" method (it would look like this: "20".to_i). So, for instance, if 
we had the following situation:
"20" + 45
We would normally not be able to perform any actual math here. But, if we added the to_i method as follows:
"20".to_i + 45
We would actually get 65 for our answer!

Another handy method that could be used is "to_f" which would convert a string to a foating number (decimal) intead of a whole number.

# What is the purpose of the `times` operation? Is that the same as `*`?

If we are talking about the ".times" method, this is not the same thing as '*' as it would not multiply numbers for us. Instead, the ".times" method,
is something that performs an action a given number of times. For instance, if we called the ".times" method in the following manner:
5.times { print "Ryan!" }
The result would be:
Ryan!Ryan!Ryan!Ryan!Ryan!

I may be off track on this one. If this is not what you're asking about (I noticed you used the word "operation" and not "method"), I will adjust my
answer accordingly. :-)