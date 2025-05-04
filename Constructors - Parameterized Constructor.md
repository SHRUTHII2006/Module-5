# Exp.No:21  
## Constructors - Parameterized Constructor

---

### AIM  
To write a Python code to create a class for a person with a parameterized constructor, which will take the `name` and `rollno` of the person as parameters and print the `rollno` of the person.

---

### ALGORITHM

1. Begin the program.  
2. Define a `person` class.  
3. The `person` class should have a parameterized `__init__` method that accepts two parameters: `name` and `rollno`.  
4. Inside the `__init__` method, assign the `name` to `self.name` and the `rollno` to `self.rollno`.  
5. Print the `self.rollno`.  
6. Prompt the user to enter their `name` (string) and `rollno`.  
7. Create an instance `s1` of the `person` class by passing the entered `name` and `rollno` to the constructor.  
8. Terminate the program.

---

### PROGRAM


class Employee:

   #Add your code here
   
   def __init__(self,id,name):
   
        self.id=id
        
        self.name=name
        
   def display(self):
   
       print("Name: "   , self.id)
       
       print("Roll no.: "   , self.name)
       
id1=input()

name=int(input())



e1=Employee(id1,name)

e1.display()



### OUTPUT


![image](https://github.com/user-attachments/assets/6b851e6e-3bd1-4e69-afb3-86041c40d8c2)

### RESULT

Thus the Python code to create a class for a person with a parameterized constructor, which will take the `name` and `rollno` of the person as parameters and print the `rollno` of the person was written and executed successfully.
 
