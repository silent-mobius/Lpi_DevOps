Until now we’ve been working (almost) exclusively with expressions, the ingredients of the recipe. But what
about statements—the instructions?
In fact, I’ve cheated. I’ve introduced two types of statements already: the print statement and
assignments. What’s the difference between a statement and an expression? You could think of it like this: an
expression is something, while a statement does something. For example, 2 * 2 is 4, whereas print(2 * 2)
prints 4. The two behave quite similarly, so the difference between them might not be all that clear.
>>> 2 * 2
4
>>> print(2 * 2)
4

As long as you execute this in the interactive interpreter, but that is only because the
interpreter always prints out the values of all expressions. That is not true of Python in general.
Later, you’ll see how to make programs that run without this interactive prompt.
putting an expression such as 2 * 2 in your program won’t do anything interesting. 4 Putting print(2 * 2)
in there, however, will still print out 4 to user.
The difference between statements and expressions is more obvious when dealing with assignments.
Because they are not expressions, they have no values that can be printed out by the interactive interpreter.
>>> x = 3
>>>
You simply get a new prompt immediately. Something has changed, however. We now have a new variable
x, which is now bound to the value 3. To some extent, this is a defining quality of statements in general: they
change things. For example, assignments change variables, and print statements change how your screen looks.
Assignments are probably the most important type of statement in any programming language,
although it may be difficult to understand their importance at the moment. Variables may just seem like temporary
“storage” (like the pots and pans of a cooking recipe), but the real power of variables is that you don’t need to
know what values they hold in order to manipulate them.

