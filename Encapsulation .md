# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Player` with **private member variables** `__name` and `__player_number`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Player` with two private attributes: `__name` and `__player_number`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__name` and `__player_number`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `obj` class to trigger the constructor.

---

## 💻 Program
```
class Player:
    def __init__(self, name, player_number):
        self.__name = name
        self.__player_number = player_number
    def getattributes(self):
        print(self.__name)
        print(self.__player_number)
    def setattributes(self, pname, pnumber):
        self.__name = pname
        self.__player_number = pnumber
obj = Player("Betty Ballmer", 10)
obj.getattributes()
obj.setattributes("Buster Ballmer", 11)
obj.getattributes()
```
## Output
<img width="1092" height="885" alt="image" src="https://github.com/user-attachments/assets/3def430e-ba43-4686-806b-2beac5c30852" />

## Result
Thus the given python program has been executed successfully.
