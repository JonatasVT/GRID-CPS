# GRID-CPS - NW - DEALER Scripts
A I4.0 Doctoral Thesis Repository

This branch contains the CoppeliaSim control scripts associated with the Warehouse and Central Distribution Workstation (NW) of the GRID-CPS architecture. It implements the distributed cyber-layer logic responsible for managing pallet storage, material dispatch, and coordination with the conveyor system and downstream workstations.

The NW-DEALER branch focuses on decision-making related to pallet availability, board handling, and robotic pick-and-place operations within the warehouse environment. The control logic is decomposed into multiple autonomous scripts that communicate through signal-based mechanisms, enabling synchronized execution of push and pull operations, pallet tracking, and interaction with transportation boards.

This branch also acts as the central coordination point for production requests, interfacing with other workstation simulations through ZMQ-based routing mechanisms. It can operate as a standalone simulation or as part of the integrated distributed CPS and serves as a reference implementation of the warehouse node within the 5C-compliant GRID-CPS framework, supporting experimentation with decentralized control and material-flow coordination.
