# ⏱ FPGA Two-Mode Digital Timer (Verilog HDL)

A modular two-mode digital timer implemented in Verilog HDL and deployed on the DE10-Lite FPGA development board. The project demonstrates RTL design, finite state machine control, clock division, and hardware-level validation.
<img width="318" height="231" alt="image" src="https://github.com/user-attachments/assets/e5515009-74a9-4180-b2b5-19da471a050f" />

---

## 📌 Overview

This project implements a configurable digital timer capable of operating in two distinct modes (e.g., count-up / count-down or dual timing behaviours) using hardware description language (Verilog).

The design was developed using a hierarchical, modular RTL structure and verified through simulation before hardware deployment.

---

## ⚙️ Key Features

- Two operational timing modes  
- Finite State Machine (FSM) based control  
- Clock division from FPGA system clock  
- Seven-segment display output  
- Hardware push-button input handling  
- Fully simulated and hardware-validated design  

---

## 🧠 Technical Highlights

### RTL Architecture
- Hierarchical, modular Verilog design
- Clear separation of timing logic and control logic
- Synthesizable HDL structure

### State Machine Design
- Explicit state encoding
- Controlled transitions between timing modes
- Deterministic behaviour across clock cycles

### Clock Management
- Derived lower-frequency timing signals from FPGA master clock
- Ensured stable and accurate second-level timing behaviour

### Verification
- Functional verification using ModelSim waveform simulation
- Timing behaviour validated prior to hardware deployment
- Confirmed correct operation on DE10-Lite FPGA board

---

## 🛠 Tools Used

- Verilog HDL  
- Intel Quartus Prime  
- ModelSim (Simulation)  
- DE10-Lite FPGA Development Board  

---

## 🚀 Build & Deployment

1. Open project in **Intel Quartus Prime**
2. Compile design
3. Run ModelSim simulation using testbench
4. Program FPGA via USB-Blaster
5. Verify behaviour using on-board switches and displays

---

## ▶️ Example Behaviour

Mode 1:
- Timer counts up in real time
- Displays value on seven-segment output

Mode 2:
- Timer counts down from preset value
- Resets or transitions based on state logic

---

## 📊 Concepts Demonstrated

- Hardware description language proficiency  
- Digital system design principles  
- Finite State Machine implementation  
- Clock domain reasoning  
- Simulation-driven verification workflow  
- Hardware debugging and validation  

---

## 🔮 Potential Improvements

- Add programmable preset value
- Implement debouncing for input switches
- Extend to multi-digit display expansion
- Integrate UART output for debugging

---

## 👤 Author

Christoff Lotter
MEng Electronic & Electrical Engineering  
Interested in FPGA design, embedded systems, and digital architecture.
