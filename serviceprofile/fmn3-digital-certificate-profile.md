---
element: Serviceprofile
nispid: fmn3-digital-certificate-profile
url: /serviceprofile/fmn3-digital-certificate-profile.html
sptype: coi
title: FMN Spiral 3.0 Digital Certificate Service Profile
profilespec:
  org: fmn
  pubnum: 
  title: FMN Spiral 3 Standards Profile
  date: 2018-10-26
  version: 3
description: The Digital Certificate Profile provides standards and guidance in support of a Public Key Infrastructure (PKI) on federated mission networks.
taxonomy:
  - T-13a17bdd-8eb2-418c-8cb8-7f32a435f432-X
refgroup:
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: itu-t-x.509
    description: 
  - obligation: optional
    lifecycle: current
    standards: 
    - refid: ietf-rfc6960
    description: The Online Certificate Status Protocol (OCSP) capability is optional for PKI Service providers and consumers.
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: ietf-rfc5280
    - refid: ietf-rfc4523
    description: CRLs may be provided at multiple endpoints. The addresses of these endpoints shall be provided in digital certificates through X.509 certificate extensions such as Authority Information Access (AIA) and CRL distribution point (CDP). Each CA shall provide CRLs using at least one of the endpoint types (HTTP or LDAP). Clients must support both types.
status:
  uri: 
  history: 
    - flag: added
      date: 2018-11-01
      rfcp: 11-57
      version: 12.0
uuid: bdb98c91-690a-439a-b3dc-007c2ca7866c
parents:
  - refid: fmn3-pr-networking
    type: profile
    title: FMN Spiral 3 Networking Profile
---
