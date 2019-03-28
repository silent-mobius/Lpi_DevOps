Tuples are sequences, just like lists. The only difference is that tuples can’t be changed.
The tuple syntax is simple—if you separate some values with commas, you automatically have a tuple.
The empty tuple is written as two parentheses containing nothing. So, you may wonder how to write
a tuple containing a single value. This is a bit peculiar—you have to include a comma,
even though there is only one value.
The tuple function works in pretty much the same way as list: it takes one sequence argument and
converts it to a tuple. 5 If the argument is already a tuple, it is returned unchanged.
As you may have gathered, tuples aren’t very complicated—and there isn’t really much you can do with
them except create them and access their elements, and you do this the same as with other sequences.
Slices of a tuple are also tuples, just as list slices are themselves lists.
There are two important reasons why you need to know about tuples.
	* They can be used as keys in mappings (and members of sets); lists can’t be used this
	way. You’ll learn more mappings in Chapter 4.
	* They are returned by some built-in functions and methods, which means that you
	have to deal with them. As long as you don’t try to change them, “dealing” with them
	most often means treating them just like lists (unless you need methods such as
	index and count, which tuples don’t have).
In general, lists will probably be adequate for your sequencing needs.
