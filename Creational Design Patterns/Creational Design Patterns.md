
# 🎨 Creational Design Patterns

Creational Design Patterns focus on the **process of object creation** or problems related to object creation.  
They help in making a system **independent of how its objects are created, composed, and represented**.

<img width="801" height="401" alt="image" src="https://github.com/user-attachments/assets/cfbbca00-353a-47e2-8928-cf5abd5c3561" />





### 🔑 Types of Creational Design Patterns

#### 1. Factory Method Design Pattern  
- Separates the **construction of an object** from its implementation.  
- Allows creating objects **without specifying the exact class** to be instantiated.  

#### 2. Abstract Factory Method Design Pattern  
- An **extension of the Factory Method**, acting as a **super-factory**.  
- Used when the system needs to be **independent of how its objects are created** across multiple families.  
- Creates other factories that produce objects.  

#### 3. Singleton Design Pattern  
- Ensures a **class has only one instance** throughout the application.  
- Provides a **global point of access** to that instance.  
- Often used for logging, caching, or configuration management.  

#### 4. Prototype Design Pattern  
- Focuses on **cloning existing objects** instead of creating new ones from scratch.  
- Useful when object creation is **costly or complex**.  
- Provides flexibility in creating objects with dynamic states.  

#### 5. Builder Design Pattern  
- Separates the **construction of a complex object** from its representation.  
- Allows building objects **step by step**.  
- The same construction process can create **different representations**.  


## 📘 Summary
Creational Patterns **abstract the instantiation process**.  
They make the system more **flexible, reusable, and decoupled** from concrete classes.

---
