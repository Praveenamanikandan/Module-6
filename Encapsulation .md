
## AIM

Create a class Car with the private variables max_speed,name change the value of a private variable, Use a setter method  setMaxSpeed(). create an object of the class to invoke the methods
---

## ALGORITHM
```
Start

Define Class Car

Declare two private variables:

__max_speed

__name

Define Constructor

Initialize __max_speed and __name with default values.

Define Setter Method

Create a method setMaxSpeed(new_speed) that updates the private variable __max_speed.

Define Display Method

Create a method display() to print car name and max speed.

Create Object

Create an object of Car.

Call Methods

Use display() to show initial values.

Use setMaxSpeed() to update the max speed.

Again call display() to show updated values.

Stop
```

##  Program
```
class Car:

    __maxspeed = 0
    __name = ""
    
    def __init__(self):
        self.__maxspeed = 200
        self.__name = "Supercar"
    
    def drive(self):
        print('driving. maxspeed ' + str(self.__maxspeed))

    # Setter method to change the value of maxspeed
    def setMaxSpeed(self, speed):
        self.__maxspeed = speed

# Create object
redcar = Car()
redcar.drive()

# Change the maxspeed to 320
redcar.setMaxSpeed(320)
redcar.drive()

```
## Output
<img width="487" height="152" alt="image" src="https://github.com/user-attachments/assets/807c26e1-921b-4b82-b086-9c90cb18ef0f" />

## Result
The Program was exected successfully
