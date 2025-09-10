
## AIM

Define the abstract base class named Polygon and also define the abstract method. This base class inherited by the various subclasses. Implement the abstract method in each subclass. Create the object of the subclasses and invoke the sides() method.
---

## 🧠 ALGORITHM
```
Start

Import Module

Import ABC and abstractmethod from the abc module.

Define Abstract Base Class

Create an abstract base class named Polygon.

Inside it, declare an abstract method sides() using @abstractmethod.

Define Subclass Triangle

Inherit from Polygon.

Implement the sides() method to print: "Triangle has 3 sides".

Define Subclass Square

Inherit from Polygon.

Implement the sides() method to print: "Square has 4 sides".

Define Subclass Pentagon

Inherit from Polygon.

Implement the sides() method to print: "Pentagon has 5 sides".

Create Objects of Subclasses

Create an object of Triangle.

Create an object of Square.

Create an object of Pentagon.

Invoke Methods

Call the sides() method using the Triangle object.

Call the sides() method using the Square object.

Call the sides() method using the Pentagon object.

Stop
```

## Program
```
from abc import ABC, abstractmethod

class Polygon(ABC):
    # Abstract method
    @abstractmethod
    def sides(self):
        pass

class Triangle(Polygon):
    def sides(self):
        print("Triangle has 3 sides")

class Pentagon(Polygon):
    def sides(self):
        print("Pentagon has 5 sides")

class Hexagon(Polygon):
    def sides(self):
        print("Hexagon has 6 sides")

class square(Polygon):
    def sides(self):
        print("I have 4 sides")

# Driver code
t = Triangle()
t.sides()

s = square()
s.sides()

p = Pentagon()
p.sides()

k = Hexagon()
k.sides()

```
## Output
<img width="489" height="216" alt="image" src="https://github.com/user-attachments/assets/8c5d05b7-5af4-435c-88c9-8524d55b3c1c" />

## Result
The Program was Executed successfully
