---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

By the look of it, there are two number types or classes in Ruby.  There are fixnum(read "integers") and float(read "decimal") numbers.

# What are some common operations and comparisons you would perform on numbers?

You've got all the basic math operations at your disposal.  '+'(addition), '-'(subtraction), '*'(multiplication), '/'(division), '**'(exponentiation or raising numbers to the power of...), and '%'(modulo, this returns the remainder when you do division, so 5 % 2 should give you 1).  There are also a number of methods you can apply to numbers using dot syntax.  For example, you've got things like the abs method which gives you the absolute value of a number.  So you could say something like -2.abs and have it return 2.  Finally, you've got booleans that allow you to perform comparisons between numbers.  Booleans are things like '==', '>', '<', '>=', '<='.  Those are "equals", "greater than", "less than", "greater than or equal to", and "less than or equal to" respectively, and they come in handy when things start getting logical. 

# What is the difference between the `+` operation on a number versus on a String?

With numbers, the '+' operation does what you'd expect it to, it adds one number to another.  With a string, it concatenates one string to another.  So, if you had two strings that you wanted to attach to one another and create a longer string, you'd do something like this string_1 = "It was the best of times" string_2 = "it was the worst of times." opening_line = string 1 + "," + string_2 and it should result in "It was the best of times, it was the worst of times."

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

Yes and no.  Some mathematical operations "work" on strings, but not in quite the way you'd expect.  For example, "20" * 2 would repeat the string 20 twice.  So, your output would look something like "2020".  Division seems to spit up an error, as do addition and subtraction.  This sort of makes sense as the only mathematical operation that would make sense with a string of characters would be multiplication.  I can envision multiplying items without mentally having to answer another question.  To wit, I have a pen in my hand.  If I multiply the number of pens by 2 or 3 or what have you, I don't have to then ask "what do you mean you multiplied them?"  If I tried to do the same for any of the other operations, I'd have questions.  If you told me you had a pen and then subtracted 2, I'd immediately ask "two what?" and probably other things besides.  However, 20 is a number and if I want to do mathematical operations on it, there's nothing keeping me from doing that save the fact that the computer views "20" not as a number with all the properties that implies, but rather as a string of characters.  The trick is getting the computer to see the "20" as 20.  To do this you'd use the to_i or to_f methods.  The difference between the two being that to_i would convert "20" into the integer 20 and to_f would convert it into 20.0, i.e., making it into a float(float being a reference to the decimal or "floating point"). 

# What is the purpose of the `times` operation? Is that the same as `*`?

The times method has to do with iterating a given bit of code x number of times.  So, you're basically telling the computer "do this this many times".  This is a bit different from the mathematical operator '*'.  As mentioned in the answer to the previous question, using that operator on a string will repeat that string however many times you tell it to.  While this might very loosely be classed as a sort of iteration, it's very limited.  Additionally, I haven't seen any indications that were you would be able to use it to iterate a block of code some integral number of times.  Thus, the times method is for controling the flow of the program and the '*' operator is for doing math.
