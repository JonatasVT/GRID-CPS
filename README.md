# GRID-CPS - NM-ROUTER
A I4.0 Doctoral Thesis Repository

This branch contains the CoppeliaSim control scripts associated with the Machining Workstation (NM) of the GRID-CPS architecture. It implements the distributed cyber-layer logic required to coordinate pallet handling, part manipulation, and machining operations such as drilling and milling.

The NM-ROUTER branch focuses on the interaction between transportation boards, intermediate buffers, and machining equipment. The control logic is structured as a set of autonomous scripts that communicate through signal-based mechanisms, enabling synchronized execution of pick-and-place tasks and machining workflows. Each script represents a computational node responsible for a specific function within the workstation.

This branch can operate independently or as part of the integrated distributed system through ZMQ-based routing, allowing coordination with other workstations. It serves as a reference implementation of the machining node within the 5C-compliant GRID-CPS framework and supports experimentation with distributed control strategies in manufacturing environments.
