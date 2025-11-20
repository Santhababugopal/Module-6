#  Method Overriding-python program to multiply two object and print the word "orange" 10 times 

AIM:

To write a Python program that overloads the multiplication operator (*) so that multiplying two objects results in printing the word "orange" multiple times based on the product of their value

ALGORITHM:

1.Start the program.

2.Define a class (e.g., Fruit).

3.Create a constructor (__init__) to initialize an attribute (e.g., value) for each object.

4.Overload the multiplication operator by defining:


5.Create two objects of the class and assign integer values.

6.Multiply the objects using the overloaded * operator.

7.Store the result and print it.

8.End the program.

#Program:
```
class CSE:
        def __init__(self,a):
                self.a=a
        def __mul__(self,other):
                return self.a *other.a
obj1=CSE(4)
obj2=CSE(10)
obj3=CSE("orange")
print(obj1*obj2)
print(obj2*obj3)

```

#Output:
<img width="1160" height="182" alt="image" src="https://github.com/user-attachments/assets/be100bc0-1bd4-4f9f-b7bb-25a6809d3bfe" />
#Result:
Thus, the Python program successfully overloads the multiplication operator (*) and prints the word "orange" repeated according to the product of the values stored in two objects. The program demonstrates the concept of operator overloading in Python.
