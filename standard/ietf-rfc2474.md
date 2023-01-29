---
element: Standard
complete: true
nispid: ietf-rfc2474
url: /standard/ietf-rfc2474.html
nisptag: "IETF RFC 2474"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 2474"
  title: "Definition of the Differentiated Services Field (DS Field) in the IPv4 and IPv6 Headers"
  date: "1998-12"
  version: ""
applicability: >2
  Differentiated services enhancements to the Internet protocol are intended to enable scalable service discrimination in the Internet without the need for per-flow state and signaling at every hop. A variety of services may be built from a small, well-defined set of building blocks which are deployed in network nodes. The services may be either end-to-end or intra-domain; they include both those that can satisfy quantitative performance requirements (e.g., peak bandwidth) and those based on relative performance (e.g., class differentiation). Services can be constructed by a combination of 

  *  setting bits in an IP header field at network boundaries (autonomous system boundaries, internal administrative boundaries, or hosts),

  *  using those bits to determine how packets are forwarded by the nodes inside the network, and

  *  conditioning the marked packets at network boundaries in accordance with the requirements or rules of each service.

  
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc2474.txt
  history: 
    - flag: added
      date: 1998-11-10
      rfcp: 
      version: 0.1
    - flag: changed
      date: 2003-03-18
      rfcp: 
      version: 0.5
    - flag: changed
      date: 2005-09-16
      rfcp: 
      version: 0.7
    - flag: changed
      date: 2017-01-14
      rfcp: 9-17
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 4bf496f5-cdf7-4211-9939-17f311f995ab
coverdocument:
consumers:
  - bsp-Transport_Services
  - fmn3-ip-quality-of-service-profile
  - fmn4-20211022-prf-50
  - fmn4-20211022-prf-88
  - fmn5-20221202-prf-50
  - fmn5-20221202-prf-88
  - fmn5-20221202-prf-154
---
