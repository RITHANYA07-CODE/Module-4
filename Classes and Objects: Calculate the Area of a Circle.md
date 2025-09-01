# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math

class cse:
    def __init__(self, radius):
        self.radius = radius
        
    def mech(self):
        return math.pi * (self.radius**2)
        
r = float(input())
c = cse(r)
print(f"Area of circle: {c.mech():.2f}")
```
## Output
<img width="694" height="198" alt="image" src="https://github.com/user-attachments/assets/4f9399d2-7f2b-46d2-8730-d2577f108234" />

## Result
The program successfully calculates the area of a circle based on the radius provided by the user.
