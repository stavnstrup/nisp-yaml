---
element: Standard
complete: true
nispid: ietf-rfc7919
url: /standard/ietf-rfc7919.html
nisptag: "IETF RFC 7919"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 7919"
  title: "Negotiated Finite Field Diffie-Hellman Ephemeral Parameters for Transport Layer Security (TLS)"
  date: "2016-08"
  version: ""
applicability: >2
  Traditional finite-field-based Diffie-Hellman (DH) key exchange during the Transport Layer Security (TLS) handshake suffers from a number of security, interoperability, and efficiency shortcomings. These shortcomings arise from lack of clarity about which DH group parameters TLS servers should offer and clients should accept. This document offers a solution to these shortcomings for compatible peers by using a section of the TLS Supported Groups Registry (renamed from EC Named Curve Registry by this document) to establish common finite field DH parameters with known structure and a mechanism for peers to negotiate support for these groups.
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc7919.txt
  history: 
    - flag: added
      date: 2017-04-30
      rfcp: 9-6
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: b54c2a00-485a-4629-a837-7d22458cf513
coverdocument:
consumers:
  - fmn3-srtp-based-media-infrastructure-security-profile
  - fmn4-20211022-prf-79
  - sip-for-tls-profile
  - fmn5-20221202-prf-79
  - fmn5-20221202-prf-164
---
