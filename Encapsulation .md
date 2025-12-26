<img width="1136" height="343" alt="Screenshot 2025-12-26 203431" src="https://github.com/user-attachments/assets/3b3ae3d5-4ea7-4d5c-8434-583a05646d44" /># 🐍 Python OOP: Encapsulation with Private Members

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
    def __init__(self, length, breadth):
        self.__length = length     
        self.__breadth = breadth
        print(f"Rectangle created with Length = {self.__length} and Breadth = {self.__breadth}")
rect = Rectangle(5, 3)
```

## Output
<img width="1136" height="343" alt="Screenshot 2025-12-26 203431" src="https://github.com/user-attachments/assets/d7a9be54-f89b-455a-813f-7e38caa6fc5d" />

## Result

The code is executed successfully.
