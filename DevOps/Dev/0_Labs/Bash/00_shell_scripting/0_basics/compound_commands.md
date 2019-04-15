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
		
	F. create a script that will read data from databse folder created in  task B.
		all the data needs to be modifyed to array and needs to shuffle the keys and values:
			for example:
							from : 1,2,3,4,5 ----> to : 5,2,4,1,3
							
	C. create a script called pretify:
		it should hold a function called sa that does as follows:
			1.holds variables pre=':' and post=':'
			2.print those variables with the string that was provided by user.
			
	D. create a script that  prints a Warning Message with a Border and a Beep.
			the alert message should say as follows:
				Alret $username
				
	E. create a script that works as process management framework:
		1. it will provide menu of options as follows:
			#create process
			#kill process
			#send process to background
			#send process to foreground
			#create a process and wait for its exit status.
		2. in case of manual interrupt  script should as user if he really wants to quit
			then wait 5 seconds, print that it will terminate now and wait another 5 seconds. 
					
	
	G. create a script that will set you bashrc configuration file:
		by using bash builtin commands, the should create a version of bashrc that
		lets the shell behave as you need.
		design a menu like interface with leading questions regarding shell behaviour
		you'd like to occur.
		
	H.create a script that reads users input and turns it automatically to array.
		the array should be kept at predefined file.
