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
    def mech(self,radius):
        totarea=math.pi*radius**2
        return totarea
pen_object=cse()
radius=int(input())
result=pen_object.mech(radius)
print("Area of circle:",round(result,2))
```

## Output
<img width="811" height="228" alt="image" src="https://github.com/user-attachments/assets/92f6ea59-6d51-448d-9081-46d7d3c11e79" />

## Result
Thus, the program was executed successfully and the area of the circle was calculated using a class and method.
