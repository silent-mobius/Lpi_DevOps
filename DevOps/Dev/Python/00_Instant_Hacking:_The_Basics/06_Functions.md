In the “Numbers and Expressions” section, I used the exponentiation operator (**) to calculate powers. The
fact is that you can use a function instead, called pow.
>>> 2 ** 3
8
>>> pow(2, 3)
8
A function is like a little program that you can use to perform a specific action. Python has a lot of functions
that can do many wonderful things. In fact, you can make your own functions, too (more about that later);
therefore, we often refer to standard functions such as pow as built-in functions.
Using a function as I did in the preceding example is called calling the function. You supply it with
arguments (in this case, 2 and 3), and it returns a value to you. Because it returns a value, a function call is
simply another type of expression, like the arithmetic expressions discussed earlier in this chapter. 6 In fact, you
can combine function calls and operators to create more complicated expressions

>>> 10 + pow(2, 3 * 5) / 3.0
10932.666666666666

everal built-in functions can be used in numeric expressions like this. For example, abs gives the absolute
value of a number, and round rounds floating-point numbers to the nearest integer.
>>> abs(-10)
10
>>> 2 // 3
0
>>> round(2 / 3)
1.0
Notice the difference between the two last expressions. Integer division always rounds down, whereas round
rounds to the nearest integer, with ties rounded toward the even number. But what if you want to round a
given number down? For example, you might know that a person is 32.9 years old, but you would like to
round that down to 32 because she isn’t really 33 yet. Python has a function for this (called floor)—it just
isn’t available directly.
