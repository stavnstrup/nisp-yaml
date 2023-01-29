---
element: Standard
complete: true
nispid: ietf-rfc2765
url: /standard/ietf-rfc2765.html
nisptag: "IETF RFC 2765"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 2765"
  title: "Stateless IP/ICMP Translation Algorithm (SIIT)"
  date: "2000-02"
  version: ""
applicability: >2
  This document specifies a transition mechanism algorithm in addition to the mechanisms already specified. The algorithm translates between IPv4 and IPv6 packet headers (including ICMP headers) in separate translator boxes in the network without requiring any per-connection state in those boxes. This new algorithm can be used as part of a solution that allows IPv6 hosts, which do not have a permanently assigned IPv4 addresses, to communicate with IPv4-only hosts. The document neither specifies address assignment nor routing to and from the IPv6 hosts when they communicate with the IPv4-only hosts.
rp: ncia-nsii
status:
  uri: https://www.ietf.org/rfc/rfc2765.txt
  history: 
    - flag: added
      date: 2005-11-20
      rfcp: 6-19
      version: 0.7
    - flag: changed
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: f7fbf490-d0c9-4d52-802d-66105b6dcc94
coverdocument:
consumers:
  - bsp-Transport_Services
---
