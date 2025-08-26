# 3x3 Matrix Multiplier – Verilog Implementation

## Overview

This project implements a **3x3 Matrix Multiplier** using combinational logic in Verilog. Two 3x3 input matrices (**A** and **B**), each with 8-bit elements, are multiplied to produce a 3x3 output matrix (**C**) with 19-bit wide elements.

- All code and testbenches are written in Verilog.
- Simulations are performed using **Xilinx ISE** and **Icarus Verilog/GTKWave**.
- Waveforms and schematics are included for visualization and verification.

---

## Features

- Performs 3x3 matrix multiplication (A × B = C) with 8-bit signed integer inputs.
- Fully combinational design (no clock required).
- Suitable for FPGA implementation and functional testbenches.
- Provided waveforms and simulation results for verification.

---

## Tools Used

- **Xilinx ISE** (schematic, synthesis, and simulation)
- **Icarus Verilog** (functional simulation)
- **GTKWave** (waveform viewing)

---

## Block Diagrams & Schematics

### RTL Schematic

![RTL Schematic](RTL%20Schematic.png)

---

### Technological Schematic

![Technological Schematic](Technological%20Schematic.png)

---

## Waveforms

### Xilinx ISE Output

![Xilinx ISE Waveform 1](Xilinx%20ISE%20Waveform%201.png)
![Xilinx ISE Waveform 2](Xilinx%20ISE%20Waveform%202.png)

---

### GTKWave Simulation Output

![GTK Wave output](GTK%20Wave%20output.png)

---

### Icarus Verilog Output

![Icarus Output](Icarus%20Output.png)

---

## How It Works

- Each input matrix element is **8 bits wide**.
- The output matrix (**C**) has **19-bit wide** elements.
- Computation is fully combinational: changes in inputs reflect instantly in outputs.
- Code is organized with generate blocks and always blocks for clarity.
- Testbenches verify function with various input patterns.

---

## Usage

1. **Clone this repository.**
2. Simulate using Xilinx ISE or Icarus Verilog.
3. View included waveform images for reference results.
4. Compare your simulation results with provided outputs.

---

## File Structure

- `matrix_multiplier.v` - Verilog implementation
- `matrix_multiplier_tb.v` - Testbench
- Schematic and waveform images for simulation

---

## Credits

Project by **Tejas Mallah**  
Verilog | Xilinx ISE | Icarus Verilog | GTKWave

---
