[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MMj2nZMu)
# Rsearch and Reflection Journal
Research and Reflection Journal for DGL 104 course


# **Course Notes - Week 8 to Week 12**

## Week 12 (March 25)
### **Class Content** ********************************************************
#### **FUNCTIONAL PARADIGM**

[1] Imperative vs Declarative
### Imperative:
- Describes *how* a program should run in detail.
- Based on statements that change the program's state, this paradigm describes how to perform processing. It encompasses procedural, structured, modular, and object-oriented approaches.
- Example: Use a while loop and if statements to extract even numbers from a list.

### Declarative:
- Describes *what* you want to achieve.
- A programming paradigm with mathematical and logical characteristics, where you describe what should be done. It avoids side effects and emphasizes the implementation of pure functions. Includes functional, logic, and dataflow programming styles.
- Example: Use Kotlin's filter method to extract even numbers.
- More concise, readable, and maintainable.

### (Procedural)
- Procedural Programming:
Built on imperative programming, it adds structure and modularity by defining and calling procedures. Languages like FORTRAN, COBOL, BASIC, and C fall under this category.

---

[2] Benefits of Functional Programming: Reducing Side Effects

- **What are side effects?
- FP avoids this by using immutable variables (once defined, their values don’t change).
- This results in more predictable and bug-resistant code.

---

[3] How Can Functional Programming Work Without Loops?

### Three Key Traits of Pure Functional Languages:

1. **Determinism**:
   - Functions always return the same output for the same input.

2. **Higher-Order Functions**:
   - Functions can take other functions as arguments or return them as results.

3. **Recursion**:
   - Functions can call themselves.

---

### Many modern languages are “multi-paradigm”:
- Languages like Swift, JavaScript, Kotlin, and Java support both OOP and functional styles.

### Functional tools are especially useful with collections:
- **filter**: Selects elements based on a condition
- **map**: Applies a function to each element
- **sort**: Sorts the list (optionally with custom conditions)

---

## Summary
- Functional programming makes code shorter, more readable, and reduces bugs.
- Even in OOP languages, you can apply many functional concepts.
- Especially useful for working with collections like lists and arrays.

---
### References
   - Class video : dgl104 functional paradigm https://www.youtube.com/watch?v=_uXZ8HvHH7o&t=1s
   - https://zenn.dev/wooootack/scraps/18f19f9c549bf4