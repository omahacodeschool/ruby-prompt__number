---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

The two kinds of numbers in Ruby are fixnum(integers with no decimal) or floats(decimal numbers). Numbers can also be displayed as strings but are technically still strings.

# What are some common operations and comparisons you would perform on numbers?

Common operators and comparisons performed on numbers are +, -, *, <, >, %, /, <=, >=, and ==.

# What is the difference between the `+` operation on a number versus on a String?

When the + operator is used on a number Ruby adds the two(or more) numbers together and returns the total. The + operator pushes strings together rather than adding the length of each string to return a fixnum.

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

When you use the * operator on a string and multiply it by a number Ruby will print out the string that number of times. Besides addition, any other mathmatical operation will not work for two strings. If a string is a number, such as "20", you would first need to convert it to a type of number using .to_i or .to_f. Then you could perform mathmatical functions with the converted string.

# What is the purpose of the `times` operation? Is that the same as `*`?

The 'times' method runs a block of code a certian amount of times. It is similar to using * on strings but (5*5) would return 25 not 55555. Using the * operator to return a string a certian amount of times works great but so will the .times method.
