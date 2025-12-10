Polymorphism means “Many forms”. Same function name, different behavior

class Bird:
    def fly(self):
        return "Flies high"

class Penguin(Bird):
    def fly(self):
        return "Can't fly"

def make_bird_fly(bird):
    print(bird.fly())

sparrow = Bird()
penguin = Penguin()
make_bird_fly(sparrow)  
make_bird_fly(penguin)  
