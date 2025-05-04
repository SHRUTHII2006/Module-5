# Exp.No:24  
## Multi-level Inheritance

---

### AIM  
To write a Python program to get the name, age, and location of a person and display them using multilevel inheritance.

---

### ALGORITHM

1. Define the `Person` class:
   - Inside the `Person` class, define the `__init__` method (constructor) with two parameters: `name` and `age`.
   - Inside the `__init__` method, assign the `name` to `self.name` and `age` to `self.age`.

2. Define the `PersonDetails` class that inherits from the `Person` class:
   - Inside the `PersonDetails` class, define the `__init__` method (constructor) with three parameters: `name`, `age`, and `person_location`.
   - Inside the `__init__` method, call the `__init__` method of the `Person` class using `super()` to initialize `name` and `age`.
   - Assign `person_id` to `self.person_location`.

3. Define the `DisplayDetails` class that inherits from the `PersonDetails` class:
   - Inside the `DisplayDetails` class, define the `__init__` method (constructor) with three parameters: `name`, `age`, and `person_location`.
   - Inside the `__init__` method, call the `__init__` method of the `PersonDetails` class using `super()` to initialize `name`, `age`, and `person_location`.

4. Inside the `DisplayDetails` class, define the `show_details` method:
   - Inside the `show_details` method, return a formatted string with `self.name`, `self.age`, and `self.person_location`.

5. Prompt the user to enter `name` (string), `age` (integer), and `person_location` (integer).

6. Create an instance `person` of the `DisplayDetails` class, passing `name`, `age`, and `person_location` to the constructor.

7. Call the `show_details` method on the `person` object and print the result.

8. Terminate the program.

---

### PROGRAM

```

class name:
    def __init__(self,a):
        self.a=a
class age(name):
    def __init__(self,a,b):
        super().__init__(a)
        self.b=b
class location(age):
    def __init__(self,a,b,c):
        super().__init__(a,b)
        self.c=c
    def disp(self):
        print(self.a,self.b,self.c)
a=input()
b=int(input())
c=input()
obj=location(a,b,c)
obj.disp()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/528d4381-36bf-4b7e-b411-ed103dad6e43)


### RESULT

Thus the Python program to get the name, age, and location of a person and display them using multilevel inheritance was successfully executed.
