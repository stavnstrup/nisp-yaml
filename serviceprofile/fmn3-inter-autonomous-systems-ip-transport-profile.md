---
element: Serviceprofile
nispid: fmn3-inter-autonomous-systems-ip-transport-profile
url: /serviceprofile/fmn3-inter-autonomous-systems-ip-transport-profile.html
sptype: coi
title: FMN Spiral 3.0 Inter-Autonomous Systems IP Transport Service Profile
profilespec:
  org: fmn
  pubnum: 
  title: FMN Spiral 3 Standards Profile
  date: 2018-10-26
  version: 3
description: The Inter-Autonomous Systems IP Transport Profile provides standards and guidance for Edge Transport Services between autonomous systems, using Internet Protocol (IP) over point-to-point Ethernet links on optical fibre.
taxonomy:
  - T-a6fef4f6-40e5-4a5c-a3b0-9ee60e4507dd-X
refgroup:
  - obligation: conditional
    lifecycle: current
    standards: 
    - refid: mil-dtl83526revd
    - refid: nato-acomp-4290-ed.a-v2
    description: If the interconnection point is outside a shelter in a harsh environment, the interconnection shall follow STANAG 4290 or MIL-DTL-83526 connector specifications.
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: itu-t-g.652
    - refid: iec-61754-20-100
    description: The use of LC-connectors is required for network interconnections inside shelters (or inside other conditioned infrastructure).
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: ietf-rfc826
    description: Standards for IP version 4 (IPv4) over Ethernet
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: iso-iec-11801-1
    description: 
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: ieee-802.3-2018
    description: Section 3 - Clause 38 - 1000BASE-LX, nominal transmit wavelength 1310nm.
status:
  uri: 
  history: 
    - flag: added
      date: 2018-10-30
      rfcp: 11-57
      version: 12.0
uuid: 79304102-dd95-45c4-9532-e238ffff7851
parents:
  - refid: fmn3-pr-communication
    type: profile
    title: FMN Spiral 3 Communications Profile
---
