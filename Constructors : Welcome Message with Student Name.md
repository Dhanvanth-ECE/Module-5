# # Constructors in Python: Welcome Message with Student Name

## 🎯 Aim
To write a Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user.

## 🧠 Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `show` that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
5. **Execute the Program**: Instantiate the `Student` class and call the `show` method.

## 🧾 Program
```p
name = input()

class Student:
    def __init__(self):
        self.a = name

    def show(self):
        print("This is non-parameterized constructor")
        print("Welcome", self.a)

s = Student()
s.show()
```
## Output
<img width="1317" height="332" alt="image" src="https://github.com/user-attachments/assets/8079c042-f922-4f8b-8364-0b0568d6d157" />

## Result
Thus, the Python program to create a Student class with a default constructor and display a welcome message with the student's name was implemented and executed successfully.
