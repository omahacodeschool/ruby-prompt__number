---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

In Ruby, there are integers (“fixnum”) which are whole numbers, and there are floats which have decimal points.


# What are some common operations and comparisons you would perform on numbers?

You can do all the familiar math operations on integers/floats in Ruby (add, subtract, multiply, divide, etc.). You can also use methods to do things like convert floats to integers and vice versa.


# What is the difference between the `+` operation on a number versus on a String?

If you add (+) two strings together, you’ll basically get the two strings mashed together. So if they’re words, say, “cat” and “dog,” adding those two strings will give you “catdog.” If your strings are digits like “4” and “5,” adding them will give you “45.” However, if they are numbers and not strings, traditional math rules apply (4 + 5 = 9, not 45). 


# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

Sometimes it will work. You can multiply a string. If you took your string “20” and multiplied it by four (“20” * 4) you would get “20202020.” But you couldn’t multiply the number 4 by your string “20” (4 * “20”). That will give you an error since “20” as a string is the same as any other group of characters acting as a string and you couldn’t get an answer for 4 multiplied by the string “cat,” for example. Division won’t work, either. As far as I can tell, you can only add and multiply strings. There’s always the option to convert string digits to integers (.to_i) and perform mathematical operations on them, though. 

Ah, right. I should have said “.to_f” is an option as well. If you use .to_i on a string “20” and divided it by 3, it’s going to give you a rounded-down answer: 6. If you want an accurate answer, you’d want to convert to a float.


# What is the purpose of the `times` operation? Is that the same as `*`?

No, they’re different. The * command will perform a mathematical multiplication on a string or number, but the .times operation will do something a specified number of times within a block, which I think you could refer to as a finite loop. 

