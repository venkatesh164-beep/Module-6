# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
class R:<br>
    def __init__(self, l, w):<br>
        self.__l = l<br>
        self.__w = w<br>
    def display(self):<br>
        print(self.__l)<br>
        print(self.__w)<br>
rect = R(5,3)<br>
rect.display()
## Output
<img width="343" height="157" alt="image" src="https://github.com/user-attachments/assets/3b1520e7-24b2-4a58-bc5b-f6267e2689d0" />

## Result
Thus ,the program executed successfully.
