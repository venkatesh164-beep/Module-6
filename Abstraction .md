# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Objects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

## 💻 Program
from abc import ABC<br>
class Shape(ABC):<br>
    def calculate_area(self):<br>
        pass<br>
class Rectangle(Shape):<br>
    length = 5<br>
    breadth =3 <br>
    def calculate_area(self):<br>
        return self.length * self.breadth<br>

class Circle(Shape):<br>
  radius = 4<br>
  def calculate_area(self):<br>
      return 3.14 * self.radius * self.radius<br>
rec=Rectangle()<br>
cir=Circle()<br>
print("Area of a rectangle:", rec.calculate_area())<br>
print("Area of a circle:", cir.calculate_area())

## Output
<img width="735" height="162" alt="image" src="https://github.com/user-attachments/assets/6e5c0211-99af-4c0b-8f49-5b17ec67c609" />

## Result
Thus ,the program excuted successfully.
