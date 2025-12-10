Constructor = runs automatically when object is created
Destructor = runs when object is destroyed
class Demo:
    def __init__(self):
        print("Object created")
    def __del__(self):
        print("Object destroyed")

d = Demo()
del d
