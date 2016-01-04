---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

integers (whole numbers), floats (numbers containing decimal points)

# What are some common operations and comparisons you would perform on numbers?

+, *, /, >, <, <=, >=, =, ==, 

# What is the difference between the `+` operation on a number versus on a String?

With numbers the + opertor will return the total of the two numbers.

1+2 returns 3

With strings the + operator will return the strings joined together.

"These " + "strings will be joined together" returns "These strings will be joined together"

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? 

It wont work if you leave "20" as a string. Simply trying to multiply "20"*5 returns 2020202020 (the string "20" five times).
You need to run the .to_i method on the string first so it treats the string as an interger. "20".to_i*5  returns 100

If you are seeking the exact quotient of "20" divide by three you'd need to trun the string into a float us the .to_f method and then / 3.

"20".to_f / 3

# What is the purpose of the `times` operation? Is that the same as `*`?

* is the operator for multiplication

5*2 returns 10

'times' is an operator that performs an action a given number of times

3.times do
    puts "hi"
end

returns

hi
hi
hi




