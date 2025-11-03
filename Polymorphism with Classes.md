# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
class Beans():<br>
def type(self):<br>
print("Vegetable")<br>
def color(self):<br>
print("Green")<br>
class Mango():<br>
def type(self):<br>
print("Fruit")<br>
def color(self):<br>
print("Yellow")<br>
def func(obj):<br>
obj.type()<br>
obj.color()<br>
obj_beans = Beans()<br>
obj_mango = Mango()<br>
func(obj_beans)<br>
func(obj_mango)
## Output
<img width="266" height="156" alt="image" src="https://github.com/user-attachments/assets/b1b30010-6c52-4b99-b113-09c5b5c03a9d" />

## Result
Thus,the program excuted successfully.
