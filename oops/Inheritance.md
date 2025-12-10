One class inherits from another
Code reusable, avoids duplication
ex: children inherits some characteristics from parents

class Animal:
    def speak(self):
        return "Animal speaks"

class Cat(Animal): 
    def speak(self):
        return "Meow!"

my_cat = Cat()
print(my_cat.speak()) 
