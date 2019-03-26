You’ve seen that you can write programs with variables without knowing their values. Of course, the
interpreter must know the values eventually. So how can it be that we don’t? The interpreter knows only
what we tell it, right? Not necessarily.
You may have written a program, and someone else may use it. You cannot predict what values users
will supply to the program. Let’s take a look at the useful function input.
>>> input('the meaning of life: ')
the meaning of life: 42
'42'

What happens here is that the first line (input(...)) is executed in the interactive interpreter. It prints out
the string "The meaning of life: " as a new prompt. I type 42 and press Enter. The resulting value of
input is that very number (as a piece of text, or string), which is automatically printed out in the last line.

To spice things up a bit, I’ll give you a sneak peek of something you aren’t really supposed to learn yet: the if statement.
The if statement lets you perform an action (another statement) if a given condition is true. One type of condition is an equality test, 
using the equality operator, ==. Yes, it’s a double equality sign.

You put this condition after the word if and then separate it from the following statement with a colon.
>>> if 1 == 2: print('One equals two')
...
>>> if 1 == 1: print('One equals one')
...
One equals one

Nothing happens when the condition is false. When it is true, however, the statement following the colon is executed


