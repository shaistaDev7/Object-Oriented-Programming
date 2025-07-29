# 🧠 Object-Oriented Programming (OOP)

Object-Oriented Programming (OOP) is a powerful programming paradigm based on the concept of **"objects"**. It allows for better organization, code reuse, and real-world modeling in software development.

---

## 🚀 What is OOP?

**OOP (Object-Oriented Programming)** is a style of programming where code is organized into **classes** and **objects**.

- **Class**: A blueprint for creating objects.
- **Object**: An instance of a class containing both data and methods.

---

## 📘 Key Concepts of OOP

| 🔑 Concept        | 💡 Description                                                                 |
|------------------|---------------------------------------------------------------------------------|
| **Class**        | Blueprint for creating objects                                                 |
| **Object**       | Instance of a class                                                            |
| **Encapsulation**| Hides internal states and requires all interaction to be performed through methods |
| **Inheritance**  | Enables new classes to receive properties and behavior from existing classes   |
| **Polymorphism** | Same interface, different implementations                                      |
| **Abstraction**  | Hides complexity and only shows essential features                             |

---

## 🌟 Advantages of OOP

| ✅ Benefit           | 📌 Explanation                                                                  |
|----------------------|---------------------------------------------------------------------------------|
| **Modularity**        | Code is divided into independent objects                                       |
| **Reusability**       | Use existing code via inheritance                                              |
| **Maintainability**   | Easy to manage, update, and debug                                              |
| **Scalability**       | Great for building complex and large applications                              |
| **Flexibility**       | Polymorphism allows interchangeable components                                 |
| **Data Security**     | Encapsulation protects internal object state                                   |

---

## 🐍 Simple Example in Python

```python
class Car:
    def __init__(self, brand, model):
        self.brand = brand
        self.model = model

    def start_engine(self):
        print(f"{self.brand} {self.model}'s engine started.")

# Create an object
my_car = Car("Toyota", "Corolla")
my_car.start_engine()

