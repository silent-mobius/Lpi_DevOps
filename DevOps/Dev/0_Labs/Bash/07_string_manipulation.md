1.
What is wrong with this code (besides the inefficiency noted at the beginning of
the chapter)?
if ! echo ${PATH} |grep -q /usr/games
PATH=$PATH:/usr/games
fi
2. Write a function called to_lower that does the opposite of the to_upper function
in Listing 7-4.
3. Write a function, palindrome, which checks whether its command-line argument
is a palindrome (that is, a word or phrase that is spelled the same backward
and forward). Note that spaces and punctuation are ignored in the test. Exit
successfully if it is a palindrome. Include an option to print a message as well as
set the return code.
4. Write two functions, ltrim and rtrim, which trim characters in the same manner
as trim but from only one side of the string, left and right, respectivel
