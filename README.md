# 🧠 Programming Principles & Patterns

> A practical guide to writing **clean, maintainable, and scalable code** using proven software engineering principles and design patterns.
---

## 📑 Table of Contents

* [🚀 Why Programming Principles Matter](#-why-programming-principles-matter)
* [🧩 Core Programming Principles](#-core-programming-principles)
* [🏗️ Design Pattern Categories](#-design-pattern-categories)
* [⚙️ Best Practices](#️-best-practices)
* [🔍 Real-World Examples](#-real-world-examples)
* [🛠️ Tech Context](#️-tech-context)
* [📌 How to Use](#-how-to-use)
* [📖 References](#-references)
* [👨‍💻 Author](#-author)

---

## 🚀 Why Programming Principles Matter

Programming principles help developers:

* Write clean and readable code
* Reduce complexity and bugs
* Improve maintainability and scalability
* Build robust and production-ready systems

> Good code is not just about working — it's about being understandable and extensible.

---

## 🧩 Core Programming Principles

### 🔹 SOLID Principles

* **S – Single Responsibility Principle (SRP)**
  A class should have only one reason to change.

* **O – Open/Closed Principle (OCP)**
  Open for extension, closed for modification.

* **L – Liskov Substitution Principle (LSP)**
  Subtypes must be replaceable for base types.

* **I – Interface Segregation Principle (ISP)**
  Prefer smaller, specific interfaces.

* **D – Dependency Inversion Principle (DIP)**
  Depend on abstractions, not implementations.

---

### 🔹 DRY (Don't Repeat Yourself)

* Avoid duplication
* Reuse logic across the system

---

### 🔹 KISS (Keep It Simple, Stupid)

* Keep code simple and easy to understand
* Avoid unnecessary complexity

---

### 🔹 YAGNI (You Aren’t Gonna Need It)

* Build only what is required
* Avoid over-engineering

---

### 🔹 Separation of Concerns (SoC)

* Divide system into independent modules
* Each module handles one responsibility

---

### 🔹 Composition Over Inheritance

* Prefer combining objects over extending classes
* Promotes flexibility and reuse

---

### 🔹 Law of Demeter (LoD)

* Avoid deep chaining
* Interact only with direct dependencies

---

### 🔹 Principle of Least Astonishment (POLA)

* Code should behave as expected
* Avoid surprises

---

### 🔹 Fail Fast

* Detect errors early
* Stop execution immediately

---

### 🔹 Convention Over Configuration

* Use sensible defaults
* Reduce manual configuration

---

## 🏗️ Design Pattern Categories

### 🟢 Creational Patterns

* Singleton
* Factory Method
* Abstract Factory
* Builder
* Prototype

---

### 🔵 Structural Patterns

* Adapter
* Bridge
* Composite
* Decorator
* Facade
* Proxy

---

### 🔴 Behavioral Patterns

* Observer
* Strategy
* Command
* Iterator
* State
* Chain of Responsibility

---

## ⚙️ Best Practices

* Write clean and readable code
* Follow consistent naming conventions
* Use proper exception handling
* Write unit tests
* Prefer immutability
* Avoid tight coupling

---

## 🔍 Real-World Examples

### ❌ Bad Code (Violates SRP)

```java
class UserService {
    public void saveUser() {}
    public void sendEmail() {}
}
```

### ✅ Good Code (Follows SRP)

```java
class UserService {
    public void saveUser() {}
}

class EmailService {
    public void sendEmail() {}
}
```

---

### 🔍 DRY Example

❌ Bad:

* Same validation logic repeated in multiple classes

✅ Good:

* Create a shared utility/service for validation

---

### 🔍 KISS Example

❌ Bad:

* Overly complex logic for simple conditions

✅ Good:

* Use simple and readable conditions

---

## 🛠️ Tech Context

These principles are widely used in:

* Java / Spring Boot
* Microservices Architecture
* REST API Design
* System Design Interviews

---

## 📌 How to Use

* Use this repo for interview preparation
* Apply these principles in real-world projects
* Refer during system design discussions

---

## 📖 References

* Clean Code – Robert C. Martin
* Design Patterns – GoF
* Refactoring – Martin Fowler

---

## 👨‍💻 Author

* Abhishek Hinge
* GitHub: https://github.com/abhishekhinge

---

## ⭐ Summary

> Write simple code (KISS),
> avoid duplication (DRY),
> build only what's needed (YAGNI),
> and structure using SOLID principles.
