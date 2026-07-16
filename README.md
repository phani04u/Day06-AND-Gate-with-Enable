# Day 06 | AND Gate with Enable using Verilog HDL

## Project Overview

This project demonstrates the implementation of an **AND Gate with Enable** using **Verilog HDL**. The Enable (EN) signal controls whether the input is allowed to pass to the output. The design is implemented using **Behavioral Modeling** and verified using **Xilinx Vivado**.

---

## Objective

- Understand the working of an Enable signal.
- Learn Behavioral Modeling in Verilog HDL.
- Write a Verilog testbench.
- Verify the design using RTL simulation.
- Analyze the RTL schematic and simulation waveform.

---

## Boolean Expression

```
If EN = 1
    Y = A

If EN = 0
    Y = 0
```

Equivalent Boolean Expression:

```
Y = A & EN
```

---

## Truth Table

| A | EN | Y |
|---|----|---|
|0|0|0|
|0|1|0|
|1|0|0|
|1|1|1|

---

## Files Included

- Verilog HDL Source Code
- Testbench
- RTL Schematic
- Simulation Waveform
- Project Documentation (PDF)

---

## Tools Used

- Verilog HDL
- Xilinx Vivado
- RTL Simulation

---

## Learning Outcome

- Learned the working of an Enable signal.
- Implemented an AND Gate with Enable using Behavioral Modeling.
- Developed a Verilog testbench.
- Verified the design using RTL schematic and simulation waveform.

---

## Author

**Phaneendra Singudasu**  
B.Tech Student | RTL Design Learner | Verilog HDL Enthusiast

**100 Days RTL Design Challenge 🚀**
