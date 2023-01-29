---
element: Standard
complete: true
nispid: ietf-rfc4271
url: /standard/ietf-rfc4271.html
nisptag: "IETF RFC 4271"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 4271"
  title: "A Border Gateway Protocol 4 (BGP-4)"
  date: "2006-01"
  version: ""
applicability: >2
  This document discusses the Border Gateway Protocol (BGP), which is an inter-Autonomous System routing protocol.  The primary function of a BGP speaking system is to exchange network reachability information with other BGP systems. This network reachability information includes information on the list of Autonomous Systems (ASes) that reachability information traverses. This information is sufficient for constructing a graph of AS connectivity for this reachability from which routing loops may be pruned, and, at the AS level, some policy decisions may be enforced.

    BGP-4 provides a set of mechanisms for supporting Classless Inter- Domain Routing (CIDR). These mechanisms include support for advertising a set of destinations as an IP prefix, and eliminating the concept of network class within BGP. BGP-4 also introduces mechanisms that allow aggregation of routes, including aggregation of AS paths.

  para>
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc4271.txt
  history: 
    - flag: added
      date: 1998-11-10
      rfcp: 
      version: 0.1
    - flag: changed
      date: 2005-09-16
      rfcp: 
      version: 0.7
    - flag: changed
      date: 2013-10-21
      rfcp: 
      version: 8.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-14
      version: 10.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-17
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 181a880b-769c-4175-a84d-a3c6176dd624
coverdocument:
consumers:
  - bsp-Transport_Services
  - fmn3-inter-autonomous-systems-routing-profile
  - fmn4-20211022-prf-61
  - fmn5-20221202-prf-61
---
