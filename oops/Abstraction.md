Showing only essential features, hiding complexity.


from abc import ABC, abstractmethod
class Payment(ABC):
@abstractmethod
def pay(self, amount):
     pass

class RazorPay(Payment):
    def pay(self, amount):
        print("Paid using RazorPay:", amount)

class Stripe(Payment):
    def pay(self, amount):
        print("Paid using Stripe:", amount)

gateway = RazorPay()
gateway.pay(500)
