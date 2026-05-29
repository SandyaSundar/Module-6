# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
```
class A:
    def __init__(self, a):
        self.a = a
    def __gt__(self, other):
        if self.a < other.a:
            print("ob2 is greater than ob1")
        else:
            print("ob2 is less than ob1")
            
obj1 = A(200)
obj2 = A(30)
obj1 > obj2
```
## Output
<img width="585" height="922" alt="image" src="https://github.com/user-attachments/assets/a76d025d-e0be-4201-9769-fe784ad1eb38" />

## Result
Thus the python program has been executed successfully.
