#Expressions vs Statements 
Expressions simply represent something in python like a number or string. 
A statement in python is anything that does something. Name = “david’ is a statement that takes name and assigns it the value of the expression “david”.


#__INIT__

The __init__  or initialization method is run as soon as an object of a class is instantiated. It is responsible for setting up that attributes that the instances will take. The double underscore tells us that "init" is a word that is already taken up in python. The __init__ method always takes the parameter self which represents the instance being created.

```python
class Person:
	def __init__(self, name, age, job)
		self.name = name
		self.age = age
		self.job = job

person1 = Person("David", 21, "student")
person1.name
person1.age
person1.job
```



