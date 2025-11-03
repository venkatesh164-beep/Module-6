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
class A:<br>
    def __init__(self, value):<br>
        self.value = value<br>
    def __lt__(self, other):<br>
        return self.value < other.value<br>
ob1 = A(20)<br>
ob2 = A(3)<br>
if ob2 < ob1:<br>
    print("ob2 is less than ob1")<br>
else:<br>
    print("ob2 is not less than ob1")

## Output
<img width="562" height="167" alt="image" src="https://github.com/user-attachments/assets/9ae3f342-bcd2-470d-9d7f-00f03aa1b20f" />

## Result
Thus,the program excuted successfully.
