# Python Program to Perform Product of Two Complex Numbers Using Binary '+' Operator Overloading

# Aim
To create a Python program that overloads the '+' operator in the `complex` class to perform the product of two complex numbers.

# Procedure
1. Define a class named `complex` with a constructor `__init__` to initialize the real and imaginary parts.
2. Overload the '+' operator by defining the `__add__` method, which will compute the product of two complex numbers.
3. Create two objects of the `complex` class.
4. Use the overloaded '+' operator to compute and display the product of the complex numbers.
# Program
```python
class complex:
    def __init__(self,a,b):
        self.a=a
        self.b=b
    def __mul__(self,other):
        return self.a*other.a , self.b * other.b
        
ob1=complex(1,2)
ob2=complex(2,3)
ob3=ob1*ob2
print(ob3)
        
```

# Output

![image](https://github.com/user-attachments/assets/1bed67be-0d6d-4a20-902d-faee7dd62cc1)

# Result
The program successfully performs the product of two complex numbers using operator overloading.

