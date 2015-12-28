---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?
In Ruby, integers are whole numbers, while floats are decimals. 
The number classes in Ruby are as follows: integer, fixnum, bignum, float & rational.

# What are some common operations and comparisons you would perform on numbers?

Some common operators are: addition (+), subtraction (-), multiplication (*), division (/),
to the power of (**), modulo (%)

Comparisons are: ==, !=, <, >, <=, >=, <==>, and ===

# What is the difference between the `+` operation on a number versus on a String?

Using the + operator on an integer will combine the value of each integer to give the user the sum of the 
two integers. For example, 2 + 2 = 4
Using the + operator on a string will combine the two separate strings into a single string.
Therefore, "2" + "2" = "22"

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

"20".to_f 
only use .to_i if you are trying to create counters. 
If you need the values for mathmatical purposes, always convert the string to a float,
allowing for the possibility of a decimal value & thus more accurate equations and results. 

# What is the purpose of the `times` operation? Is that the same as `*`?

The.times operator can iterate the variable the defined number of times. It is not a multiplier like the * operator. For example,
3*5               #=> 15 

while 
    3.times do 5
        print 5
    end           #=> 5, 5, 5,

