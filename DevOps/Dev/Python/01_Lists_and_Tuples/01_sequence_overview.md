Python has several built-in types of sequences. We'll concentrates on two of the most common ones:
lists and tuples. Strings are another important type, which we'll discuss later.
The main difference between lists and tuples is that you can change a list, but you can’t change a tuple.
This means a list might be useful if you need to add elements as you go along, while a tuple can be useful if,
for some reason, you can’t allow the sequence to change. Reasons for the latter are usually rather technical,
having to do with how things work internally in Python. That’s why you may see built-in functions returning
tuples. For your own programs, chances are you can use lists instead of tuples in almost all circumstances.
