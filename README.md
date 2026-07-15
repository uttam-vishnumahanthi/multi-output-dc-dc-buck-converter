# Multi-Output DC-DC Buck Converter

A compact, high-efficiency multi-output DC-DC buck converter designed to convert a variable **16–28 V DC input** into regulated **3.3 V**, **5 V**, and **12 V** outputs. This project focuses on reliable power conversion, PCB optimization, modular hardware design, and future integration of protection circuitry for embedded and autonomous systems.

---

## Project Overview

This project aims to develop a compact power supply module capable of providing multiple regulated voltage rails from a single DC source. The converter is intended for embedded electronics, robotics, autonomous systems, and other applications requiring stable and efficient power distribution.

The current implementation includes a fully designed and tested **5 V buck converter** using the **LM2596-ADJ** switching regulator. Future work includes the implementation of 3.3 V and 12 V outputs, advanced protection features, and PCB optimization.

---

## Features

- Input Voltage: **16 V – 28 V DC**
- Regulated Outputs:
  - 3.3 V
  - 5 V
  - 12 V
- High-efficiency buck converter architecture
- LM2596-ADJ based design
- Compact PCB layout
- Low ripple output
- Hardware implementation and testing
- KiCad PCB design
- Proteus simulation
- Modular architecture for future expansion

---

## Hardware Specifications

| Parameter | Value |
|-----------|--------|
| Input Voltage | 16–28 V DC |
| Output Voltages | 3.3 V, 5 V, 12 V |
| Converter Type | Buck (Step-Down) |
| Main Controller | LM2596-ADJ |
| PCB Design Tool | KiCad |
| Simulation Tool | Proteus Professional |

---

## Design Workflow

1. Requirement Analysis
2. Buck Converter Design
3. Component Selection
4. Simulation in Proteus
5. PCB Design in KiCad
6. Hardware Assembly
7. Performance Testing
8. Future Design Improvements

---

## Current Progress

✔ Requirement analysis completed

✔ LM2596 buck converter designed

✔ Simulation completed

✔ PCB designed in KiCad

✔ Hardware assembled

✔ Initial hardware testing completed

✔ 3.3 V output implementation

✔ 12 V output implementation

⬜ Protection circuitry

⬜ Thermal optimization

⬜ EMI/EMC improvements

---

## Future Improvements

- Over Voltage Protection (OVP)
- Over Current Protection (OCP)
- Reverse Polarity Protection
- Thermal Shutdown
- EMI/EMC Optimization
- Improved PCB Layout
- Multi-output regulation
- Military-grade reliability practices
- Efficiency optimization
- Wide-temperature operation

---

## Applications

- Embedded Systems
- Robotics
- Autonomous Vehicles
- Industrial Electronics
- Sensor Power Distribution
- Automotive Electronics
- Research and Development Platforms

---

## Tools Used

- KiCad
- Proteus Professional
- LM2596-ADJ
- LM5145
- Digital Multimeter
- Oscilloscope
- Soldering Workstation

---

## Author

**Uttam V**

Electronics and Computer Engineering

---

## License
MIT License

Copyright (c) 2026 uttam-vishnumahanthi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
