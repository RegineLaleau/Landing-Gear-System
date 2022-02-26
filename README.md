# Landing-Gear-System
This repository presents graphical modeling of the high-level architecture of an extract of the landing gear system case study and its automatic translation into formal specification for formal verification.

**High-Level Architecture:** is designed using a set of SysML diagrams which are: Package, Block Definition, State-Machine and Sequence diagrams.

**Formal specification:** for this purpose we have used B system which is an Event-B syntactic variant proposed by ClearSy. While Event-B is supported by RODIN, B system is supported by Atelier B.
Event-B and B System have the same semantics defined by proof obligations.

Event-B is based on two principale mechanisms which are: model refinement and model decomposition. These two mechanisms are supported by RODIN which gives a deducated plugin to apply automatic model decomposition on a specified machine, contrary to AtelierB which supports only model refinement.

As we are using B system on AtelierB and the aim of our work is to generate automatically formal specification from high-level architecture modeling, we proposed an automatic transition from SysML concept to B system concepts.

While Event-B based mechanisms are recommended to be used in modeling complex systems high-level architecture, we have proposed a SysML extension based on UML profiling to support refinement and decomposition mechanisms on modeling diagrams.

As mentionned above, AtelierB supported B system does not give automatic model decomposition mechanism, that's why we proposed an automatic translation of the proposed SysML refinement and decomposition extensions in order to simulate these mechanisms on B system.

In order to verify that the model decomposition in the B system specification generated with the automatic transition are correct and consistent, we have modeled the same exemple on RODIN and we have applied its automatic decompostion features on the same machine to be decomposed in the generated B system specification.
Therefore, we have noticed that the decomposition applied on RODIN is similar to the decomposition created with our transition and gives the same result.