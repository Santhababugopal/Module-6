6D:  Python OOP: Operator Overloading (Less Than `<`)


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

class A:
    def __init__(self,a):
        self.a=a
    def __gt__(self,other):
        return self.a<other.a
ob1=A(200)
ob2=A(30)
if(ob1<ob2):
    print("ob2 is less than ob1")
else:
    print("ob1 is less than ob1")
```
## OUTPUT
<img width="603" height="184" alt="image" src="https://github.com/user-attachments/assets/63d12b29-1b1c-4bd8-ad1d-1e38b6e5b858" />


## RESULT
Thus, the program to implement Operator Overloading (Less Than <) in Python was executed successfully and produced the expected result.
