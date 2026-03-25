#  Audio Input Preamplifier & PCB Design

This repository contains the complete design, simulation, and physical layout files for an analog audio input preamplifier with a regulated power supply. It was built as a university hardware project, taking a theoretical schematic all the way to manufacturing-ready files.

## What's this about?
Instead of just doing the math on paper, I had to adapt a base schematic to meet a strictly customized set of parameters (tuning the circuit for a 200mV input sensitivity and a 1000 kOhm input impedance, typical for a ceramic pick-up). 

The engineering process involved:
* **Circuit Simulation:** Before routing anything, I validated the stability and performance of the Class-A amplifier stages using transient and frequency response simulations.
* **Component Substitution:** Swapping out theoretical parts for physically available counterparts (like the BC109C transistors) and making sure the math still checks out.
* **PCB Layout:** Moving from the schematic to **OrCAD PCB Editor**, where I managed trace routing, component placement, and via configurations.

## Tools Used
* **OrCAD Capture CIS** (for schematics and SPICE simulation)
* **OrCAD PCB Editor** (for the physical board layout)

## Project Showcase

<img width="1423" height="611" alt="schematic" src="https://github.com/user-attachments/assets/d62d0594-28cf-407f-8829-2f15c0fe9f1d" />

![layout_pcb](https://github.com/user-attachments/assets/4ce40a3d-0721-45c6-8c6e-4bc93eb5934b)

## What's in this repo?
If you want to check out the technical details, you'll find:
* **Project Documentation:** Detailed math, component choices, and simulation graphs (Transient & Bode plots).
* **Bill of Materials (BOM):** The exact list of resistors, capacitors, transistors, and power supply components used to build the circuit.
* **Gerber Files:** The exported manufacturing files, ready to be sent to a PCB fab.

