#python sets

	A.Check if "apple" is present in the fruits set.
	B.Use the add method to add "orange" to the fruits set.
	C.Use the correct method to add multiple items (more_fruits) to the fruits set.
	D.Use the remove method to remove "banana" from the fruits set.
	E.Use the discard method to remove "banana" from the fruits set.





A.
fruits = {"apple", "banana", "cherry"}
if ("apple" in fruits):
  print("Yes, apple is a fruit!")

B.
fruits = {"apple", "banana", "cherry"}
fruits.add("orange")

C.
fruits = {"apple", "banana", "cherry"}
more_fruits = ["orange", "mango", "grapes"]
fruits.update(more_fruits)

D.
fruits = {"apple", "banana", "cherry"}
fruits.remove("banana")

E.
fruits = {"apple", "banana", "cherry"}
fruits.discard("banana")
