# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

## 💻 PROGRAM:
```
class Fish:
       #Add your code here
       def type(self):
           print("fish")

class Shark(Fish):
    def type(self):
        print("shark")
	#Add your code here

obj1=Fish()
obj2=Shark()
obj1.type()
obj2.type()
```
## OUTPUT
<img width="1352" height="803" alt="image" src="https://github.com/user-attachments/assets/46c234e7-0ea3-4037-a884-c3d01f75e783" />

## RESULT
Thus the given python program has been executed successfully.
