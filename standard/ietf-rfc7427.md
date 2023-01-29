---
element: Standard
complete: true
nispid: ietf-rfc7427
url: /standard/ietf-rfc7427.html
nisptag: "IETF RFC 7427"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 7427"
  title: "Signature Authentication in the Internet Key Exchange Version 2 (IKEv2)"
  date: "2015-01"
  version: ""
applicability: >2
  The Internet Key Exchange Version 2 (IKEv2) protocol has limited support for the Elliptic Curve Digital Signature Algorithm (ECDSA). The current version only includes support for three Elliptic Curve groups, and there is a fixed hash algorithm tied to each group. This document generalizes IKEv2 signature support to allow any signature method supported by PKIX and also adds signature hash algorithm negotiation. This is a generic mechanism and is not limited to ECDSA; it can also be used with other signature algorithms.
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc7427.txt
  history: 
    - flag: added
      date: 2016-04-18
      rfcp: 8-5
      version: 9.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-17
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 504e0f97-7f45-4ee4-b7ba-e753b57db39d
coverdocument:
consumers:
  - fmn3-ipsec-based-media-infrastructure-security-profile
  - fmn3-routing-encapsulation-profile
  - fmn4-20211022-prf-52
  - fmn4-20211022-prf-73
  - fmn5-20221202-prf-52
---
