
# 🏗️ Structural Design Patterns

Structural Design Patterns solve problems related to how **classes and objects are composed or assembled** to form larger, more flexible, and efficient structures.  
- **Structural class patterns** use inheritance to compose interfaces or implementations.  
- **Structural object patterns** use composition to assemble behaviors at runtime.

  <img width="801" height="401" alt="image" src="https://github.com/user-attachments/assets/619359ed-86d3-4395-b381-51e1d156007a" />



### 🔑 Types of Structural Design Patterns

#### 1. Adapter Design Pattern  
- Converts the **interface of a class** into another interface that clients expect.  
- Enables classes with **incompatible interfaces** to work together.  

#### 2. Bridge Design Pattern  
- Decouples **Abstraction** from **Implementation** so they can vary independently.  
- Client code interacts only with the abstraction, without worrying about implementation details.  

#### 3. Composite Design Pattern  
- Used to **compose objects into tree structures** to represent part-whole hierarchies.  
- Allows clients to treat **individual objects and groups of objects uniformly**.  

#### 4. Decorator Design Pattern  
- Dynamically adds **functionality or behavior** to an object without modifying its class.  
- Unlike inheritance (compile-time extension), decorators provide **runtime flexibility**.  

#### 5. Facade Design Pattern  
- Provides a **unified high-level interface** to a set of interfaces in a subsystem.  
- Simplifies complex systems by making them easier to use.  

#### 6. Flyweight Design Pattern  
- Minimizes memory usage by **sharing common parts of objects** instead of creating new ones.  
- Useful when dealing with **a large number of similar objects**.  

#### 7. Proxy Design Pattern  
- Acts as a **placeholder or surrogate** for another object.  
- Controls access to the real object (e.g., security, lazy initialization, remote access).  
- Related in structure (but not purpose) to Adapters and Decorators.  


## 📘 Summary
Structural Patterns focus on **class and object composition**.  
They help make systems **easier to understand, scalable, and more maintainable**.  

