#python dictionaries
1.
	A.create a discrionary  that describes car, car's model and year of production.
		Use the get method to print the value of the "model" key of the car dictionary.
	B.Change the "year" value from 1964 to 2018.
	C.Add the key/value pair "color" : "red" to the car dictionary.
	D.Use the pop method to remove "model" from the car dictionary.
	E.Use the clear method to empty the car dictionary.
2.
Write a function named reverseLookup that finds all of the keys in a dictionary
that map to a specific value. The function will take the dictionary and the value to
search for as its only parameters. It will return a (possibly empty) list of keys from
the dictionary that map to the provided value.
Include a main program that demonstrates the reverseLookup function as part
of your solution to this exercise. Your program should create a dictionary and then
show that the reverseLookup function works correctly when it returns multiple
keys, a single key, and no keys. Ensure that your main program only runs when
the file containing your solution to this exercise has not been imported into another
program.

3.
Morse code is an encoding scheme that uses dashes and dots to represent numbers
and letters. In this exercise, you will write a program that uses a dictionary to store
the mapping from letters and numbers to Morse code. Use a period to represent a dot,
and a hyphen to represent a dash. The mapping from letters and numbers to dashes
and dots is shown in Table at : https://upload.wikimedia.org/wikipedia/commons/b/b5/International_Morse_Code.svg
Your program should read a message from the user. Then it should translate each
letter and number in the message to Morse code, leaving a space between each
sequence of dashes and dots. Your program should ignore any characters that are not
letters or numbers. The Morse code for Hello, World! is shown below:
	
	.... . .-.. .-.. --- .-- --- .-. .-.. -..

4.
Two words are anagrams if they contain all of the same letters, but in a different
order. For example, “evil” and “live” are anagrams because each contains one e, one
i, one l, and one v. Create a program that reads two strings from the user, determines
whether or not they are anagrams, and reports the result.


1.
A.
car =	{
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(car.get("model"))

B.
car =	{
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}

car["year"]=2018

C.
car =	{
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
car["color"]="red"


D.
car =	{
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
car.pop("model")

E.
car =	{
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
car.clear()


2.

def reverse_lookup(data,value):
	keys=[]
	for key in data:
		if data[key] == value:
			keys.append(key)
		
	return keys


def main():
	GermanEnglish={'der': 'the', 'das': 'the', 'booche': 'book', 'shtrasse': 'street'}
	print('the german equivalent for  "the"  are:',reverse_lookup(GermanEnglish, "the"))
	print('Expected : "Der" , "Das"')
	print()
	print('the german equivalent for  "street"  are:',reverse_lookup(GermanEnglish,'street'))
	print('Expected : "shtrasse"')

	
if __name__ == "__main__":
	main()

3.
def lookup(data,value):
    keys=[]
    for k in data:
        if data[k] == value:
            keys.append(k)
    
    keys=''.join(keys)

    return keys


    

def main():
    MorseEnglish={'.---':'a','---...':'b','---.---.':'c','---..':'d','.':'e','..---.':'f','------.':'g','....':'h','..':'i','.---------':'j','---.---':'k','.---..':'l','------':'m','---.':'n','---------':'o','.------.':'p','------.---':'q','.---.':'r','...':'s','---':'t','..---':'u','...---':'v','.------':'w','---..---':'x','---.------':'y','------..':'z','   ':' '}
    data = input('Please provide some data : ')
    print('The translated data looks like this :')
    for d in data:
        print(lookup(MorseEnglish,d),end=' ')
    print()


if __name__ == "__main__":
    main()


4.

def char_counts(s):
	counts={}
	
	for ch in s:
		if ch in counts:
			counts[ch] = counts[ch] + 1
		else:
			counts[ch] = 1
	return counts
	
def main():
	s1 = input('Enter first string: ')
	s2 = input('Enter second string: ')
	
	counts1 = char_counts(s1)
	counts2 = char_counts(s2)
	
	if counts1 == counts2:
		print('strings are anagrams')
	else:
		print('strings are NOT anagrams')
		
		
if __name__ == "__main__":
	main()
