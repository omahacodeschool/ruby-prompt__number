---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

Ruby uses fixednum AKA integers and floats which are numbers that include a decimal point.


# What are some common operations and comparisons you would perform on numbers?

Ruby can do any basic arithmetic like addition (+), subtraction (-), multiplication (*), division (/), and exponents (**). There's also a modulo operation (%) that will find the remainder of one integer divided by another.
You can find the absolute value of a number with the .abs method and switch an integer to a float with '.to_f or vice versa with .to_i.


# What is the difference between the `+` operation on a number versus on a String?

The addition operation when performed on two or more numbers will find the sum of those numbers. Whereas the '+' operation, when used on two or more strings, will join those strings into one longer string.


# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

It will not. The string "20" is merely a two followed by a zero, not the number twenty. 
Attempting a mathematical operation between two strings, say, "20" + "50" will combine them into another string "2050". Attempting any other mathematical operation will net you an error.
You can multiply a string by another number, but "20" * 3 won't get you 60, instead it will repeat the string three times, ending up with "202020"
To do math with a number in a string, you have to convert that string to a number using the .to_i or .to_f methods like this:

    "20".to_i * 3

Now the VM will know to convert the string "20" into an integer and multiply it by 3, giving you 60.


# What is the purpose of the `times` operation? Is that the same as `*`?

The 'times' operation is used to repeat the same operation several times. 
You start by defining the number of times you want an operation to repeat using an integer and .times. For example: 4.times will repeat the operation four times.
This can be used on do loops or just by putting the operation in curly brackets like this:

    3.times{ 5 - 5 }
    
This tells the VM to do the operation 5-5 thrice, getting 0 each time.
The 'times' operation can be used in conjunction with multiplication or any mathematical operations, but it is not interchangeable with '*'.