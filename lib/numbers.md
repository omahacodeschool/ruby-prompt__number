---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

In Ruby, the number types are integers and floats. Integers are whole numbers where floats are numbers with a decimal point.

# What are some common operations and comparisons you would perform on numbers?

Some common operations include '+' (addition), '-' (subtraction), '*' (multiplication), '/' (division), '**' (exponentiation). and '%' (modulus). Comparisons used in Ruby include '>' (greater than), '<' (less than), '>=' (greater than or equal to), '<=' (less than or equal to), '==' (equal to), '!=' (different from).

# What is the difference between the `+` operation on a number versus on a String?

Using '+' on a set of numbers will perform addition (e.g. 1 + 1 = 2), where this operation used on a set of strings will combine the strings (e.g. 'This is' + ' a string.' becomes: 'This is a string.')

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

No, you would first need to convert the string to either an integer or float with the .to_i or .to_f methods.

# What is the purpose of the `times` operation? Is that the same as `*`?

The 'times' operation tells Ruby to run a program a specified ammount of times (e.g. 4.times do puts "z" end, will put the string "z" 4 times). It's not the same as the '*' (multiplication) method but acts similar to simple multiplication in a sense.
