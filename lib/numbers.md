---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

Ruby can function on a basic level as a calculator, but the opportunities to continually perform math functions and re-evaluate the value of data is very intriguing. One could use the math functions in Ruby to make countdowns, to keep track of points and declare winners, report statistics on performance in sports, and help you divide pizzas among the office more effectively (modulo is new to me but I can see the possibilities). 
Numbers in Ruby can also get confusing to newcomers, since several functions specific to Ruby will give you different answers to simple math questions than if you had asked your standard calculator.
Integers (also known as fixums) are whole numbers. Floats are numbers that include decimals. Ruby will not give you a decimal unless you ask for one (3/2 is 1). Numbers can also exist in strings, but then they are the word that represents the number, and not the value of that number. For example, adding with '+' on a fixum will result in mathematical addition (2+5=7) while '+' on a string will put the strings next to each other (2.to_s + 5.to_s = 25). Similarly, 20.to_s is not a number, so math won't work on it the way you expect it to--20.to_s * 2 is 2020, not 40. If you want to have math work in the traditional way, you'll need to convert the string back into an integer, by using .to_i. If you are looking to multiply as a mathematical function, you’ll want to use ‘*’ on your integers--the .times operation lets you repeat yourself (and your code) but is not, technically, math.



