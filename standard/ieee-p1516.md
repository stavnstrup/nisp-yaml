---
element: Standard
complete: true
nispid: ieee-p1516
url: /standard/ieee-p1516.html
nisptag: "IEEE P1516-2000"
orgid: ieee
document:
  org: ieee
  pubnum: "P1516"
  title: "Modeling and Simulation (M&S) High Level Architecture (HLA) -- Framework and Rules - Redline"
  date: "2000-12-11"
  version: ""
applicability: >2
  The High Level Architecture (HLA) has been developed with the objective of providing a common architecture applicable across all classes of simulation to support simulation interoperability and reuse. The HLA is defined by the following three standards   Framework and Rules - IEEE Standard P1516  The HLA rules describe the responsibilities of federates (simulations, supporting utilities, or interfaces to live systems) and federations (sets of federates working together to support distributed applications). The rules comprise a set of underlying technical principles for the HLA. For federations, the rules address the requirement for a federation object model (FOM), object ownership and representation, and data exchange. For federates, the rules require a simulation object model (SOM), time management in accordance with the HLA Runtime Infrastructure (RTI) time management services, and certain required functionality and constraints on attribute ownership and updates.

    Federate Interface Specification - IEEE Standard P1516.1  In the HLA, federates interact with an RTI (analogous to a special-purpose distributed operating system) to establish and maintain a federation and to support efficient information exchange among simulations and other federates. The HLA interface specification defines the nature of these interactions, which are arranged into sets of basic RTI services.

    Object Model Template (OMT) Specification - IEEE Standard P1516.2  The HLA requires simulations (and other federates) and federations to each have an object model describing the entities, not necessarily platform entities, represented in the simulations and the data to be exchanged across the federation. The HLA object model template prescribes the method for recording the information in the object models, to include objects, attributes, interactions, and parameters, but it does not define the specific data (e.g., vehicles, unit types) that will appear in the object models.

  
rp: ncia-et
status:
  uri: https://ieeexplore.ieee.org/document/893287
  history: 
    - flag: added
      date: 2003-08-03
      rfcp: 4-34
      version: 0.5
    - flag: changed
      date: 2005-09-08
      rfcp: 
      version: 0.7
    - flag: changed
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 354bac8e-6ba0-4913-88c3-15dd6598d559
coverdocument:
consumers:
  - bsp-Modeling_and_Simulation_Services
---
