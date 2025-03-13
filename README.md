# Quantum Circuit to QuEra Bloqade Translator

## Overview
This project translates **Qiskit quantum circuits** into **QuEra Bloqade pulse sequences**, enabling execution on **neutral-atom quantum computers**.

## Features
- Converts **Hadamard, CNOT, and RZ gates** into Bloqade-compatible instructions.
- Generates **Bloqade code** for quantum simulations.
- Bridges the gap between **gate-based and analog quantum computing**.

## How to Use
1. Install dependencies: qiskit & bloqade
2. Define a Qiskit circuit.
3. Run the provided Python script to generate Bloqade code.
4. Execute the translated code on QuEra’s Bloqade emulator.

## Future Improvements
- Expanding support for **more quantum gates**.
- Running Bloqade simulations on **QuEra's cloud**.
- Building a **web-based interactive tool** for translation.
