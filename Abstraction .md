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
~~~
from abc import ABC,abstractmethod
class type_shape(ABC): 
    @abstractmethod
    def area(self):
        pass

class Rectangle(type_shape):
  length = 6
  breadth = 4
  def area(self):
    return self.length * self.breadth

class Circle(type_shape):
  radius = 7
  def area(self):
      return 3.14*self.radius*self.radius

r = Rectangle() 
c = Circle() 
print("Area of a rectangle:", r.area()) 
print("Area of a circle:", c.area())
~~~

## Output
![image](https://github.com/user-attachments/assets/d685918a-5331-4ff1-9875-d1a73be6da73)


## Result
A python program with an abstract class named Shape with an abstract method calculate_area, is successfully implemented in two subclasses: Rectangle and Circle.
