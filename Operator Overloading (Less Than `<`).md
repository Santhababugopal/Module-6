#  Python OOP: Operator Overloading (Less Than `<`)


##  AIM:
To write a Python program that overloads the less-than (<) operator using the __lt__() method to compare two objects based on their attributes.

##  ALGORITHM:

1.Start the program.

2.Define a class (e.g., Student).

3.Create a constructor (__init__) to initialize object attributes
(example: marks).

4.Overload the less-than operator by defining the method:
5.Use the < operator to compare the objects.

6.Display the comparison result based on the overloaded method.

7.End the program.
##  PROGRAM:
```
class marks:
    def __init__(self, x):
        self.x = x
    def __lt__(self, other):
        return self.x <= other.x


obj1 = marks(20)
obj2 = marks(10)

print(obj1 < obj2)

```
## OUTPUT
<img width="351" height="163" alt="image" src="https://github.com/user-attachments/assets/97f32c06-8796-4901-a7a0-9713dd837f9b" />

## RESULT
Thus, the Python program successfully overloads the less-than (<) operator using the __lt__() method and compares two objects based on their attribute values. This demonstrates the concept of operator overloading in Python, allowing user-defined classes to use built-in operators for meaningful comparisons.
