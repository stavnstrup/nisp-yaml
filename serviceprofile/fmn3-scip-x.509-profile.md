---
element: Serviceprofile
nispid: fmn3-scip-x.509-profile
url: /serviceprofile/fmn3-scip-x.509-profile.html
sptype: coi
title: FMN Spiral 3.0 SCIP X.509 Profile
profilespec:
  org: fmn
  pubnum: 
  title: FMN Spiral 3 Standards Profile
  date: 2018-10-26
  version: 3
description: The X.509 standard is used in cryptography to define the format of public key certificates, which are used in many Internet protocols. One example is the use in Transport Layer Security (TLS) / Secure Sockets Layer (SSL), which is the basis for HTTPS, the secure protocol for browsing the web. Public key certificates are also used in offline applications, like electronic signatures. An X.509 certificate contains a public key and an identity (a hostname, or an organization, or an individual), and is either signed by a certificate authority or self-signed. When a certificate is signed by a trusted certificate authority, or validated by other means, someone holding that certificate can rely on the public key it contains to establish secure communications with another party, or validate documents digitally signed by the corresponding private key. Besides the format for certificates themselves, X.509 specifies certificate revocation lists as a means to distribute information about certificates that are no longer valid, and a certification path validation algorithm, which allows for certificates to be signed by intermediate Certificate Authority (CA) certificates, which are in turn signed by other certificates, eventually reaching a trust anchor.
taxonomy:
  - T-a0d92ce5-6739-407c-82db-6ed315aa3651-X
refgroup:
  - obligation: conditional
    lifecycle: current
    standards: 
    - refid: iicwg-scip-233.109
    - refid: iicwg-scip-233.307
    - refid: iicwg-scip-233.401
    - refid: iicwg-scip-233.423
    - refid: iicwg-scip-233.444
    - refid: iicwg-scip-233.601
    description: SCIP Network Standards for operation over other network types
status:
  uri: 
  history: 
    - flag: added
      date: 2018-11-27
      rfcp: 11-57
      version: 12.0
uuid: 6442bd9e-91e7-4621-8608-b1bf007dd92b
parents:
---
