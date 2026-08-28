# XNOR Gate using SystemVerilog

## 📌 About the Project

This project demonstrates the implementation and simulation of a **2-input XNOR (Exclusive-NOR) Gate** using **SystemVerilog**.

The XNOR gate produces a HIGH (`1`) output when both inputs are the **same** and a LOW (`0`) output when the inputs are different.

## ⚡ How XNOR Gate Works

XNOR stands for **Exclusive-NOR**.

In simple terms:

- Same inputs → Output `1`
- Different inputs → Output `0`

### Boolean Expression

**Y = A ⊙ B**

or

**Y = ~(A ⊕ B)**

### Truth Table

| A | B | Output (Y) |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

## 🔬 Simulation & Verification

The XNOR gate was verified using a **SystemVerilog testbench** by applying all possible combinations of the two input signals.

The simulation output was compared with the XNOR truth table to confirm correct functionality.

## 🛠️ Tools & Technologies

- **SystemVerilog** – Hardware Description Language
- **EDA Playground** – RTL simulation and verification
- **GitHub** – Version control and project documentation

## 🎯 Applications

XNOR gates are commonly used in:

- Equality Comparators
- Digital Comparators
- Error Detection Circuits
- Parity Circuits
- Arithmetic Circuits
- Digital Logic Systems

## 📚 Learning Outcomes

Through this project, I learned:

- Fundamentals of XNOR logic
- XNOR Boolean expression and truth table
- SystemVerilog RTL concepts
- Testbench-based functional verification
- Digital circuit simulation using EDA Playground
- GitHub project documentation

