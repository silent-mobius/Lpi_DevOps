##intro
{id:intro}
So, what is Python, and why should you use it? To quote an old official blurb, it is “an interpreted,
object-oriented, high-level programming language with dynamic semantics.” Many of these terms will
become clear as you read this book, but the gist is that Python is a programming language that knows how to
stay out of your way when you write your programs. It enables you to implement the functionality you want
without any hassle and lets you write programs that are clear and readable (much more so than programs in
most other currently popular programming languages).
Even though Python might not be as fast as compiled languages such as C or C++, what you save in
programming time will probably be worth using it, and in most programs, the speed difference won’t be
noticeable anyway. If you are a C programmer, you can easily implement the critical parts of your program
in C at a later date and have them interoperate with the Python parts. If you haven’t done any programming
before, Python’s combination of simplicity and power makes it an ideal choice as a place to start.

So, who uses Python? Since Guido van Rossum created the language in the early 1990s, its following
has grown steadily, and interest has increased markedly in the past few years. Python is used extensively for
system administration tasks (it is, for example, a vital component of several Linux distributions), but it is also
used to teach programming to complete beginners. The US National Aeronautics and Space Administration
(NASA) uses Python both for development and as a scripting language in several of its systems. Industrial
Light & Magic uses Python in its production of special effects for large-budget feature films. Google has used it to implement
many components of its web crawler and search engine. 

To begin, you need to install Python, or verify that you already have it installed. If you’re running
Linux, open a terminal, type in python, and press Enter. You should get a welcome message, ending with the following prompt:
	
	>>>
If you do, you can start entering Python commands immediately. Note, however, that you may have an old
version of Python. If the first line starts with Python 2 rather than Python 3, you might want to install a
newer version anyway, as Python 3 introduces several breaking changes. Yon can find python 3 installation 
instructions in the main folder of the course.
Once you have Python installed, try to fire up the interactive interpreter. If you’re using the command
line, you could simply use the python command, or perhaps python3 if you have an older version installed
as well.

##The Interactive Interpreter

When you start up Python, you get a prompt similar to the following:
Python 3.6.8 (default, Mar 01 2019, 10:09:12) 
[GCC 8.3.1 20190223 (Red Hat 8.3.1-2)] on linux
Type "help", "copyright", "credits" or "license" for more information.

