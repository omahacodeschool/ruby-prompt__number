---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

Integers (aka Fixnum) are whole numbers. 
When used in mathematical operations they will always return whole numbers.

    15/2 = 7
    
Floats are numbers with a decimal point. Floats great than -1 and less than 1 require a zero in front of the decimal point. 
When used in mathematical operations they will always return floats.

    15/2.0 = 7.5

# What are some common operations and comparisons you would perform on numbers?

+ (addition)
+= (combined operator....
all of the combined operators perform an arithmetic operation on the variable before assigning it a new value
example:
    
    x=1
    x+=2  (translation: x=x+2)
    now x=3
)

- (subtraction)
-= (combined operator)
* (multiplication)
*= (combined operator)
/ (division)
/= (combined operator)
** (exponent)
% (modulus- Divides left # by right # and returns remainder)
.to_i (converts float to integer)
.to_f (converts integer to float)
== (asks if true)
!= (asks if false)
> (asks if greater than)
< (asks if less than)
>= (asks if greater than or equal to)
<= (asks if less than or equal to)
<=> (combined comparison...if both numbers are same it returns 0, if first number is greater than second number it returns 1, and if the opposite is true it returns -1)


# What is the difference between the `+` operation on a number versus on a String?

Using the '+' on two numbers will execute the mathematical operation of addition while using it on two strings will combine the strings to form one string.

    1 + 1 = 2
vs.

    "1" + "1" = "11"


# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

No, it won't work as a mathematical operation because your computer won't recognize "20" as a number. 
It is only a collection of characters to your computer. 
You will need to convert the string to an integer and also possibly a float

x="20"
x.to_i.to_f/3

will give you the quotient

# What is the purpose of the `times` operation? Is that the same as `*`?

x.times will do an operation x times, while '*' is a multiplication operator.

    3.times do
      puts "ha"
    end
    ha
    ha
    ha
vs.

    2 * 3.0 = 6.0