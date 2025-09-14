## Data-Science Notes

# 1) Python-notes notebook
  1> Basic Operations and Data types -> Define Variables, print(), f-string, input("prompt"), type(), len(), Data-types[text, numeric(int, float, complex), sequence(list, tuple, range), map(dictionary), set, boolean, None Type]
  
  2> Control Flow -> if-elif-else, for-in, while, for-else, range(-,-,-)
  
  3> String Operations -> (v1,v2=a1,a2), s[i](char at ith index), slicing(s[-:-:-]), reversed=s[::-1], concatenation(s1.join(s2))

  4> List and List comprehensions -> [],same data type, lst[-1](last element), slicing lst[-:-:-], lst.append("-"), lst.insert(index,"-"), lst.remove("-"), lst.pop()(last item remove and print), lst.index('-'), lst.count('-'), [2::2], reverse slice [::-2], (for index, value in enumerate(lst):), comprehension [x****2 for x in range(5)], with condition [x**2 for x in range(10) if x%2 == 0], nested comprehension [[i*j for j in range(1,4)] for i in range(1,4)], [len(word) for word in words], % 10 - unit digit -> // 10 - unit digit remove

  5> Tuples -> (1,) - single element tuple, immutable, different data types possible, accessing --> ([0],[-1] - last element, [1:4], [::-1] - reverse, [::2]), concatenation tup1+tup2, "-" in tup, repeat = tup*2 -> values repeat, tup.count('-') -> freq of duplicated element, tup.index(3) -> element at that index, tup.index('-', 1) -> index of '-' starting from 1, packing = 1,2,3 -> (1,2,3) (implicitly/by itself), unpack -> a,b = (1,2), nested tuple -> tupp[1][2], for item in numbers_tup, for i, item in enumerate(numbers_tup), swap -> (x,y = y,x) 

  6> Sets 

  7> Dictionaries

  8> Functions and Lambda Functions

  9> Real world applications

  10> Map

  11> Filter

  12> Importing Modules

  13> Libraries

  14> File handling and operations

  15> Exceptions

  16> Object Oriented Programming -> class --: -> (object)audi = car(), dir() -> list of methods associated witha object, constructor -> def __init__(self, name, age): self.name= name, self.age= age -> obj('name', 3), call -> object.name, object.age, .age and .name can be used with all objects made, methods -> def method_name(self): ---self.name, self.age can be used, calling -> object.method_name(), method argument - def deposit(self,amount), self is for accessing og variables, inheritance ->inherited class - class Tesla(Car) -> inherited og arguments-> constructor addns -> super().__init__(windows, doors,enginetype), multiple inheritance -> derieved class inherits from 2 or more base classes, class Animal, class Pet, class Dog(Animal, Pet), og attributes inheriting def __init__(self,name, owner):Animal.__init__(self, name), Pet.__init__(self, owner),  polymorphism - with this 2 or more derieved classes from same base class can access same method, also known as method overiding, class Animal, class Dog(Animal), class Cat(Animal) -> Animal, Dog and Cat all have method called speak, but it returns different things in different class, function that demonstrate polymorphism -> def animal_speak(animal): print(animal.speak()), animal_speak(dog_object) -> returns speak method of Dog class, polymorphism with abstract base class, from abc import ABC, abstractmethod, class Vehicle(ABC): @abstractmethod def start_engine(self): pass, class Car(Vehicle), class Motorcycle(Vehicle), both derieved classes Car and Motorcycle have start_engine method, function of polymorphism -> def start_vehicle(vehicle): print(vehicle.start_engine()), start_vehicle(car_object) -> Car class method trigger
             
             
