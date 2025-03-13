# Qiskit-to-QuEra: Optimized Circuit Mapping for Neutral-Atom Quantum Computing

## Overview
This project **translates Qiskit quantum circuits into QuEra Bloqade pulse sequences**, enabling execution on **neutral-atom quantum computers**.  
Additionally, it **automatically optimizes qubit-to-atom mapping**, reducing manual layout adjustments and improving execution efficiency.

## Features
✅ **Converts Qiskit circuits (Hadamard, CNOT, RZ) into Bloqade instructions**  
✅ **Optimizes qubit placement using force-directed graph layouts**  
✅ **Generates Bloqade-compatible code for direct simulation**  
✅ **Visualizes atom placement before execution**  

## How to Use
1. Install dependencies:  
   ```
   !pip install qiskit bloqade matplotlib networkx
   ```
2. Define a Qiskit circuit.
3. Run the provided Python script to **optimize qubit placement** and **generate Bloqade code**.
4. Execute the **translated Bloqade script** on QuEra’s simulator.

## Next Steps
 **Support additional gates (SWAP, Toffoli, etc.)**  
 **Enhance placement optimization using ML techniques**  
 **Integrate a web-based interactive circuit mapper**  

## Contact:
Email: saka4331@colorado.edu
Linkedin: https://www.linkedin.com/in/mohitraosatya/
