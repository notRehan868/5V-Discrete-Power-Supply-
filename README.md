# Discrete 5V / 100mA DC Power Supply (No ICs)

### Author: Md Rehan Raza  
📌 [LinkedIn](https://linkedin.com/in/mdrehanraza) | [Email](mailto:khanrehan94407@gmail.com)

---

## 📖 Project Overview
This project demonstrates the design and implementation of a **5V regulated DC power supply** delivering up to **100 mA** output, built entirely from **discrete components (no integrated regulator ICs)**.  
It is suitable for powering small electronic circuits, sensor modules, and embedded applications.

---

## ⚡ Features
- Input: 230V AC (via step-down transformer)  
- Output: **5V ± 5% @ 100 mA**  
- Components: Transformer, bridge rectifier, filter capacitor, Zener diode (reference), BD139 transistor (series pass), resistors  
- Low-cost, educational design for ECE students  
- Includes **schematic diagrams, SPICE netlist, and documentation PDF**

---

## 🛠️ Block Diagram
![Schematic](./schematics/schematic.png)
230V AC → Step-down Transformer → Bridge Rectifier → Filter Capacitor → Zener + Transistor Regulator → 5V DC

---

## 📂 Repository Structure
schematics/
 ├── schematic.svg            # detailed circuit
 ├── schematic.pdf
 └── Discrete_5V_PSU.sch      # KiCad project
docs/
 └── Discrete_5V_100mA_NoIC_Summary.pdf
images/
 └── block_diagram.png        # simple flow diagram

