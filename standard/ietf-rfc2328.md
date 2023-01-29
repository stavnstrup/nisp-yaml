---
element: Standard
complete: true
nispid: ietf-rfc2328
url: /standard/ietf-rfc2328.html
nisptag: "IETF RFC 2328"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 2328"
  title: "OSPF Version 2 (STD-54)"
  date: "1998-04"
  version: ""
applicability: >2
  This memo documents version 2 of the OSPF protocol. OSPF is a link-state routing protocol. It is designed to be run internal to a single Autonomous System. Each OSPF router maintains an identical database describing the Autonomous System's topology. From this database, a routing table is calculated by constructing a shortest- path tree. OSPF recalculates routes quickly in the face of topological changes, utilizing a minimum of routing protocol traffic. OSPF provides support for equal-cost multipath. An area routing capability is provided, enabling an additional level of routing protection and a reduction in routing protocol traffic. In addition, all OSPF routing protocol exchanges are authenticated.
rp: ncia-nsii
status:
  uri: https://www.ietf.org/rfc/rfc2328.txt
  history: 
    - flag: added
      date: 1998-04-01
      rfcp: 
      version: 0.1
    - flag: changed
      date: 2005-09-16
      rfcp: 
      version: 0.7
    - flag: changed
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: aee6b8bd-ea5d-4caa-9499-dea18a697760
coverdocument:
consumers:
  - bsp-Transport_Services
---
