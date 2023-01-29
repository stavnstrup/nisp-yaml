---
element: Serviceprofile
nispid: fmn3-isr-library-interface-profile
url: /serviceprofile/fmn3-isr-library-interface-profile.html
sptype: coi
title: FMN Spiral 3.0 ISR Library Interface Profile
profilespec:
  org: fmn
  pubnum: 
  title: FMN Spiral 3 Standards Profile
  date: 2018-10-26
  version: 3
description: The ISR Library Interface is the standard interface for querying and accessing heterogeneous product libraries maintained by various nations.
taxonomy:
  - T-da4a7c62-0dd4-4b5b-a4cc-8b2a84a737ae-X
refgroup:
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: iso-639-2
    - refid: iso-iec-11179-3
    - refid: iso-iec-12087-5
    - refid: iso-iec-14750
    description: The following international standards are mandated for interoperability of ISR libraries.
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: nato-aedp-04-ed.2-v1
    - refid: nato-aedp-07-ed.2-v1
    - refid: nato-aedp-17-ed.A-v1
    - refid: nato-aedp-18-ed.A-v1
    - refid: nato-aedp-19-ed.A-v1
    - refid: nato-nnstd-misp-2015.1
    description: The following NATO standards are mandated for interoperability of ISR libraries. (For STANAG 4559 Ed 4  Only Standard AEDP-17 Ed. A Ver. 1 NATO Standard ISR Library Interface.)
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: nato-stanag5525ed1
    description: Note  implementation of STANAG 5525 in the context of the ISR Library Interface Profile is limited to the definition of unique keys that could be used to unambiguously refer to an external information object that is modelled in accordance with STANAG 5525.
status:
  uri: 
  history: 
    - flag: added
      date: 2018-11-01
      rfcp: 11-57
      version: 12.0
uuid: b0b85dcb-fe39-4741-b93f-e4381df106a5
parents:
  - refid: fmn3-pr-intell
    type: profile
    title: FMN Spiral 3 Intelligence Profile
---
