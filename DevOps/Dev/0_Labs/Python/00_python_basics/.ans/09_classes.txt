
1. create a script that has person class built in it. it should have attributes name and age, and it also suppose to have method that prints the name via attribute.
2. create a script that has pizza class. it should have  a constructor, and make and eat methods. in constructor, you should get pizzan name and and its price. in  make/eat methods you should have  qunatity variables set to 1.
3. create script that creates a bulb class.  it should have method that initializes it, and also methods on and off that will put the light on and also off



1.
	class Person:
	  def __init__(mysillyobject, name, age):
		mysillyobject.name = name
		mysillyobject.age = age

	  def myfunc(abc):
		print("Hello my name is " + abc.name)

	p1 = Person("John", 36)
	p1.myfunc()

2.
class Pizza():
    def __init__(self, name, price):
        self.name = name
        self.price = price
        print("Pizza created: {} (${})".format(self.name, self.price))

    def make(self, quantity=1):
        print("Made {} {} pizza(s)".format(quantity, self.name))

    def eat(self, quantity=1):
        print("Ate {} pizza(s)".format(quantity, self.name))

pizza_01 = Pizza("olive", 15)
pizza_01.make()
pizza_01.eat()

pizza_02 = Pizza("diahriah", 12)
pizza_02.make(2)
pizza_02.eat()






3. 


class Bulb():
	def __init__(self, val=False):
		self._on = val
	
	def lights_on(self):
		if not self._on:
			print('Lights on')
			self._on = True
			
	def lights_off(self):
		if self._on:
			print('Lights off')
			self._on = False
			


l = Bulb()

g = Bulb(val = True)


l.lights_on()

l._on = False

l.lights_on()
