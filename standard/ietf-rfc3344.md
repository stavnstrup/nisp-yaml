---
element: Standard
complete: true
nispid: ietf-rfc3344
url: /standard/ietf-rfc3344.html
nisptag: "IETF RFC 3344"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 3344"
  title: "IP Mobility Support for IPv4"
  date: "2002-08"
  version: ""
applicability: >2
  This document specifies protocol enhancements that allow transparent routing of IP datagrams to mobile nodes in the Internet. Each mobile node is always identified by its home address, regardless of its current point of attachment to the Internet. While situated away from its home, a mobile node is also associated with a care-of address, which provides information about its current point of attachment to the Internet. The protocol provides for registering the care-of address with a home agent. The home agent sends datagrams destined for the mobile node through a tunnel to the care- of address. After arriving at the end of the tunnel, each datagram is then delivered to the mobile node.
rp: ncia-nsii
status:
  uri: https://www.ietf.org/rfc/rfc3344.txt
  history: 
    - flag: added
      date: 2002-01-01
      rfcp: 
      version: 0.4
    - flag: changed
      date: 2003-07-31
      rfcp: 
      version: 0.5
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
uuid: ae6d78f1-f01c-4bc5-a62f-51b8ba31d747
coverdocument:
consumers:
  - bsp-Transport_Services
---
