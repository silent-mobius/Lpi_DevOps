You may think of modules as extensions that can be imported into Python to expand its capabilities. You
import modules with a special command called (naturally enough) import. The function mentioned in the
previous section, floor, is in a module called math.
>>> import math
>>> math.floor(32.9)
32
Notice how this works: we import a module with import and then use the functions from that module by
writing module.function. For this operation in particular, you could actually just convert the number into an
integer, like I did earlier, with the results from input.
>>> int(32.9)
32

If you are sure that you won’t import more than one function with a given name (from different modules),
you might not want to write the module name each time you call the function. Then you can use a variant of
the import command.
>>> from math import sqrt
>>> sqrt(9)
3.0
After using the from module import function, you can use the function without its module prefix.

cmath and Complex Numbers
The sqrt function is used to calculate the square root of a number. Let’s see what happens if we supply it
with a negative number:

>>> from math import sqrt
>>> sqrt(-1)
Traceback (most recent call last):    
...
ValueError: math domain error
or, on some platforms:
>>> sqrt(-1)
nan

Note : nan is simply a special value meaning “not a number.” it is not a batman call out theme song.

Back to the __future__
It has been rumored that Guido van Rossum (Python’s creator) has a time machine—on more than one
occasion when people have requested features in the language, they have found that the features were already
implemented. Of course, we aren’t all allowed into this time machine, but Guido has been kind enough to
build a part of it into Python, in the form of the magic module __future__. From it, we can import features
that will be standard in Python in the future but that aren’t part of the language yet.
