#python lists:
1.
	A.Print the second item in the fruits list.
	B.Change the value from "apple" to "kiwi", in the fruits list.
	C.Use the append method to add "orange" to the fruits list.
	D.Use the insert method to add "lemon" as the second item in the fruits list.
	E.Use the remove method to remove "banana" from the fruits list.
2.
Write a program that reads integers from the user and stores them in a list. Your
program should continue reading values until the user enters 0. Then it should display
all of the values entered by the user (except for the 0) in order from smallest to largest,
with one value appearing on each line. Use either the sort method or the sorted
function to sort the list.

3.
In this exercise, you will create a program that reads words from the user until the
user enters a blank line. After the user enters a blank line your program should dis-
play each word entered by the user exactly once. The words should be displayed in
the same order that they were entered. For example, if the user enters:
	first
	second
	first
	third
	second
then your program should display:
	first
	second
	third

4. Do Not Try Before Learning Functions !!!
NEED TO CHANGE THE EXERCISE!!!

5. A sublist is a list that makes up part of a larger list. A sublist may be a list containing
a single element, multiple elements, or even no elements at all. For example, [1],
[2], [3] and [4] are all sublists of [1, 2, 3, 4]. The list [2, 3] is also a sublist of [1, 2, 3, 4], but 
[2, 4] is not a sublist [1, 2, 3, 4] because the elements 2 and 4 are not adjacent in the longer list.
The empty list is a sublist of any list. As a result, [] is a sublist of [1, 2, 3, 4]. A list is a sublist of itself,
meaning that [1, 2, 3, 4] is also a sublist of [1, 2, 3, 4]. In this exercise you will create a function, isSublist, 
that determines whether or not one list is a sublist of another. Your function should take two lists, larger
and smaller, as its only parameters. It should return True if and only if smaller
is a sublist of larger. Write a main program that demonstrates your function.

6.
In order to win the top prize in a particular lottery, one must match all 6 numbers
on his or her ticket to the 6 numbers between 1 and 49 that are drawn by the lottery
organizer. Write a program that generates a random selection of 6 numbers for a
lottery ticket. Ensure that the 6 numbers selected do not contain any duplicates.
Display the numbers in ascending order.

7.
Using the definition of a sublist from Exercise 5, write a function that returns a list
containing every possible sublist of a list. For example, the sublists of [1, 2, 3]
are [], [1], [2], [3], [1, 2], [2, 3] and [1, 2, 3]. Note that your func-
tion will always return a list containing at least the empty list because the empty list
is a sublist of every list. Include a main program that demonstrate your function by
displaying all of the sublists of several different lists.
