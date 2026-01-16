# GRID-CPS - NA - ROUTER
A I4.0 Doctoral Thesis Repository

This branch contains the CoppeliaSim control scripts associated with the Assembling Workstation (NA) of the GRID-CPS architecture. It implements the distributed cyber-layer logic responsible for part handling, assembly operations, and coordination with upstream and downstream workstations.

The NA-ROUTER branch focuses on flexible control of assembly tasks, including pallet handling, part transfer between buffers and assembling boards, and interaction with quality inspection processes. The control logic is decomposed into multiple autonomous scripts that communicate through signal-based mechanisms, reflecting the distributed and System-of-Systems principles adopted in the proposed CPS architecture.

This branch is designed to operate as an independent simulation file or as part of the integrated distributed system, communicating with other workstations via ZMQ-based routing mechanisms. It serves as a reference implementation of the assembling node within the 5C-compliant GRID-CPS framework and supports further experimentation, extension, and comparative analysis.
