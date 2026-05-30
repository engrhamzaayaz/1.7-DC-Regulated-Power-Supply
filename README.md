# 1.7V DC Regulated Power Supply using Zener Diode


## Overview
This project presents the design and implementation of a **1.7V DC Regulated Power Supply** using a **Zener diode** as the core voltage regulation component. The goal was to convert an unregulated DC input into a stable, regulated 1.7V DC output — regardless of input voltage fluctuations or load variations.

The project followed a complete development workflow: from theoretical circuit design and LTSpice simulation to physical breadboard implementation and result verification using a digital multimeter.

This was completed as a **semester project** for the Electronics/Circuit Analysis course.

---

## 👥 Team
| Name | Role |
|------|------|
| Hamza Ayaz | Circuit Design, Simulation, Hardware Implementation |
| Ali | Hardware Assembly, Testing |
| Muneeb | Circuit Analysis, Documentation |

---

## 👨‍🏫 Supervised By
- **Dr. M. Aqil**
- **Dr. M. Riaz**

---

## 🛠️ Tools Used
| Tool | Purpose |
|------|---------|
| LTSpice | Circuit simulation and waveform analysis |
| Breadboard | Physical circuit prototyping |
| Digital Multimeter | Output voltage verification |
| Resistors, Zener Diode | Core circuit components |

---

## ⚡ Circuit Description

### How a Zener Diode Regulates Voltage
A **Zener diode** is a special type of diode designed to operate in the **reverse breakdown region**. Unlike a normal diode, when the reverse voltage across a Zener diode reaches its **breakdown voltage (Vz)**, it allows current to flow while maintaining a nearly **constant voltage** across its terminals.

### Working Principle of This Circuit
1. An unregulated DC voltage is applied at the input
2. A **series resistor (Rs)** is connected to limit the current flowing through the Zener diode
3. The Zener diode is connected in **reverse bias** across the output/load
4. When input voltage exceeds 1.7V, the Zener enters breakdown and clamps the output to a stable **1.7V DC**
5. Any excess voltage is dropped across the series resistor

### Key Formula
Rs = (Vin - Vz) / (Iz + IL)
Where:
- `Vin` = Input voltage
- `Vz` = Zener breakdown voltage (1.7V)
- `Iz` = Zener current
- `IL` = Load current

---

## 📊 Results

| Parameter | Value |
|-----------|-------|
| Input Voltage | Unregulated DC |
| Regulated Output Voltage | **1.7V DC** |
| Regulation Method | Zener Diode Reverse Breakdown |
| Verified Using | Digital Multimeter |

✅ The circuit successfully achieved a **stable 1.7V DC output**, confirming proper Zener regulation behavior.

---


## 📚 What We Learned
- Practical application of Zener diode voltage regulation
- Circuit simulation and analysis using LTSpice
- Difference between regulated and unregulated DC power supplies
- Hands-on breadboard prototyping and hardware debugging
- Team collaboration on an electronics engineering project

---

## 📄 License
This project is for academic purposes.
