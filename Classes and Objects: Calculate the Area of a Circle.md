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

class cse:

    def mech(self, r):

        area = 3.14159 * (r ** 2)
        
        print(f"Area of circle: {round(area, 2)}")

radius = float(input("Enter the radius of the circle: "))

slot = cse()

slot.mech(radius)

## Output
<img width="1143" height="281" alt="image" src="https://github.com/user-attachments/assets/47802faf-6e61-423a-b90a-682caab720e5" />

## Result
Thus, the Python program that calculates the **area of a circle** based on the radius provided by the user is executed and verified successfully.
