---
element: Standard
complete: true
nispid: ietf-rfc1584
url: /standard/ietf-rfc1584.html
nisptag: "IETF RFC 1584"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 1584"
  title: "Multicast Extensions to OSPF"
  date: "1994-03"
  version: ""
applicability: >2
  This memo documents enhancements to the OSPF protocol enabling the routing of IP multicast datagrams. In this proposal, an IP multicast packet is routed based both on the packet's source and its multicast destination (commonly referred to as source/destination routing). As it is routed, the multicast packet follows a shortest path to each multicast destination. During packet forwarding, any commonality of paths is exploited; when multiple hosts belong to a single multicast group, a multicast packet will be replicated only when the paths to the separate hosts diverge. The multicast extensions are built on top of OSPF Version 2. The extensions have been implemented so that a multicast routing capability can be introduced piecemeal into an OSPF Version 2 routing domain. Some of the OSPF Version 2 routers may run the multicast extensions, while others may continue to be restricted to the forwarding of regular IP traffic (unicasts).
rp: ncia-nsii
status:
  uri: https://www.ietf.org/rfc/rfc1584.txt
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
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: b7455b78-c2ce-4284-b357-28793dedc938
coverdocument:
consumers:
---
