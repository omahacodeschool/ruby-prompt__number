---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

Fixnum : An integer (a whole number with no decimal point).
Float : A number with a decimal. eg: 3.14


# What are some common operations and comparisons you would perform on numbers?

.abs : Absolute value (numerical value, regardless of whether it is positive or negative.
% : Modulo, or the remainder of a division operation.
** : Exponent
/ : Division
+ : Addition
- : Subtraction
* : Multiplication

# What is the difference between the `+` operation on a number versus on a String?

Used with a number, the '+' operation will perform additive math. Used with a String, the '+' operation will merely place the strings next to one another.

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

No, you must convert the string to an integer before performing math operations on it. 
Use:
'20'.to_i

# What is the purpose of the `times` operation? Is that the same as `*`?

The purpose of the 'times' operation is to create a looping process. An example would be:

4.times do
puts 'Echo!'
end

Echo
Echo
Echo
Echo

Using '*', we can use:

'Echo' * 4

EchoEchoEchoEcho

The difference (which my examples above do not illustrate):
Using 'times', we can repeat any process.
Using '*', we can only multiply numbers and repeat strings.
