# Landing-Gear-System
This repository presents the SysML modeling of the high-level architecture of an extract of the landing gear system case study and its automatic translation into an Event-B formal specification for formal verification.  

**High-Level Architecture** is designed using a set of SysML diagrams: Package, Block Definition, State-Machine and Sequence diagrams.

**Formal specification.** we have used BSystem, an Event-B syntactic variant, supported by AtelierB, while Event-B is supported by the RODIN platform. 

The pdf file "landing_systemCase_Study.pdf" contains all the SysML diagrams and the BSystem specification.

Event-B is based on two main mechanisms to master complexity of systems: refinement and decomposition. Refinement is available in the two tools but only RODIN supports decomposition thanks to a plug-in. In order to verify that our translation rules give the right result for the decomposition mechanism, we have applied the decomposition mechanism of RODIN on the BSystem machines of the case study to be decomposed. (Fortunately,) we obtained the same result!  
