# Standard Cell Design Repository

## Overview
This repository contains the **Standard Cell Design** for fundamental digital logic gates using **CMOS technology**. The cells are designed and implemented for efficient integration into **ASIC design flows**.

## Included Standard Cells
The repository includes the transistor-level design, layout, and simulation results for the following standard cells:

### **2-Input Gates**
- AND
- AOI (AND-OR-INVERT)
- BUFFER
- D Flip-Flop (DFF)
- INVERTER
- MUX (Multiplexer)
- NAND
- NOR
- OAI (OR-AND-INVERT)
- OR
- XNOR
- XOR

### **3-Input Gates**
- AND
- NAND
- OR
- NOR

## Features
- **Schematic Design**: Transistor-level circuit design.
- **Layout Implementation**: CMOS layout for fabrication.
- **SPICE Simulations**: Functional verification and power, delay analysis.
- **Design Rule Checks (DRC) & Layout vs Schematic (LVS)**: Ensuring manufacturability and correctness.
- **Standard Cell Characterization**: Timing and power characterization.

## Tools Used
- **Cadence Virtuoso** (Designing)
- **Calibre** (DRC, LVS, and PEX Verification)

## Repository Structure
```
StandardCell/
│-- Schematic/      # Schematic designs
│-- Layout/         # Layout files
│-- Simulation/     # SPICE simulations
│-- Characterization/ # Timing & Power characterization results
│-- Reports/        # Design analysis reports
│-- README.md       # Project documentation
```

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/allenblade-commits/StandardCell.git
   cd StandardCell
   ```
2. Open the schematic and layout files in **Cadence Virtuoso**.
3. Run **SPICE simulations** using Spectre.
4. Perform **DRC & LVS checks** using Calibre.
5. Analyze the characterization reports for timing and power data.

## Contribution
Feel free to contribute by improving designs, adding new standard cells, or optimizing layouts. Submit a pull request with a detailed description of your changes.

## License
This project is open-source under the **MIT License**.

## Contact
For any queries, reach out to **Allen Stanley** ([@allenblade-commits](https://github.com/allenblade-commits)).
