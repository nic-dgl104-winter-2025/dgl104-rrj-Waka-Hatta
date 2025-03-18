[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MMj2nZMu)
# Rsearch and Reflection Journal
Research and Reflection Journal for DGL 104 course


# **Course Notes - Week 8 to Week 12**

---

---
## Week 8 (February 25)
### **Class Content** 

#### **User Stories:
Written in natural language, e.g., "As a user, I can upload a profile picture."
Help teams align on the app’s behavior and goals.
Good for communication but lack technical details.
Might miss performance needs or non-functional requirements like speed.

#### **Technical Design Document (TDD):
A higher-level guide covering technical approaches, chosen technologies, and architecture (like MV* patterns).
Includes testing plans and performance expectations.
Useful in early development stages but often outdated once coding starts.

#### **Functional Requirements:
Describe app features as input-output relationships, similar to functions in programming.
Often derived from user stories or use cases.
Provide clarity on how data moves and transforms within the app.


### **Required research** 
#### **RESEARCH A NEW LANGUAGE to the Slack
I researched about Lua.
Lua is a programming language originally developed to be embedded in C programs, and as a scripting language, it is known for its high execution speed. Lua is often used in game development and plugin development. One of Lua's unique characteristics is that it is frequently utilized as an embedded language within other applications. For example, in game development, parts that require high-speed processing are implemented in C, while Lua is used for scripting scenarios and sections that need to be flexibly modified. The main features of Lua include easy embeddability, high extensibility, being free software, and fast execution speed.

#### **WRITE A USER STORY to the Slack
Hana, a junior high school student, wants to start learning English from the basics, which will help her in her future studies and travels. Duolingo allows her to learn English from the basics in a game-like way, and the ranking function helps her stay motivated and continue.
John, a busy working professional, wants to practice business English in a short amount of time, which will improve his communication with overseas clients. He uses Duolingo's Business English category to practice listening during his commute, and on weekends he practices business conversation through role-playing.

### **Community code project Progress** 


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


### **Community code project Progress** *********************************************
  - **Create and review a Database ER diagram**  
  - **Research the setup process for a React development environment**  
    - **Reference:** [Learn React](https://react.dev/learn)


---
## Week 10 (March 11)
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
## Week 11 (March 18)
### **Class Content** *******************************************************************
### **Community code project Progress** *********************************************

---
## Week 12 (March 25)
### **Class Content** *******************************************************************
### **Community code project Progress** *********************************************
