---
element: Serviceprofile
nispid: fmn3-inter-autonomous-systems-multicast-routing-profile
url: /serviceprofile/fmn3-inter-autonomous-systems-multicast-routing-profile.html
sptype: coi
title: FMN Spiral 3.0 Inter-Autonomous Systems Multicast Routing Profile
profilespec:
  org: fmn
  pubnum: 
  title: FMN Spiral 3 Standards Profile
  date: 2018-10-26
  version: 3
description: The Inter-Autonomous Systems Routing Profile provides standards and guidance for routing between inter-autonomous systems.
taxonomy:
  - T-5c6b2b30-6819-4224-9afa-e299e6e49e33-X
  - T-8b0fcb44-08fd-4757-a12a-0fe3ea9aad7b-X
refgroup:
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: ietf-rfc6308
    - refid: ietf-rfc5771
    - refid: ietf-rfc2365
    description: The following standards shall apply to multicast routing.
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: ietf-rfc3618
    - refid: ietf-rfc4760
    description: Service providers with their own multicast capability shall provide a Rendezvous Point (RP) supporting the following IP multicast protocol standards.
  - obligation: optional
    lifecycle: current
    standards: 
    - refid: ietf-rfc4607
    - refid: ietf-rfc4608
    description: 
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: ietf-rfc7761
    - refid: ietf-rfc1112
    - refid: ietf-rfc3376
    description: The following standards shall apply for all IP interconnections.
status:
  uri: 
  history: 
    - flag: added
      date: 2018-10-31
      rfcp: 11-57
      version: 12.0
uuid: d167eda4-d10f-4a04-8ac2-9fd1f60c46ba
parents:
  - refid: fmn3-pr-communication
    type: profile
    title: FMN Spiral 3 Communications Profile
---
