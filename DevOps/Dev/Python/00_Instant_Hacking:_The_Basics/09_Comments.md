The hash sign (#) is a bit special in Python. When you put it in your code, everything to the right of it is
ignored (which is why the Python interpreter didn’t choke on the /usr/bin/env stuff used earlier). Here is
an example:
# Print the circumference of the circle:
print(2 * pi * radius)
The first line here is called a comment, which can be useful in making programs easier to understand—
both for other people and for yourself when you come back to old code. It has been said that the first
commandment of programmers is “Thou Shalt Comment” (although some less charitable programmers
swear by the motto “If it was hard to write, it should be hard to read”). Make sure your comments say
significant things and don’t simply restate what is already obvious from the code. Useless, redundant
comments may be worse than none
