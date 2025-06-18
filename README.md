# PLECS-SIMULATION
Simulation OF DAB
Bidirectional Dual Active Bridge (DAB) DC-DC Converter

This repository contains the simulation and preliminary implementation efforts for a bidirectional Dual Active Bridge (DAB) DC-DC converter. The project focuses on power transfer between 48 V and 400 V, suitable for applications in renewable energy systems and energy storage.

Project Overview

The core objectives of this project include:

Design and Simulation: Develop a robust model of the DAB converter in PLECS, incorporating a Single Phase Shift (SPS) control strategy.

Controller Design: Design and tune a PI controller to regulate the phase shift for stable operation and dynamic performance.

Hardware Implementation (Preliminary): Utilize key components such as SiC MOSFETs, an EE70/70 transformer, current/voltage sensors, and a TI C2000 microcontroller for hardware realization.

Simulation Details

The system was rigorously simulated using PLECS. These simulations confirmed the stability and dynamic performance of the system under various load and power direction conditions (boost and buck modes). Detailed schematics, component parameters, and solver settings used in the simulation are available in the project documentation.

Hardware Implementation Status

Preliminary hardware implementation has been conducted, utilizing [mention key components again briefly, e.g., SiC MOSFETs and a TI C2000 DSP]. While simulation results have been highly promising, the full experimental validation of the converter's capabilities has faced challenges due to hardware-related issues, primarily stemming from component costs and difficulties in obtaining comprehensive technical information. Efforts are ongoing to address these practical limitations and achieve full hardware performance.

Getting Started (for collaborators/reviewers)

PLECS: Ensure you have PLECS software installed to open and run the .plecs model files.

TI C2000 Toolchain: If interacting with the generated C code, Code Composer Studio (CCS) and the relevant C2000Ware package will be required.

Note: This project is part of a Master's thesis. Further updates and detailed documentation will be added as the hardware implementation progresses.
