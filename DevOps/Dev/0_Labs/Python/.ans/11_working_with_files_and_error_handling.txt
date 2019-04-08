#working wit files
1.
	A. Create a script that operates with files. in script try to open 'demofile.txt'. write in it: 'this is a demofile' and close. catch an exception that handles 'file does not exists'.
	B. Create a script that tries to open readonly file. handle exception that does not allows to write in to readonly file.
	C. Create a script that handles file. it should try to catch any error and should have 'finally' resolution.
	D. Create a script which handles file, and catchs any exception, but also has 'else' resolution.

1.
	A. try:
		  f = open("demofile.txt")
		  f.write("this is demofile")
	   except:
		  print("Something went wrong when writing to the file")

	B.
		try:
			  f = open("demofile.txt")
			  f.write("this is demofile")
		except:
			  print("Something went wrong when writing to the file")

	C.
		try:
			  f = open("demofile.txt")
			  f.write("this is demofile")
		except:
			  print("Something went wrong when writing to the file")
		finally:
			  f.close()
	D.
	
	try:
		  f = open("demofile.txt")
		  f.write("this is demofile")
	except:
		  print("Something went wrong")
	else:
		  print("Nothing went wrong")
