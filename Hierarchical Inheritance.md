# Exp.No:25  
## Hierarchical Inheritance

---

### AIM  
To write a Python program to get the employee and doctor details and display them using hierarchical inheritance. Create a parent (base) class named `Details` and two child (derived) classes named `Employee` and `Patient`.

---

### ALGORITHM

1. **Begin the program.**
2. **Create a class Details** with an `__init__` method to initialize three attributes: `id`, `name`, and `gender`.
3. **Define a method display_details()** to print the values of `id`, `name`, and `gender`.
4. **Create a class Employee** that inherits from the `Details` class. 
   - Add two additional attributes: `company` and `department`.
   - Override the `display_details()` method to print the employee-specific attributes (`company` and `department`) along with the inherited details.
5. **Create a class Doctor** that also inherits from the `Details` class. 
   - Add two additional attributes: `hospital` and `department`.
   - Override the `display_details()` method to print the doctor-specific attributes (`hospital` and `department`) along with the inherited details.
6. **Accept input** for employee and doctor details.
7. **Create objects of Employee and Patient** using the input.
8. **Call the `display_details()` method** for both objects to print the details.
9. **Terminate the program.**

---

### PROGRAM
```
class details:

    def __init__(self,Id,name,gend,hosp,dept):
        self.Id=Id
        self.name=name
        self.gend=gend
        self.hosp=hosp
        self.dept=dept
    def disp(self):
        print(f"Id:  {self.Id}")
        print(f"Name:  {self.name}")
        print(f"Gender:  {self.gend}")
        print(f"Company:  {self.hosp}")
        print(f"Department:  {self.dept}")
    def disp2(self):
        print(f"Id:  {self.Id}")
        print(f"Name:  {self.name}")
        print(f"Gender:  {self.gend}")
        print(f"Hospital:  {self.hosp}")
        print(f"Department:  {self.dept}")
class doctor(details):
    def __init__(self,Id,name,gend,hosp,dept):
        super().__init__(Id,name,gend,hosp,dept)
    def display(self):
        print("Employee Object")
        self.disp()
class patient(details):
    def __init__(self,Id,name,gend,hosp,dept):
        super().__init__(Id,name,gend,hosp,dept)
    def display(self):
        print("\nPatient Object")
        self.disp2()
d_Id=int(input())
d_name=input()
d_gend=input()
d_hosp=input()
d_dept=input()
doc=doctor(d_Id,d_name,d_gend,d_hosp,d_dept)
doc.display()

p_Id=int(input())
p_name=input()
p_gend=input()
p_hosp=input()
p_dept=input()
docc=patient(p_Id,p_name,p_gend,p_hosp,p_dept)
docc.display()


        
```

### OUTPUT  

![image](https://github.com/user-attachments/assets/75dad831-47a9-4297-8b23-227d2c5c544f)


### RESULT

Thus the  Python program to get the employee and doctor details and display them using hierarchical inheritance. Create a parent (base) class named `Details` and two child (derived) classes named `Employee` and `Patient` was successfully executed.
