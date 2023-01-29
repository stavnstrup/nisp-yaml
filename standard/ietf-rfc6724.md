---
element: Standard
complete: true
nispid: ietf-rfc6724
url: /standard/ietf-rfc6724.html
nisptag: "IETF RFC 6724"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 6724"
  title: "Default Address Selection for Internet Protocol version 6 (IPv6)"
  date: "2012-09"
  version: ""
applicability: >2
  This document describes two algorithms, one for source address selection and one for destination address selection. The algorithms specify default behavior for all Internet Protocol version 6 (IPv6) implementations. They do not override choices made by applications or upper-layer protocols, nor do they preclude the development of more advanced mechanisms for address selection. The two algorithms share a common context, including an optional mechanism for allowing administrators to provide policy that can override the default behavior. In dual-stack implementations, the destination address selection algorithm can consider both IPv4 and IPv6 addresses -- depending on the available source addresses, the algorithm might prefer IPv6 addresses over IPv4 addresses, or vice versa.  Default address selection as defined in this specification applies to all IPv6 nodes, including both hosts and routers.

  
rp: ncia
status:
  uri: https://www.ietf.org/rfc/rfc6724.txt
  history: 
    - flag: added
      date: 2005-11-20
      rfcp: 6-19
      version: 0.7
    - flag: changed
      date: 2013-10-21
      rfcp: 7-27
      version: 8.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-14
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: daab4b8c-d98c-4504-adc6-e7812f4439ee
coverdocument:
consumers:
  - fmn5-20221202-prf-125
---
