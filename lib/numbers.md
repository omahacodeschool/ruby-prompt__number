---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

The two basic kinds of numbers in Ruby are:
1) floats (numbers with a decimal point, such as 14.7)
2) integers (whole numbers, or numbers without a decimal point, such as 360)


# What are some common operations and comparisons you would perform on numbers?

Common operations performed on numbers are the following:
1) Addition (+)
2) Subtraction (-)
3) Multiplication (*)
4) Division (/)
5) Exponent (**) 
SIDE NOTE: "Exponent" is probably not as common as the previous four operations, but since I found it, figured I'd include it.


# What is the difference between the `+` operation on a number versus on a String?

The plus sign (+) operation between two strings would result in concatenation of the values. For example, if I were to submit the following code

puts '5' + '2'

my program would return the string "52". However, if I were to try to submit either the 5 or the 2 as a string, the compiler would return an error since the values are not of the same datatype (see example below, taking into consideration that Ruby reads the code from right to left):

Example #1
(my code) puts '5' + 2
(error msg) no implicit conversion of Fixnum into String

Example #2
(my code) puts '5' + 2
(error msg) String can't be coerced into Fixnum



# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

It will not work since the string datatype would not be read as a number by the program compiler in its current state. You'd have to convert it into an integer using the "to_i" in order for the compiler to read your equation as a number:

Working Code:
(my code) puts 5*'20'.to_i
(result) 100

Non-working Code:
(my code) puts 5*'20'
(error msg) String can't be coerced into Fixnum



# What is the purpose of the `times` operation? Is that the same as `*`?

The times operation is a method that instructs the program to repeat, or loop, through a series of steps a specific number of times. The times operation in Ruby would replace a "for loop" in other languages.
