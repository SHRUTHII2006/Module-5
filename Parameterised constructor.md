# Exp.No:23  
## Parameterised constructor

---

### AIM  
To write a python code to implement a class Dress with the parameterised constructor ,that accepts the cloth,cloth-type and quantity , and print the details.
---

### ALGORITHM

1.Start

2.Define a class Dress.

3.Define the __init__ method to accept parameters: cloth, cloth_type, and quantity.

4.Assign these parameters to instance variables.

5.Define a method print_details to display the cloth details.

6.Create an object of class Dress by passing values to the constructor.

7.Call the print_details method to show the dress information.

8.End


### PROGRAM

```
class Dress():
    def cloth(self,a,b,c):
        self.a=a+'(s)'
        self.b=b
        self.c=c
        print(self.c,self.b,self.a)
a=input()
b=input()
c=int(input())
obj=Dress()
obj.cloth(a,b,c)

```

### OUTPUT

![image](https://github.com/user-attachments/assets/09c0de3b-6a99-4c7f-82dd-c31973062f09)


### RESULT

Thus the  python code to implement a class Dress with the parameterised constructor ,that accepts the cloth,cloth-type and quantity , and print the details was successfully executed.


