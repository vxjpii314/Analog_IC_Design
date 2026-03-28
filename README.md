# Analog IC Design: IC design Lab & Project Portfolio

[![EDA Tool: Synopsys](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ9mFDDdvjcSViTlgv-i3oj6eyja5o1OoeLiA&s)]()

## 📌 Overview
This repository contains the complete documentation and implementation of analog circuit design and layout.

---

## 📂 Repository Structure

| Folder/File | Description |
| :--- | :--- |
| **`/FrontEnd`** | **Schematic-Level Design:** Ihe design of a circuit in schematic level. This includes circuit specification, characterization, simulation(PVT and Monte Carlo) and verification. Front design requires a strong theoretical thinking in electronic physics and semiconductor to ensure a good performance and efficiency of the circuit designed |
| **`/BackEnd`** | **Physical Implementation:**  The design flow of turning schematic design into manufacturable layout design. This includes floorplanning, circuit routing, physical verification (DRC, LVS, PEX), post-layout simulation and GDSII file format. |
| **`/Slides`** | Presentation slides to describe and summarize the circuits designed. |
| **`/MyNote`** | My analog IC design notes and look-up table for circuit characterization |

---

## 💻 Implementation & Toolflow
The design flow is executed using the **Synopsys Custom Design Platform**. The methodology follows a "Theory-First" approach:

1.  **Analytical Modeling:** Initial hand-calculations and topology research to meet target specifications.
2.  **Pre-Layout Simulation:** Schematic entry and characterization across PVT (Process, Voltage, Temperature) corners.
3.  **Physical Design:** Full-custom layout with a focus on signal integrity and parasitic reduction.
4.  **Verification:** Sign-off via Design Rule Checks (DRC) and Layout vs. Schematic (LVS) verification.
5.  **Extraction:** Parasitic Extraction (PEX) and back-annotation for final performance validation.

---

## 🛠 Tech Stack
* **EDA Tools:** Synopsys (Custom Compiler, HSPICE, FineSim, IC Validator)
* **Process Node:** [e.g., 180nm / 65nm / 28nm] Generic PDK
* **Key Circuits:** [e.g., Operational Amplifiers, Bandgap References, LDO Regulators]

---
