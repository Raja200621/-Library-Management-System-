#  Library Management System - Java OOP Project

This is a simple **Library Management System** built using core Java principles to demonstrate Object-Oriented Programming (OOP)
concepts such as abstraction, encapsulation, inheritance, and polymorphism.

---

##  Features

- Add new books and users
- Display all books and users
- Issue books to users
- Return issued books
- Console-based user interaction

---

##  Tech Stack

- **Language:** Java
- **IDE:** VS Code (or any Java-supported IDE)
- **Execution:** Terminal / Command Prompt

---

##  Project Structure

LibraryManagement/
├── Book.java # Book class with properties and issue logic
├── User.java # User class with user details
├── Library.java # Core logic: manage books and users
├── Main.java # Entry point with menu-driven interface
└── README.md # Project documentation



---

##  OOP Concepts Used

| Concept             | How It's Used                                      |
|---------------------|----------------------------------------------------|
| **Abstraction**     | Defined classes like `Book`, `User`, and `Library` |
| **Encapsulation**   | Private fields with getters/setters                |
| **Polymorphism**    | Overridden `toString()` methods                    |
| **Inheritance**     | Ready for extensions (e.g., AdminUser extends User)|
| **Constructor Chaining** | Used for initializing objects                  |
| **Dynamic Binding** | At runtime via overridden methods                  |
| **HAS-A Relationship** | `Library` HAS-A `Book` and `User` list         |

---

##  How to Run

### Compile
```bash
javac *.java

### Run:
java Main



