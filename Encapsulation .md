# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program

```
class Rectangle:
    def __init__(self,length,width):
        self.__length=length
        self.__width=width
    
    def display(self):
        print(self.__length) #displaying inside the class
        
obj=Rectangle(5,3)
obj.display()
print(obj._Rectangle__width) #displaying outside the class
```

## Output

![Screenshot 2025-05-23 213119](https://github.com/user-attachments/assets/fd8b11b1-4cc2-40a0-9c18-809af87168a2)


## Result

Therefore,the given python programm is sucessfully verified.
