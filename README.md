# 8-Bit-Carry-Select-Adder-Using-Hybrid-Full-Adder-Architecture

## 📌 Overview
This project presents the design and performance analysis of an **8-bit Carry Select Adder (CSLA)** using a **Hybrid Full Adder (HFA)** architecture.  
The proposed design focuses on improving **speed, reducing power consumption, minimizing transistor count, and optimizing Power Delay Product (PDP)** for VLSI applications.

## 🚀 Features
- 8-bit Carry Select Adder implementation
- Hybrid Full Adder (PTL + GDI based)
- Reduced transistor count (22 MOSFETs per HFA)
- Low power consumption
- Improved speed and reduced delay
- Optimized Power-Delay Product (PDP)
- Designed using **GPDK 180nm Technology**

## 🧠 Problem Statement
Conventional Carry Select Adders improve speed but increase:
- Area usage
- Power dissipation
- Redundant logic

This project solves these limitations using Hybrid Full Adder based CSLA architecture.

## ⚙️ Proposed Solution
- Hybrid Full Adder implementation using:
  - Pass Transistor Logic (PTL)
  - Gate Diffusion Input (GDI)

### Boolean Equations
```text
SUM  = A ⊕ B ⊕ Cin
Cout = AB + Cin(A ⊕ B)
```

## 🏗 Architecture
The 8-bit CSLA consists of:
- Lower 4-bit HFA block
- Upper 4-bit HFA block for Cin = 0
- Upper 4-bit HFA block for Cin = 1
- 2:1 Multiplexer for final sum selection
- 2:1 Multiplexer for carry output

## 📊 Results
| Parameter | Value |
|---------|-------|
| Supply Voltage | 1.0V |
| Power Consumption | 1.8 µW |
| Delay | 6.9 ns |
| PDP | 12.42 fJ |

### Key Improvements
✅ Reduced power  
✅ Lower delay  
✅ Reduced transistor count  
✅ Better performance than conventional CSLA

## 🔬 Tools & Technology
- Cadence Virtuoso (or simulation tool used)
- GPDK 180nm
- CMOS VLSI Design
- Hybrid Full Adder Design

## 📸 Outputs
Includes:
- 1-bit HFA schematic
- Input/Output waveforms
- 8-bit CSLA block diagram
- Simulation results

## 🎯 Applications
- Arithmetic Logic Units (ALUs)
- DSP Processors
- Embedded Systems
- IoT Devices
- AI Accelerators

## 🔮 Future Scope
- Extend to 16-bit / 32-bit / 64-bit adders
- Implement in advanced CMOS nodes (90nm, 45nm)
- Integrate low-power optimization techniques
- Explore approximate/hybrid adders

## 📚 References
1. Ripple-Carry Adder Overview  
2. Carry Look-Ahead Adder  
3. Performance Comparison of CSLA and CLA  
4. BEC Based CSLA  
5. Low Power Area Efficient CSLA  
6. Full Adder Transistor-Level Designs  
7. Hybrid Full Adder for Low Power Applications

## ⭐ Conclusion
The proposed **HFA-based CSLA** overcomes drawbacks of conventional CSLA by reducing **power, delay, and area**, making it suitable for high-speed and low-power VLSI systems.
