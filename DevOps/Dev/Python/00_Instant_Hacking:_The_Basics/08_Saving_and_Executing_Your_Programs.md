Running Your Python Scripts from a Command Prompt
Actually, there are several ways to run your programs. First, let’s assume you have a DOS window or a UNIX
shell prompt before you and that the directory containing the Python executable (called python in Linuz) or
the directory containing the executable (in Windows) has been put in your PATH environment variable.
Also, let’s assume that your script from the previous section (hello.py) is in the current directory.
Then you can execute your script with the following command:
$ python hello.py

Making Your Scripts Behave Like Normal Programs
Sometimes you want to execute a Python program (also called a script) the same way you execute other
programs (such as your web browser or text editor), rather than explicitly using the Python interpreter.
In UNIX, there is a standard way of doing this: have the first line of your script begin with the character
sequence #! (called pound bang or shebang) followed by the absolute path to the program that interprets the
script (in our case Python). Even if you didn’t quite understand that, just put the following in the first line of
your script if you want it to run easily on UNIX:

#!/usr/bin/env python

This should run the script, regardless of where the Python binary is located. If you have more than one
version of Python installed, you could use a more specific executable name, such as python3, rather than
simply python. Before you can actually run your script, you must make it executable.

$ chmod a+x hello.py

Now it can be run like this (assuming that you have the current directory in your path):

$ hello.py

If this doesn’t work, try using ./hello.py instead, which will work even if the current directory (.) is not part
of your execution path (which a responsible sysadmin would probably tell you it shouldn’t be).
If you like, you can rename your file and remove the py suffix to make it look more like a normal
program.
