---
element: Serviceprofile
nispid: fmn3-tactical-message-distribution-profile
url: /serviceprofile/fmn3-tactical-message-distribution-profile.html
sptype: coi
title: FMN Spiral 3.0 Tactical Message Distribution Profile
profilespec:
  org: fmn
  pubnum: 
  title: FMN Spiral 3 Standards Profile
  date: 2018-10-26
  version: 3
description: The Air Information Exchange Profile provides standards and guidance to support the exchange of Recognized Air Picture (RAP) information within a coalition network or a federation of networks.
taxonomy:
  - T-b0523d88-fcef-4265-a6aa-69ce20c9ec8f-X
  - T-6980cc23-83cd-4174-81c3-ffb7ac3997b9-X
  - T-75a41fc4-9672-479c-a7fe-2b0cc8b01d4b-X
refgroup:
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: nato-atdlp-5.18-ed.b-v2
    description: The Standard for Joint Range Extension Application Protocol (JREAP) - ATDLP-5.18 Edition B enables TDL data to be transmitted over digital media and networks not originally designed for tactical data exchange. JREAP consists of three different protocols  A, B and C. For implementation in FMN only JREAP, Appendix C 'Encapsulation over Internet Protocol (IP)' which enables TDL data to be transmitted over an IP network must be used. As per the common time reference within JREAP, UTC must be supported as the common time reference. If no common time reference is available, round-trip shall be used.
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: nato-stanag5516ed4
    description: The "Minimum Link-16 Message Profile", as described in the FMN Spiral 3 Service Interface Profile for RAP Data, defines the minimum set of data elements that are required to be available for operational or technical reasons so that correctly formatted technical message can be generated to establish a Recognized Air Picture in a federated environment. The implementation of the following message types of STANAG 5516 is MANDATORY  Precise Participant Location and Identification (PPLI) Messages J2.0 Indirect Interface Unit PPLIJ2.2 Air PPLIJ2.3 Surface (Maritime) PPLIJ2.4 Subsurface (Maritime) PPLIJ2.5 Land (Ground) Point PPLIJ2.6 Land (Ground) Track PPLI Surveillance Messages J3.0 Reference PointJ3.1 Emergency PointJ3.2 Air Track messageJ3.3 Surface (Maritime) TrackJ3.4 Subsurface (Maritime) TrackJ3.5 Land (Ground) Point/TrackJ3.7 Electronic Warfare Product Information To maximize the ability to share tactical data in support of Situational Awareness, the following message types must also be supported  J7 Information ManagementJ8 Information ManagementJ9 Weapons Coordination and ManagementJ10 Weapons Coordination and ManagementJ12 ControlJ13 Platform and System StatusJ15 Threat WarningJ17 Miscellaneous
status:
  uri: 
  history: 
    - flag: added
      date: 2018-11-16
      rfcp: 11-57
      version: 12.0
uuid: 2fbc5e51-17bf-40e7-ba97-5ca79aa4bf22
parents:
  - refid: fmn3-pr-sit-aware
    type: profile
    title: FMN Spiral 3 Situational Awareness Profile
---
