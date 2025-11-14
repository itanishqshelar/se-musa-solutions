**Coupling and Cohesion** are two important concepts in software engineering used to measure the quality of a module’s design.
**Cohesion refers to how closely the functions within a module are related**, whereas **Coupling refers to how dependent one module is on another**.
Good design aims for **high cohesion** and **low coupling**.

---

# **1. Types of Cohesion (High to Low)**

### **a) Functional Cohesion (Best)**

All elements of a module work together to perform **one single, well-defined function**.
Example: A function that calculates the sum of numbers.

### **b) Sequential Cohesion**

Output of one function becomes input to another inside the same module.
Example: Read data → process it → store the result.

### **c) Communicational (Informational) Cohesion**

Module’s functions are grouped because they operate on the **same data set**.
Example: A module that reads and updates the same customer record.

### **d) Procedural Cohesion**

Tasks are related because they must be performed in a **specific sequence**, though they perform different operations.
Example: A routine that checks input validity and then prints a message.

### **e) Temporal Cohesion**

Elements are grouped because they execute during the **same time period**.
Example: Initialization routines executed at program startup.

### **f) Logical Cohesion**

Elements perform logically similar tasks, and one is selected based on a condition.
Example: A module that handles keyboard, mouse, or touch input.

### **g) Coincidental Cohesion (Worst)**

Elements have **no meaningful relationship** and are grouped randomly.
Example: A module that performs logging, sorting, and printing.

---

# **2. Types of Coupling (Low to High)**

### **a) Data Coupling (Best)**

Modules communicate by passing **only necessary data**.
Example: `add(a, b)` – only required variables are shared.

### **b) Stamp Coupling**

Modules share a **data structure**, even when only a part of it is needed.
Example: Passing a whole record or object when a single field is used.

### **c) Control Coupling**

One module controls the behavior of another by passing **control information or flags**.
Example: A parameter “mode = 1 for save, 2 for print”.

### **d) External Coupling**

Modules depend on an **external interface, protocol, or hardware**.
Example: Two modules sharing a specific file format or communication protocol.

### **e) Common Coupling**

Modules share the **same global data**.
This increases dependency and risks unintended modifications.
Example: Multiple functions using the same global variable.

### **f) Content Coupling (Worst)**

One module directly **accesses or modifies** another module’s data or code.
Example: Jumping into another module’s code segment or modifying internal variables.

---

# **Conclusion**

- **High Cohesion** ensures that a module is focused, understandable, and reusable.
- **Low Coupling** ensures that modules are independent and changes in one module do not affect others.
  Together, both lead to a **modular, maintainable, and flexible software system**, which is the goal of good software design.

---
