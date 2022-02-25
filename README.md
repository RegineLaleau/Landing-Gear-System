# Landing-Gear-System
This repository presents graphical modeling of the high-level architecture of an extract of the landing gear system case study and its automatic translation into formal specification for formal verification.

**High-Level Architecture:** is designed using a set of SysML diagrams which are: Package, Block Definition, State-Machine and Sequence diagrams.

**Formal specification:** for this purpose we have used B system which is an Event-B syntactic variant proposed by ClearSy. While Event-B is supported by RODIN, B system is supported by Atelier B.
Event-B and B System have the same semantics defined by proof obligations.

Event-B is based on two principale mechanisms which are: model refinement and model decomposition. These two mechanisms are supported by RODIN which gives a deducated plugin to apply automatic model decomposition on a specified machine, contrary to AtelierB which supports only model refinement.
