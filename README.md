# .py
num = int(input("enter number :")
if(num%2==0):
    print(num,"is even number")
    if(num%5==0):
        print(num,"is even number and be divisible by 5")
    else:
       print(num,"is even number ans not divisible by 5")
else:
    print(num,"is odd number")




# example of class and importing external libraries
import math
def calculate_area_circle(radius):
    """calculates area of circle"""
    return math.pi*radius**2
class Rectangle:
    """Represents a rectangle with width and height"""
    def __init__(self,width,height):
         self.width = width
         self.height = height
    def calculate_area(self):
         return self.width*self.height
    
    
