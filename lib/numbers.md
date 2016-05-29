---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

There are two different kinds of numbers, fixnum and float. Fixnum are also called integers, whole numbers without a decimal point.  Float are decimal-ed numbers, specific numbers not whole.

# What are some common operations and comparisons you would perform on numbers?

Well, most of the basic functions that are found in arithmatic can be performed on numbers.  That would include addition, subtraction, multiplication and division.  There is also a way, in the case of division, to get the remainder of two numbers.  This is called the modulo, and uses the % operation.  Now, in the case of all of these things, it really matters whether one uses an integer or a float.  If integers are used, an integer will be returned, and there won't be an exact decimal-point-type answer that some people might be required for exact calculations.  That is why float numbers can be more informative. 
Numbers can also be compared.  You can use "is equal to" functions, or == to check if two numbers are equal.  You can look into whether or not numbers are greater than, like 5 > 4, greater than or equal to, formatted as >= , and there are many more that probably don't need much explanation, like less than <, less than or equal to <=, and is not equal to !=.

# What is the difference between the `+` operation on a number versus on a String?

The + operations on a number will add the two (or more) numbers on the opposite sides of the + sign, whereas in the case of a string, the + joins the two halves of the string together.  So, in the case of a number, 3 + 4.05 will give 7.05, while "I am a " + "positive person." will result in "I am a positive person."

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

You cannot perform a mathematical operation on "20" because that sequence is not an integer or a float.  It is a string, and thus is not a number.  It is a sequence of characters that represents something.  To make it an integer, you would have to remove the quoation mark, and to make it a float, I would remove the quotation marks and add a decimal point.  Then normal mathematical operators would work on it!  But it would no longer be a string.

# What is the purpose of the `times` operation? Is that the same as `*`?

The times operation does not work as a multiplication operation, which is what '*' does.  The times operation, when combined with a number, gives the command to perform a certain operation or set of code a certain number of times.   So, writing 4.times do |x|, it will do x 4 times.
