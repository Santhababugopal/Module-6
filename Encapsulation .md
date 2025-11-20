#  Python OOP: Create a Class  Student with the private members name and age ,Add getter and setter to initialize the age variable

##  AIM

To create a Python class Student with private data members name and age, and to implement getter and setter methods to access and modify the private age variable.


##  ALGORITHM

1.Start the program.

2.Define the class Student.

3.Inside the class:

4.Declare private members:

__name

__age

5.Create a constructor __init__() to initialize the private variables.

6.Create a getter method get_age() to return the value of __age.

7.End the program.

##  Program
```

class Student:
    def __init__(self, name, age):
        self.name = name
        self.__age = age
    def set_age(self,age):
        self.__age=age
    def get_age(self):
        return self.__age
        
stud = Student('Jessa', 14)
print('Name:', stud.name, stud.get_age())

stud.set_age(16)

print('Name:', stud.name, stud.get_age())
```
## Output
<img width="522" height="186" alt="image" src="https://github.com/user-attachments/assets/03746f63-cc38-4c93-8015-606045d32a65" />

## Result
Thus, the Python program successfully creates a class Student with private members name and age, and implements getter and setter methods to safely access and modify the private age variable. This demonstrates the concept of data hiding and encapsulation in Object-Oriented Programming.
