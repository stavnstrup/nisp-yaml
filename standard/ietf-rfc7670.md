---
element: Standard
complete: true
nispid: ietf-rfc7670
url: /standard/ietf-rfc7670.html
nisptag: "IETF RFC 7670"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 7670"
  title: "Generic Raw Public-Key Support for IKEv2"
  date: "2016-01"
  version: ""
applicability: >2
  The Internet Key Exchange Version 2 (IKEv2) protocol did have support for raw public keys, but it only supported RSA raw public keys. In constrained environments, it is useful to make use of other types of public keys, such as those based on Elliptic Curve Cryptography. This document updates RFC 7296, adding support for other types of raw public keys to IKEv2.
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc7670.txt
  history: 
    - flag: added
      date: 2017-04-30
      rfcp: 9-6
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 3038dd0a-2862-4d07-aed0-5513841d5500
coverdocument:
consumers:
  - fmn3-ipsec-based-media-infrastructure-security-profile
  - fmn3-routing-encapsulation-profile
  - fmn4-20211022-prf-52
  - fmn4-20211022-prf-73
  - fmn5-20221202-prf-52
---
