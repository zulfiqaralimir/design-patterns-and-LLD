---

## 🤝 Behavioral Design Patterns

Behavioral Design Patterns are concerned with **algorithms and the assignment of responsibilities between objects**.  
They focus not only on the **objects or classes themselves**, but also on the **communication and interaction** between them.  

These patterns often characterize **complex control flows** that are difficult to trace at runtime, making systems easier to extend and maintain.  

---

### 🔑 Types of Behavioral Design Patterns

#### 1. Chain of Responsibility Pattern  
- Achieves **loose coupling** by passing a request along a **chain of handlers**.  
- Each handler decides whether to process the request or forward it to the next handler.  

#### 2. Command Pattern  
- Encapsulates a **request as an object**, allowing it to be stored, queued, or executed later.  
- Useful for implementing **undo/redo** operations and task scheduling.  

#### 3. Interpreter Pattern  
- Defines a **grammatical representation** for a language.  
- Provides an **interpreter** to process and evaluate sentences in that language.  

#### 4. Mediator Pattern  
- Introduces a **mediator object** to handle communication between multiple objects.  
- Promotes **loose coupling** by preventing direct references between collaborating objects.  

#### 5. Memento Pattern  
- Captures and stores an object’s **internal state** without exposing its implementation.  
- Allows restoring the object to its previous state (useful for **checkpoints/undo**).  

#### 6. Observer Pattern  
- Establishes a **one-to-many dependency** between objects.  
- When the subject changes state, all **observers** are automatically notified and updated.  

#### 7. State Pattern  
- Allows an object to **change its behavior when its internal state changes**.  
- Replaces complex `if-else` blocks with **state-specific classes**.  

#### 8. Strategy Pattern  
- Defines a family of **algorithms**, encapsulates them, and makes them interchangeable.  
- Allows selecting an algorithm’s behavior at **runtime**.  

#### 9. Template Method Pattern  
- Defines the **skeleton of an algorithm** in the base class.  
- Lets subclasses override specific steps without changing the overall algorithm structure.  

#### 10. Visitor Pattern  
- Separates an algorithm from the objects it operates on.  
- Useful when you need to perform **new operations** on a group of similar objects without modifying their classes.  

---

## 📘 Summary
Behavioral Patterns focus on **communication, algorithms, and responsibilities**.  
They simplify **control flow** and improve **flexibility, reusability, and scalability** of software systems.  

---
