# GRID-CPS - NQ-Router - Under Development
A I4.0 Doctoral Thesis Repository

This branch contains the CoppeliaSim control scripts associated with the Quality Inspection Workstation (NQ) of the GRID-CPS architecture. It extends the material-handling logic of previous workstations by incorporating inspection and discard operations for defective parts.

The NQ-ROUTER branch implements autonomous control logic for transferring parts between pallets and quality inspection boards, evaluating inspection outcomes, and executing discard procedures when required. Communication among scripts is achieved through signal-based coordination, ensuring consistent synchronization with upstream assembling operations and downstream material flow.

Like the other workstation branches, the NQ-ROUTER branch supports both standalone execution and integration within the distributed CPS through ZMQ-based routing mechanisms. It provides a concrete implementation of quality-related decision logic within a 5C-compliant CPS and contributes to the evaluation of distributed, multi-stage manufacturing processes.

NQ-ROUTER - Signal Diagram

<img width="434" height="460" alt="image" src="https://github.com/user-attachments/assets/ef4f6568-9fa2-4285-8144-48998f51e8e3" />
