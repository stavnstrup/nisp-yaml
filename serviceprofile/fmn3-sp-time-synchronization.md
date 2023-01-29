---
element: Serviceprofile
nispid: fmn3-sp-time-synchronization
url: /serviceprofile/fmn3-sp-time-synchronization.html
sptype: coi
title: FMN Spiral 3.0 Time Synchronization Service Profile
profilespec:
  org: fmn
  pubnum: 
  title: FMN Spiral 3 Standards Profile
  date: 2018-10-26
  version: 3
description: The Time Synchronization Profile provides standards and guidance to support the synchronization of clients and servers across a network or a federation of networks and the safeguard of the accurate use of timestamps.
taxonomy:
  - T-f15d7721-33a3-48e1-b2c6-b0d896f642dc-X
refgroup:
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: ietf-rfc5905
    - refid: itu-r-tf.460-6
    description: Service providers must synchronize their network segment with a stratum 1 time server directly connected to a stratum 0 device, or over a reliable network path to a stratum 1 time server of another service provider. All other entities in the federation must use the time service of their host service provider.
status:
  uri: 
  history: 
    - flag: added
      date: 2018-11-01
      rfcp: 11-57
      version: 12.0
uuid: 9272fa4f-820c-4bef-ab6d-63d975807e1e
parents:
  - refid: fmn3-pr-networking
    type: profile
    title: FMN Spiral 3 Networking Profile
---
