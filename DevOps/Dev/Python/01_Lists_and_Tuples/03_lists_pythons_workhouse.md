You’ve seen how useful they are, but this section deals with what makes them different 
from tuples and strings: lists are mutable—that is, you can change their contents—and 
they have many useful specialized methods.

Basic List Operations: You can perform all the standard sequence operations on lists, such as indexing, slicing, concatenating,
and multiplying. But the interesting thing about lists is that they can be modified.

Changing Lists: Item Assignments :Regular assignment usually looks like this: x = 2. Instead of writing something like that, you use the indexing notation to assign
to a specific, existing position, such as x[1] = 2. 1 represent the place in list.(they start from 0)

Changing Lists: Deleting Elements: Deleting elements from a list is easy, too. You can simply use the 'del' statement.

Assigning to Slices: Slicing is a very powerful feature, and it is made even more powerful by the fact that you can assign to slices.
So you can assign to several positions at once. You may wonder what the big deal is. Couldn’t you just have
assigned to them one at a time? Sure, but when you use slice assignments, you may also replace the slice
with a sequence whose length is different from that of the original. Slice assignments can even be used to
insert elements without replacing any of the original ones.

List Methods: A method is a function that is tightly coupled to some object, be it a list, a number, a string, or whatever. In
general, a method is called like this: object.method(arguments)

*append: The append method is used to append an object to the end of a list.
*clear:The clear method clears the contents of a list, in place.
*copy: The copy method copies a list. Recall that a normal assignment simply binds another name to the same list.
*count: The count method counts the occurrences of an element in a list.
*extend: The extend method allows your original to be extended by the other one. works like concatonation.
*index: The index method is used for searching lists to find the index of the first occurrence of a value.
*insert: The insert method is used to insert an object into a list.
*pop: The pop method removes an element (by default, the last one) from the list and returns it.
*remove: The remove method is used to remove the first occurrence of a value.
*reverse: The reverse method reverses the elements in the list.
*sort: The sort method is used to sort lists in place. Sorting “in place” means changing the original list so its
elements are in sorted order, rather than simply returning a sorted copy of the list.


