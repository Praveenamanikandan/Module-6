
##  AIM:
write a python program to perform division of two complex number using binary '+' operator overloading

## ALGORITHM:
```

Start

Define a class with required data members.

Create a constructor to initialize the data members.

Define the operator overloading method (__add__) to perform the desired operation (here, complex number division).

Return the result as a new object of the same class.

Define a method to display the result in a readable format.

Create objects of the class with initial values.

Use the overloaded operator between the objects to perform the operation.

Display the final result.
```

## PROGRAM:
```
class complex:
    def __init__(self,a,b):
        self.a=a
        self.b=b
    def __truediv__(self,o):
        return self.a/o.a,self.b/o.b
    
Ob1 = complex(10, 21)

Ob2 = complex(2, 3)
ob=Ob1/Ob2
print(ob)

```
## OUTPUT
<img width="431" height="162" alt="image" src="https://github.com/user-attachments/assets/f0d6543e-d83f-459c-b357-6a58fc9c497f" />

## RESULT
The program was execited successfully
