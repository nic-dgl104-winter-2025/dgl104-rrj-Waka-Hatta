[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MMj2nZMu)
# Rsearch and Reflection Journal
Research and Reflection Journal for DGL 104 course


# **Course Notes - Week 8 to Week 12**

---
## Week 8 (March 4)

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


### **Community code project Progress** *********************************************
  - **Create and review a Database ER diagram**  
  - **Research the setup process for a React development environment**  
    - **Reference:** [Learn React](https://react.dev/learn)


---
## Week 9 (March 11)
### **Class Content** *******************************************************************
#### **MV* PATTERNS**

1. Creational DP -> Singleton, Factory, Builder, Prototype
2. Structural DP -> Adapter, Decorator, Facade, Composite
3. Behavioral DP -> Observer, Strategy, Command, State

[1] MVVM (Model-View-ViewModel)
   - MVVM is a UI-based architectural pattern similar to MVC but focuses on data binding.
   - he Model contains business logic and data.
   - The View is responsible for UI representation.
   - The ViewModel acts as a bridge between the Model and View without directly referencing the View.
   - Data Binding is a key feature, reducing boilerplate code and improving efficiency.
   - MVVM is particularly useful when real-time data updates are required.
   - It is widely used in modern Android development, Swift UI, and web frameworks like Vue, Angular, and React.

[2] MVC (Model-View-Controller)
   - MVC is another UI architectural pattern.
   - The Model handles data, storage, and business logic.
   - The View presents data but does not store or process it.
   - The Controller manages interactions between Model and View.
   - MVC is common in web frameworks like Ruby on Rails, Django, Angular, and Vue.
   - While historically used in iOS and Android, it has been largely replaced by MVVM for modern mobile development.

### References
   - Design Patterns https://en.wikipedia.org/wiki/Design_Patterns
   - MVC vs MVVM https://www.issoh.co.jp/column/details/2051/

### **Community code project Progress** *********************************************
  - **Develop using the MVC pattern**
  - **DB construction**
  - **UI determination**
    - User login 
    - Task management 
    - User management 



---
## Week 10 (March 18)
### **Class Content** *******************************************************************
### **Community code project Progress** *********************************************

---
## Week 11 (March 25)
### **Class Content** *******************************************************************
### **Community code project Progress** *********************************************

---
## Week 12 (April 1)
### **Class Content** *******************************************************************
### **Community code project Progress** *********************************************