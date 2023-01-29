---
element: Standard
complete: true
nispid: ietf-rfc3775
url: /standard/ietf-rfc3775.html
nisptag: "IETF RFC 3775"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 3775"
  title: "Mobility Support in IPv6"
  date: "2004-06"
  version: ""
applicability: >2
  This document specifies a protocol which allows nodes to remain reachable while moving around in the IPv6 Internet. Each mobile node is always identified by its home address, regardless of its current point of attachment to the Internet. While situated away from its home, a mobile node is also associated with a care-of address, which provides information about the mobile node's current location. IPv6 packets addressed to a mobile node's home address are transparently routed to its care-of address. The protocol enables IPv6 nodes to cache the binding of a mobile node's home address with its care-of address, and to then send any packets destined for the mobile node directly to it at this care-of address. To support this operation, Mobile IPv6 defines a new IPv6 protocol and a new destination option. All IPv6 nodes, whether mobile or stationary, can communicate with mobile nodes.
rp: ncia-nsii
status:
  uri: https://www.ietf.org/rfc/rfc3775.txt
  history: 
    - flag: added
      date: 2004-07-24
      rfcp: 5-35
      version: 0.6
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
uuid: 10bab8d2-06d6-4539-b3fe-ab794181854b
coverdocument:
consumers:
  - bsp-Transport_Services
---
