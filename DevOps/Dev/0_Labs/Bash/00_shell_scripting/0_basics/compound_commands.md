1. compound commands and extention and builtin commands


	A. by using a grouping utility create a folder tree as follows:
		*app:
			#model:
			#view:
			#controller:
		*bin:
			#setup:
		*log: 
			#output:
				1_app
				2_app
				3_app
			#error:
				1_app
				2_app
				3_app
	!!!Note: all signs(#*) are to signify a folder - they do not need to be in folder naming.

	B.write a script that:	
		1. asks from user detail as follows:
			#name
			#last name
			#dob
			#id
			#status
		2. after the details are received - verify them with the user.
		3. save the data provided to predefined dabase directory.(create it before)
	C. create a script called pretify:
		it should hold a function called sa that does as follows:
			1.holds variables pre='%' and post='%'
			2.print those variables with the string that was provided by user.
			
	D. create a script that  prints a Warning Message with a Border and a Beep.
			the alert message should say as follows:
				Alret $username
				
