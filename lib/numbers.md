---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

Basically there are two kinds of numbers in Ruby. 
Numbers that do not have a decimal point are INTEGERS, numbers that do have a decimal point 
are floating-point numbers, or FLOATS for short. 
Integers can be further divided into Fixnum and Bignum "classes." I read something that indicated Ruby automatically 
converts a Fixnum to a Bignum when an integer is so big it is outside the range of Fixnum. 
Don't know specifically when this happens and don't know if I will ever encounter it.

(Note to me: Every kind of data in Ruby has a class. A class is a set of properties and functionality, says the Bastards Book.)
 

# What are some common operations and comparisons you would perform on numbers?

OPERATORS
 + addition
-subtraction
*multiply
/divide
** to the power of
%modulo (returns the remainder of a division problem)

Not sure yet when I would use modulo.

OPERATORS - I understand these so I’m not going into much detail. 
 + addition
-subtraction
*multiply
/divide
** to the power of
%modulo (returns the remainder of a division problem)

Not sure yet when I would use modulo.

COMPARISONS
== Asking the program to check whether the stuff on the left equals the stuff on the right. 
If they are equal it is “true” if not it is “false.’

!= I guess I’ll call it “does not equal.” If the left side and right side are not equal it returns a value of true. 
If the left and right side are equal the condition is false.   

< Asking the program to check whether the stuff on the left is less than the stuff on the right. If it is then the condition is true.

The ">" is asking the program to check whether the stuff on the left is greater than the stuff on the right. If so the condition is true. (Note to me: 
the > symbol at the beginning of the line was changing the color of all text that followed. Don't know what it means, but rewriting the sentence fixed it.)

>= Asking the program to check whether the stuff on the left is greater than or equal to
the stuff on the right. If so then the condition is true.

<= Asking the program to check whether the stuff on the left is less than or equal to
the stuff on the right. If so then the condition is true.

<=> This one is new to me. Returns 0 if the left and right are equal. Returns 1 if the left is 
greater than the right. Returns -1 if the left is less than the right.

=== The explanation from Tutorials Point does nothing for me. “Used to test equality within
a when clause of a case statement.” In the puny examples I did on repl.it, == and === returned the same thing.
(Note to me: Need to learn more about case statements after I get the other work done. Spent too much time on this one already.) 

.eql? True if the receiver and argument have the same type and equal value. So camparing value and whether it is an integer or a float.
Example: 1 == 1.0 returns true. But 1.eql?(1.0) would return false. 

.equal? True if the receiver and argument have the same object ID. (Note to me: I guess
I can think of an object ID as a place in memory.In that case the receiver and the argument would have to be exact replicas.) 
So far on repl.it I have not been able to see a distinction between .eql? and .equal? but there must be one. I need to learn
a lot more about classes before I get it, I think. To me, it looks like there a lot of situations in which ==,===,.eql? and .equal? return the same thing.


# What is the difference between the `+` operation on a number versus on a String?

The difference between the + operation on a number vs on a string is the difference 
between combining and adding. "7" + "7" gets you "77" but 7 + 7 gets you 14. 
You can add and multiply strings but you cannot divide or subtract them. Multiply works like "repeat," 
so that "3" * 5 = "33333" but 3 * 5 = 15. 
Note to me: The insider word for combining in this case is "concatenation," which means joining
character strings end to end.
Using repl.it, if I combine "7" + "7" I get the result I expect, but if I multiply "3" * "3" 
I get an error message. Other interesting detail: If I put one of these on line 4 of a program, 
the other on line 5, I return the result for the one on line 5, even if I change the order. Odd but OK at least I know.

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

To do a mathematical operation on a string you have to convert the string to a number. Use .to_i to convert to an integer.
Use .to_f to convert to a float. If it was necessary to do so I guess you could then convert the result back to a string
using .to_s. I did the little program below in repl.it. It returned 20, 4 and "4". I probably waste a lot of lines with 
unnecessary "puts" but I want to see what the program is doing at each step. 

puts "20".to_i
Number = ("20".to_i) 
puts (Number) / 5
Numbera = (Number) / 5
Numbera.to_s

# What is the purpose of the `times` operation? Is that the same as `*`?

The times operation lets the program do a broader scope of repetitive work than just 
multiplication of numbers. It is more of a loop, telling the program to do the same thing
a specified number of times.

In repl.it I did this little program

5.times do 
    puts "Pat Clark is cool."
end

which returns
Pat Clark is cool.
Pat Clark is cool.
Pat Clark is cool.
Pat Clark is cool.
Pat Clark is cool.
5
The "5" is in green and I take that to mean it's like a note that just provides the number of times the operation ran.
I didn't see anything similar in the information about the times operation I found online.

I tried another one that would perform a second operation. 
This returned 2,3,4,5,6 and the 5 again for the number of times the operation was done.
var = 2
5.times do 
    puts var
    var = var + 1
end


