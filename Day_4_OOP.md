# OOP learning

## 1) Classes and Objects
#### CLASS - A Class is like an object constructor, or a "blueprint" for creating objects.
#### OBJECT - Almost everything in Python is an object, with its properties and methods
```py
#OOP for a training
class scholar:                                                         #class
    def __init__(self, name, age):                                     #object
        self.name = name
        self.age = age

    def __str__(self) -> str:                                          #object
        return f'{self.name} is {self.age} years old.'
    
    def get_bio(self):                                                 #object
        print(f'Scholar called {self.name}, is {self.age} years old')
        

Person = scholar
p1 = Person('Mike', 18)
print(p1) #activates __str__ func

p1.get_bio() #activates get_bio func
```
## 2) Encapsulation
#### ENCAPSULATION - 
```py

```
## 3) Inheritance
#### since classes are devided in children and parents, monipulations with them became easier
#### INHERITANCE - lika a family tree. You obtaining information from both parents
```py
#OOP for a training
class Human:                                                        #Parent
    def __init__(self, name ):     
        self.name = name

    def human_part(self):
        print(f"'{self.name}' shows emotions, because he/she has an intelligence")


class Machine:                                                    #Parent
    def __init__(self, number):
         self.number = number

    def Machine_part(self):
        print(f"'{self.number}' can be upgraded with modificators and mechanisms")


class Cyborg(Human,Machine):                                      #Child
    def __init__(self, name,number ):
        self.name = name
        self.number = number


object1 = Cyborg('Roger', '348FFK54DKHHO4')                       # giving attributes
object1.human_part()                                              # inherited from Human
object1.Machine_part()                                            # inherited from Machine
```
## 4) Polymorphism
#### POLYMORPHISM - 
```py

```
## 5) Abstraction
#### ABSTRACTION - 
```py

```
#                       FeedBack
## 1) Iterators
### functions __iter__() and __next__()
#### 'Dictionary', 'tuple', 'set', 'list' are iterable
```py

```
#### 'string' also can be iterated
```py

```
