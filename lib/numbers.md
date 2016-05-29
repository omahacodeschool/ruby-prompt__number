---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

There are two types of numbers in Ruby - fixnums and floats. Fixnums are integer values with no decimal point. Floats, or floating point numbers, are numbers which do contain decimal points. The size of floats can be controlled to optimize memory use.

# What are some common operations and comparisons you would perform on numbers?

Any basic mathematical operations can be performed on numbers. Ruby includes basic methods for addition, subtraction, multiplication, division (and division with remainders), and exponentiation. It includes operators for comparing numbers, such as greater/less than, greater/less than or equal to, and equals/does not equal. Ruby also contains logical operators such as 'and', 'or', and 'not' for checking the truth of an expression. Finally, Ruby includes assignment operators to assign values, including numerical values, to variables, or to perform a mathematical function on a value and then store the resulting value to a variable. These are all common operations that can be performed using numbers.

# What is the difference between the `+` operation on a number versus on a String?

The '+' operator will perform addition on a number and will perform string concatenation on a string, joining a second string onto the end of a string and outputting a new single string.

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

Some mathematical operations can be performed on a string. However, they will only manipulate the string but will not give a mathematical result. For example, multiplying "20" by 5 would result in "2020202020". But the string "20" can be converted to an integer using the .to_i method, or to a float using the .to_f method. The mathematical operation can then be performed on the number. The result can be converted back to a string using the .to_s method.

# What is the purpose of the `times` operation? Is that the same as `*`?

The 'times' operation is similar to the '*' only in that it repeats a method a certain number of times. Whereas '*' would repeat the addition method a set number of times, 'times' repeats a method a certain number of times. For example, '5*3' is equivalent to '5+5+5', and the result of 3.times do print "Hello" end is equivalent to the result of print "Hello" print "Hello" print "Hello".