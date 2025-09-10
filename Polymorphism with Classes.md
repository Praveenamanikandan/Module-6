# # Python OOP: Polymorphism with Classes

##  AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

##  ALGORITHM

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

##  Program
```
class Beans:
    def type(self):
        print("Vegetable")

    def color(self):
        print("Green")

class Mango:
    def type(self):
        print("Fruit")

    def color(self):
        print("Yellow")

# Generic function that works with any object having `type()` and `color()` methods
def show_info(obj):
    obj.type()
    obj.color()

# Create objects
bean = Beans()
mango = Mango()

# Pass objects to the generic function
show_info(bean)
show_info(mango)

```
## Output
<img width="472" height="245" alt="image" src="https://github.com/user-attachments/assets/f1739a51-1df0-4170-b1f5-7a382a231721" />

## Result
The program was executed successfully
