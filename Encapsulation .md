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
~~~
class Rectangle:
length = 0
breadth = 0
def __init__(self):
    ___ length = 5
    ___ breadth = 3
    print(self.__length) 
    print(self.__breadth)
rect = Rectangle()
~~~

## Output
![image](https://github.com/user-attachments/assets/66c3f1ea-c740-48e4-b5f7-8ca190987a5a)


## Result
Thus, the program has been successfully executed
