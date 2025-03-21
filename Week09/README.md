[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MMj2nZMu)
# Rsearch and Reflection Journal
Research and Reflection Journal for DGL 104 course


# **Course Notes - Week 8 to Week 12**

*********************************************
## Week 9 (March 4)

### **Class Content**

#### **Fundamental Principles of GoF Design Patterns**
The GoF design patterns are based on the following two key principles:
1. **Program to an interface, not an implementation**  
   - Writing code that depends on interfaces rather than concrete implementations ensures flexibility and maintainability.
2. **Favor object composition over class inheritance**  
   - Instead of relying on deep inheritance hierarchies, using object composition makes code more modular and easier to manage.

#### **Categories of Design Patterns**
Design patterns are generally classified into three main categories:
1. **Creational Patterns** – Efficiently manage object creation.  
   - **Examples:** Singleton Pattern, Factory Pattern  
2. **Structural Patterns** – Define how classes and objects are composed.  
   - **Examples:** Adapter Pattern, Composite Pattern  
3. **Behavioral Patterns** – Manage communication and interactions between objects.  
   - **Examples:** Observer Pattern, Strategy Pattern  

#### **Common Design Patterns**
##### **1. Singleton Pattern (Creational Pattern)**
- **Purpose:** Ensures that only one instance of a class exists throughout the application.  
- **Common Use Cases:**  
  - Database connections  
  - Configuration management  
  - Logging systems  

##### **2. Observer Pattern (Behavioral Pattern)**
- **Purpose:** Allows dependent objects (**Observers**) to be automatically notified of state changes in a subject (**Subject**).  
- **Common Use Cases:**  
  - GUI event handling  
  - Reactive data updates  

#### **Summary**
Design patterns improve software design by enhancing efficiency and maintainability. However, they are not universal solutions for all problems. Choosing the appropriate pattern is crucial to avoid unnecessary complexity.  
It is important to **"avoid excessive inheritance"** and **"utilize object composition effectively"** for better code organization.


1. Creational DP -> Singleton, Factory, Builder, Prototype
   - A Singleton is a class that can be instantiated only once and provides global access to that single instance. Because this single instance can be shared across the entire application, the Singleton pattern is well-suited for managing global state within an application.

   - The Builder is a creational design pattern that allows complex objects to be constructed step by step. This pattern enables you to produce different types and representations of objects using the same construction code.

   - The Prototype pattern is a creational design pattern that enables copying existing objects without depending on their specific classes.

   - The Factory Method is a creational design pattern that defines an interface for creating objects in a superclass, but allows subclasses to alter the type of objects that will be created.

2. Structural DP -> Adapter, Decorator, Facade, Composite
   - The Adapter pattern is used to wrap an incompatible object with an adapter so that it becomes compatible with another class.

   - The Decorator pattern allows you to dynamically change the behavior of an object at runtime by wrapping it with a decorator class.

   - A Facade is an object that provides a simplified interface to a larger body of code, such as a class library.

   - The Composite pattern allows clients to treat individual objects and groups of objects in a uniform way.
   - 
3. Behavioral DP -> Observer, Strategy, Command, State
   - The Observer pattern consists of two roles: the Subject (being observed) and the Observer (observing). When the state of the Subject changes, it notifies all Observers. This pattern is effective when you need to perform actions in response to state changes.

   - The Strategy design pattern consists in letting a calling code use one of several possible algorithms, by hiding them behind an interface.

   - The Command pattern encapsulates a request as an object, allowing parameterization of clients with different requests.

   - The State design pattern is useful when an object can be in several formalized states. 


### References
   - Class video : Design patterns https://www.youtube.com/watch?v=A9sAIokPGsQ&t=1s
   - Singleton https://zenn.dev/morinokami/books/learning-patterns-1/viewer/singleton-pattern
   - Structural DP https://techracho.bpsinc.jp/hachi8833/2020_12_11/46069
   - Behavioral DP https://zenn.dev/mossan_hoshi/books/84487f17784b44


