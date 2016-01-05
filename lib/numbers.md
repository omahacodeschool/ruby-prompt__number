---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

The two basic kinds of numbers in Ruby are integers (whole numbers) and floats (numbers with decimal points).

# What are some common operations and comparisons you would perform on numbers?

Some common operators would be addition '+', subtraction '-', multiplication '*', division '/', exponentiation '**', and modulo '%'.

# What is the difference between the `+` operation on a number versus on a String?

A '+' will combine the contents of strings added together.  For example, "2" + "7" => "27"
A '+' with numbers will perform the addition operation.  For example, 2 + 7 => 9

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

Some mathematical operations can be performed on strings, some can not.  
Strings can be added to other strings, i.e. "20" + "3" => "203".  Here we are simply adding the contents of the strings.
Strings can be multiplied by a number, i.e. "20" * 3 => "202020". Here we are telling Ruby to add the contents of the string "20" + "20" + "20".
Note: for this question the string must come first, i.e. 3 * "20" results in an error because we can not multiply a number by a string.
All other mathematical operations with respect to strings will result in an error because they do not follow any logic.

# What is the purpose of the `times` operation? Is that the same as `*`?

The 'times' operation is a method used to repeat an instruction a set number of times.
The 'times' operation is not the same as '*' operation, it is only an a mathematical operation.
