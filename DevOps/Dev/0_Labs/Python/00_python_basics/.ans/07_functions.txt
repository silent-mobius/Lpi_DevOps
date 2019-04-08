#python functions
1.
	A.Create a function named my_function that prints hello from function.
	B.Call (execute) a function named my_function.
	C.Inside a function with two parameters, print the first parameter.
	D.Let the function return the x parameter + 5.
2.
A magic date is a date where the day multiplied by the month is equal to the two digit
year. For example, June 10, 1960 is a magic date because June is the sixth month, and
6 times 10 is 60, which is equal to the two digit year. Write a function that determines
whether or not a date is a magic date. Use your function to create a main program
that finds and displays all of the magic dates in the 20th century.

3.
Write a function that determines how many days there are in a particular month. Your
function will take two parameters: The month as an integer between 1 and 12, and
the year as a four digit integer. Ensure that your function reports the correct number
of days in February for leap years. Include a main program that reads a month and
year from the user and displays the number of days in that month. 

4.
A prime number is an integer greater than 1 that is only divisible by one and itself.
Write a function that determines whether or not its parameter is prime, returning
True if it is, and False otherwise. Write a main program that reads an integer
from the user and displays a message indicating whether or not it is prime. Ensure
that the main program will not run if the file containing your solution is imported
into another program.

5.
Write a function that generates a random password. The password should have a
random length of between 7 and 10 characters. Each character should be randomly
selected from positions 33 to 126 in the ASCII table. Your function will not take
any parameters. It will return the randomly generated password as its only result.
Display the randomly generated password in your file’s main program. Your main
program should only run when your solution has not been imported into another file.


1.
A.
def my_function():
     print("Hello from a function")
     
B.
def my_function():
  print("Hello from a function")
  
my_function()


C.
def my_function(fname, lname):
  print(fname)
  

D.
def my_function(x):
  return x+5



2.




3.





4.

def is_prime(n):
	if n <=1:
		return False
		
	for i in range(2,n):
		if n % i == 0 :
			return False
		return True
		
def main():
	val = int(input('enter integer: '))
	
	if is_prime(val):
		print(val,'is Prime')
	else:
		print(val,'is Not Prime')
			

if __name__ == '__main__':
	main()

5.

def check_passwd(password):
	has_upper=False
	has_lower=False
	has_num = False
	
	for ch in password:
		if ch >= 'A' and ch <= 'Z':
			has_upper= True
		elif ch >= 'a' and ch <= 'z':
			has_lower = True
		elif ch >= '0' and ch <= '9':
			has_num = True
		
	if len(password) >= 8 and has_upper and has_lower and has_num:
		return True
	
	return False
	

def main():
	passwd = input('Enter a password: ')
	if check_passwd(passwd):
		print('Good password')
	else:
		print('that\'s not really best password ')


if __name__ == "__main__":
	main()
