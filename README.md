# GRID-CPS
A I4.0 Doctoral Thesis Repository

This repository contains the CoppeliaSim simulation files and control scripts developed as part of the GRID-CPS research project. The project proposes and evaluates a distributed Cyber-Physical System (CPS) architecture compliant with the 5C model (Connection, Conversion, Cyber, Cognition, and Configuration) in the context of Industry 4.0 robotic manufacturing systems.

The simulation environment implements a multi-workstation manufacturing plant composed of autonomous cyber nodes that coordinate through signal-based communication. Each script represents an independent computational unit responsible for sensing, decision-making, control, or inter-node coordination, reflecting the distributed and System-of-Systems (SoS) principles adopted in the proposed architecture.

Repository Structure

The repository is organized into multiple branches, each corresponding to a specific simulation file and workstation:

NW-DEALER – Warehouse and central distribution logic

NM-ROUTER – Machining workstation

NA-ROUTER – Assembling workstation

NQ-ROUTER – Quality inspection workstation

CoppeliaSim-FIles – The simulation files to run in CoppeliaSim 4.9 rev 6 in Windows

Each branch contains the complete set of CoppeliaSim scene files and scripts required to execute the corresponding workstation simulation independently or as part of the distributed system.
