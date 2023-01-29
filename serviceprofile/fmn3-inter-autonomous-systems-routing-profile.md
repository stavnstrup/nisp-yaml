---
element: Serviceprofile
nispid: fmn3-inter-autonomous-systems-routing-profile
url: /serviceprofile/fmn3-inter-autonomous-systems-routing-profile.html
sptype: coi
title: FMN Spiral 3.0 Inter-Autonomous Systems Routing Profile
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
    - refid: ietf-rfc1997
    - refid: ietf-rfc4360
    - refid: ietf-rfc5492
    - refid: ietf-rfc4271
    - refid: ietf-rfc4760
    - refid: ietf-rfc7606
    - refid: ietf-rfc6793
    - refid: ietf-rfc6286
    - refid: ietf-rfc7153
    description: The following standards apply for all IP interconnections.
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: ietf-rfc4632
    description: The following standard applies for unicast routing.
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: ietf-rfc5082
    description: The following standard is added to improve MD5-based BGP-authentication
  - obligation: conditional
    lifecycle: current
    standards: 
    - refid: ietf-rfc7454
    description: The following standard can be added to improve MD5-based BGP-authentication, depending on bilateral agreement.
  - obligation: recommended
    lifecycle: current
    standards: 
    - refid: ietf-rfc5668
    description: Additionally, the following standard applies for 32-bit autonomous system numbers (ASN).
status:
  uri: 
  history: 
    - flag: added
      date: 2018-10-31
      rfcp: 11-57
      version: 12.0
uuid: 500015c1-5d82-42f9-94c0-c9dfdd43b610
parents:
  - refid: fmn3-pr-communication
    type: profile
    title: FMN Spiral 3 Communications Profile
---
