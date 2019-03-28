Sequences: A sequence is a data structure in which the elements are numbered
(starting with zero). Examples of sequence types are lists, strings, and tuples.
Of these, lists are mutable (you can change them), whereas tuples and strings
are immutable (once they’re created, they’re fixed). Parts of a sequence can
be accessed through slicing, supplying two indices that indicate the starting
and ending positions of the slice. To change a list, you assign new values to its
positions or use assignment to overwrite entire slices.

Membership: Whether a value can be found in a sequence (or other container)
is checked with the operator in. Using in with strings is a special case—it will let
you look for substrings.

Methods: Some of the built-in types (such as lists and strings but not tuples)
have many useful methods attached to them. These are a bit like functions,
except that they are tied closely to a specific value. Methods are an important
aspect of object-oriented programming, which we look at in Chapter 7.

New Functions :

Function 	Description
len(seq) 	Returns the length of a sequence
list(seq) 	Converts a sequence to a list
max(args) 	Returns the maximum of a sequence or set of arguments
min(args) 	Returns the minimum of a sequence or set of arguments
reversed(seq) 	Lets you iterate over a sequence in reverse
sorted(seq)	Returns a sorted list of the elements of seq
tuple(seq) 	Converts a sequence to a tuple
