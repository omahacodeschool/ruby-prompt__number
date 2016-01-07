---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

The main types of numbers in Ruby are Fixnums (integers), and Floats (decimals). Numbers can also be Strings in Ruby if indicated by quotation marks.

# What are some common operations and comparisons you would perform on numbers?

You can use all the basic math operators to perform operations on numbers, including addition, substraction, division, multiplication, and so forth. 

You can also determine if a number is less than, greater than, or equal to another number.

# What is the difference between the `+` operation on a number versus on a String?

The + operator in Ruby can be used to concatenate Strings, or combine Strings together into a single String. So you could use + to create the String "I love elephants" by putting: puts "I" + "love" + "elephants".
Using the + on Fixnums or Floats in Ruby will return the sum of those numbers.

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

No, you cannot perform a mathematical operation on a String without first converting that String into a Fixnum or Float number using the method .to_f or .to_i.
So, instead of "20"/2, you would put "20".to_i/2 to run a mathmatical operation. You can then subsequently convert the answer back into a String if you desire.

# What is the purpose of the `times` operation? Is that the same as `*`?

The 'times' operation is an integer method where you can repeat something a given number of times, including a String or a variable. So I could use 'times' to tell my program to output "I love elephants" a given number of times.
*, on the other hand, is used for multiplication, and when used on Fixnums or Floats will multiply numbers together and return a product.
