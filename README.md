# Student Management System (Java)

## OOP vs Procedural Approach – Detailed Explanation

---

## 📌 Project Overview

This project is a simple **Student Management System** developed in Java.
It takes input from the user (name, age, roll number, course) and displays the student details.

The same system is implemented in two different programming approaches:

* **Procedural Programming**
* **Object-Oriented Programming (OOP)**

---

# 🔷 Procedural Programming Approach

## 📖 Definition

Procedural programming is a programming paradigm where the program is written as a sequence of instructions (steps).
It focuses on **functions and logic**, not on objects.

---

## ⚙️ How It Works in This Project

* All data is stored in **simple variables**
* Logic is written directly inside the `main()` method
* No classes (except Main), no objects
* Data and functions are not separated

---

## 🧠 Example Concept

```java
String name;
int age;
```

Data is directly accessed and modified.

---

## ✅ Advantages

* Simple and easy to understand
* Less code for small programs
* Good for beginners

---

## ❌ Disadvantages

* No data security
* Difficult to manage large projects
* Code reuse is limited
* Not modular

---

## Procedural Code

Link : https://github.com/aqsamustafa101-cell/Procedural_Code

---

# 🔷 Object-Oriented Programming (OOP)

## 📖 Definition

OOP is a programming paradigm based on **objects and classes**.
It organizes code into reusable and structured components.

---

## ⚙️ How It Works in This Project

* Data is stored in **classes (Person, Student)**
* Object is created in `main()` method
* Uses:

  * **Encapsulation**
  * **Inheritance**

---

# 🔹 Encapsulation

## 📖 Definition

Encapsulation means **hiding data** and allowing access through methods.

## ⚙️ In This Project

* Variables are declared `private`
* Accessed using getter/setter methods

```java
private String name;

public void setName(String name) {
    this.name = name;
}
```

## ✅ Benefits

* Data security
* Controlled access
* Clean structure

---

# 🔹 Inheritance

## 📖 Definition

Inheritance allows one class to **use properties of another class**

## ⚙️ In This Project

```java
class Student extends Person
```

* `Student` class inherits:

  * name
  * age
* No need to rewrite code

## ✅ Benefits

* Code reuse
* Less duplication
* Easy maintenance

---

## OOP BASE Code :

Link : https://github.com/aqsamustafa101-cell/OOP_Base_Code

---

# 🔄 Key Differences (OOP vs Procedural)

| Feature       | Procedural      | OOP                      |
| ------------- | --------------- | ------------------------ |
| Structure     | Functions/Steps | Classes & Objects        |
| Data Security | No              | Yes (Encapsulation)      |
| Reusability   | Low             | High                     |
| Complexity    | Simple          | Better for large systems |
| Maintenance   | Difficult       | Easy                     |

---

# 🎯 Conclusion

* **Procedural Programming** is best for small and simple programs
* **OOP** is better for real-world and large applications

In this project:

* Procedural version shows **basic logic**
* OOP version shows **real-world structure and best practices**

---

# 💡 Viva Tip (Important)

If examiner asks:

👉 *"Which approach is better?"*

Answer:

> OOP is better because it provides data security, code reusability, and better structure for large applications, while procedural programming is only suitable for small programs.

---

## ✅ End of File
