# Single-Phase Inverter – PCB Design (Part 2)

This repository contains the second part of the project: the PCB design of a single-phase inverter. The schematic and simulation were previously developed in [Part 1](https://github.com/seu-usuario/Single-Phase-Inverter-with-PWM-Control).

## 🔧 Tools Used

- **LTspice** – for circuit simulation
- **KiCad 7** – for schematic capture and PCB layout

## 🛠️ Step-by-Step Overview

1. **Schematic Design**
   - The schematic was recreated in KiCad using the same topology from LTspice.
   - NMOS, resistors, connectors, and power symbols were used.
   - All nets were labeled for clarity.

2. **Footprint Assignment**
   - Footprints were chosen based on standard SMD packages (e.g., SOT-23 for MOSFETs).
   - All components were matched to the PCB layout library.

3. **PCB Layout**
   - Traces were sized for low current (~0.5mA) control logic.
   - Ground planes were created for both front and back layers.
   - Silk screen includes component labels, revision info, and author details.

4. **DRC and ERC Checks**
   - No design rule or electrical rule errors were found.
   - Ratsnest was cleaned and optimized.

5. **Gerber Generation**
   - Gerber and drill files generated and ready for PCB fabrication.
   - Files stored in `/Gerbers/`.
  
