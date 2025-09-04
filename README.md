# Gaussian Elimination Solver

## 📌 Description
This repository contains the implementation of the **Gaussian Elimination Algorithm**, a classical method used to solve systems of linear equations.  
It demonstrates step-by-step matrix transformations, from constructing the augmented matrix to converting it into **row echelon form** and finally performing **back substitution** to find the solution.

The project highlights numerical problem-solving skills, linear algebra understanding, and algorithmic implementation.

---

## 🧩 Features
- Solves systems of **n equations with n variables**.
- Implements **row switching, row scaling, and row replacement** operations.
- Handles augmented matrix construction automatically.
- Provides a **clean step-by-step transformation** of the matrix.
- Designed to solve **non-singular systems** with a unique solution.

---

## 🛠️ Algorithm Overview
Gaussian elimination is used to systematically reduce a system of equations into a simplified form for easy solution.

### **Steps Involved:**
1. **Create Augmented Matrix**  
   Combine coefficient matrix **A** and constants vector **B** into `[A | B]`.
2. **Row Echelon Transformation**  
   - Row Switching → Moves the pivot row to the top.
   - Row Scaling → Normalizes pivot elements.
   - Row Replacement → Eliminates variables step by step.
3. **Back Substitution**  
   Solve for variables starting from the last row.
4. **Final Solution**  
   Output the solved variable values.

---


