---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

Float (decimal numbers) and Fixnum (integers)

# What are some common operations and comparisons you would perform on numbers?

Operations: addition (+), subtraction (-), multiplication (*), to the power,
(**), division (/),modulo (%)

Comparisons : greater than (>), greater than or equal to (>=), less than (<), 
              less than or equal to (<=)

# What is the difference between the `+` operation on a number versus on a String?

the '+' operation on strings will "add" the strings together by combining them, the output is still a string
     example: "23" + "dog"   #=>   "23dog"
the '+' operation on numbers will add the numbers together and output the sum
    example: 21 + 15    #=> 36

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

Since "20" is a string (-) and (/) operations will not work on it at all, if you try either of these
it will produce an error. (+) will work if another string is being "added" to it, otherwise
it causes an error because you cannot add a string and a number together. However, (*) will work, 
but the output will still be a string, not a number.
    Examples:  "20" * 3     #=> "202020"
                "20" + 2    #=> error
                "20" + "2"  #=> "202"
 
To be able to perform a mathematical operation you would have to first convert the 
string to a number: "20".to_i   (converts 20 to an integer)
Once converted to a number, mathematical operations, such as division or multiplication, will work.

# What is the purpose of the `times` operation? Is that the same as `*`?

'times' is a method that allows a task to be done a given number of times. 
It can replace some for loops.

example:
2.times {|i| puts i}  #=> 0
                          1

'times' and '*' are not the same thing. 
'*' is a operation used for multiplacation of numbers or strings
