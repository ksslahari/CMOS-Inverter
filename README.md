# CMOS-Inverter
## Project Overview

This project aims to experiment with the working of an inverter and to understand the various parameters involved, using the SkyWater 130nm PDK and open-source tools like Xschem, NGSPICE, MAGIC, and Netgen.

### Project Workflow

1. **NMOS and PMOS Analysis**: Start by analyzing the 1.8V standard NMOS and PMOS models from the PDK to determine a common W/L ratio, and extract parameters like gm, ron, etc.
2. **CMOS Inverter Design**: Create a schematic for a CMOS inverter and measure key parameters such as delays, noise margins, rise time, and fall time. Use SPICE programming capabilities for enhanced measurement accuracy.
3. **Layout Design**: Design the layout in MAGIC Layout Editor, exploring different layers and understanding their significance in mask design.
4. **LVS (Layout vs. Schematic) Verification**: Compare the schematic and layout netlists to ensure they match.

### Purpose

This project serves as a hands-on practice in analog design using an open-source toolchain. It aims to provide clear and accessible documentation for anyone looking to replicate or learn from the process.
