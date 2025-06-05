# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Objects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

## 💻 Program

```
from abc import ABC
class Shape(ABC): 
    def calculate_area(self):
      pass

class Rectangle(Shape):
  length = 6
  breadth = 4
  def calculate_area(self):
      return self.length*self.breadth

class Circle(Shape):
  radius = 7
  def calculate_area(self):
      return 3.14*self.radius*self.radius

r=Rectangle()
c=Circle() 

print("Area of a rectangle:", r.calculate_area()) 
print("Area of a circle:", c.calculate_area())  
```

## Output

![Screenshot 2025-05-23 212947](https://github.com/user-attachments/assets/8c0dbfd1-78c7-454a-a643-b6c5ec2f40fd)


## Result

Thus, the program is verified successfully.
