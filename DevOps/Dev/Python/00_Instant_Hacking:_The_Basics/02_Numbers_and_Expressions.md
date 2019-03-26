The interactive Python interpreter can be used as a powerful calculator. Try the following:
>>> 2 + 2
This should give you the answer 4. That wasn’t too hard. Well, what about this:

>>> 103291 + 131986
235277

Admittedly, this is pretty standard stuff. (I’ll assume that you’ve used a calculator.
All the usual arithmetic operators work as expected. Division produces decimal numbers,
called floats (or floating-point numbers).
>>> 1 / 2
0.5
>>> 1 / 1
1.0
If you’d rather discard the fractional part and do integer division, you can use a double slash.
>>> 1 // 2
0
>>> 1 // 1
1
>>> 5.0 // 2.4
2.0
In older versions of Python, ordinary division on integers used to work like this double slash. If you’re using
Python 2.x, you can get proper division by adding the following statement to the beginning of your program
(writing full programs is described later) or simply executing it in the interactive interpreter:
>>> from __future__ import division

Another alternative, if you’re running an old Python from the command line, is to supply the command-
line switch -Qnew. There is a more thorough explanation of the __future__ stuff in the section “Back to the
__future__” later in this chapter.
Now you’ve seen the basic arithmetic operators (addition, subtraction, multiplication, and division),
but I’ve left out a close relative of integer division.
>>> 1 % 2
1
This is the remainder (modulus) operator. x % y gives the remainder of x divided by y. In other words, it’s
the part that’s left over when you use integer division. That is, x % y is the same as x - ((x // y) * y).
>>> 10 // 3
3
>>> 10 % 3
1
>>> 9 // 3
3
>>> 9 % 3
0
>>> 2.75 % 0.5
0.25

Here 10 // 3 is 3 because the result is rounded down. But 3 × 3 is 9, so you get a remainder of 1. When you
divide 9 by 3, the result is exactly 3, with no rounding. Therefore, the remainder is 0. This may be useful
if you want to check something “every 10 minutes” as in the recipe earlier in the chapter. You can simply
check whether minute % 10 is 0.

Looking at these examples, it might not be immediately obvious how it works. It’s probably easier to
understand if you look at the companion operation of integer division.
>>> 10 // 3
3
>>> 10 // -3
-4
>>> -10 // 3
-4
>>> -10 // -3
3

Given how the division works, it’s not that hard to understand what the remainder must be. The important
thing to understand about integer division is that it is rounded down, which for negative numbers is away
from zero. That means -10 // 3 is rounded down to -4, not up to -3.
The last operator we’ll look at is the exponentiation (or power) operator.
>>> 2 ** 3
8
>>> -3 ** 2
-9
>>> (-3) ** 2
9
Note that the exponentiation operator binds tighter than the negation (unary minus), so -3**2 is in fact the
same as -(3**2). If you want to calculate (-3)**2, you must say so explicitly.

Hexadecimals Octals and Binary
To conclude this section, I should mention that hexadecimal, octal, and binary numbers are written like this:
>>> 0xAF
175
>>> 010
8
>>> 0b1011010010
722
The first digit in both of these is zero. (If you don’t know what this is all about, you probably don’t need this
quite yet. Just file it away for later use.)

