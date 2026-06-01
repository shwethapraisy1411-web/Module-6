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
<img width="801" height="526" alt="image" src="https://github.com/user-attachments/assets/37b42fa0-fa95-4f3a-a94f-3f227ff17075" />

## Output
<img width="443" height="197" alt="image" src="https://github.com/user-attachments/assets/04b80a25-b13f-4c43-8a84-84a498505fb6" />

## Result
The output is verified successfully.
