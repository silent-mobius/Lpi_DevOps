operators:
1.
	A.Create a script that usesq variables x=10 and y=5. Multiply x and y, and print the result.
	B.In the same script,using divide 10 by 2, and print the result.
	C.Create a list of fruits.(apple,banana,melon,orange)Use the correct membership operator to check if "apple" is present in the fruits object.
	D.Create a condition check.Use the correct comparison operator to check if 5 is not equal to 10.
	E.Create a condition check.Use the correct logical operator to check if at least one of two statements is True.

2.
Create a program that reads two integers, a and b, from the user. Your program should compute and display:
	The sum of a and b
	The difference when b is subtracted from a
	The product of a and b6
	The quotient when a is divided by b
	The remainder when a is divided by b
	The result of a^b

#ans

1.ans
	A.	x=5
		y=10
		
		z=x+y
		print(z)
	
	B.  x=5
		y=10
		
		
		print(z)
		y=y/2
		print(y)
	
	C.
		fruits=[apple, banana, melon, orange]
		print("apple" in fruits)
	D. 
		x=5
		y=10
		print(x != y)
		
	E. DC_Heroes=10
	   Marvel=9
		if DC_Heroes == 10 or Marvel == 4:
            print("At least one of the statements is true")



2.ans

a = int(input("Enter a"))
b = int(input("Enter b"))


print(a, "+",b,"=",a+b)
print(a, "-",b,"=",a-b)
print(a, "*",b,"=",a*b)
print(a, "/",b,"=",a/b)
print(a, "%",b,"=",a%b)
print(a, "**",b,"=",a**b)
