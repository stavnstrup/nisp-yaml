---
element: Standard
complete: true
nispid: ietf-rfc3768
url: /standard/ietf-rfc3768.html
nisptag: "IETF RFC 3768"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 3768"
  title: "Virtual Router Redundancy Protocol"
  date: "2004-04"
  version: ""
applicability: >2
  This memo defines the Virtual Router Redundancy Protocol (VRRP). VRRP specifies an election protocol that dynamically assigns responsibility for a virtual router to one of the VRRP routers on a LAN. The VRRP router controlling the IP address(es) associated with a virtual router is called the Master, and forwards packets sent to these IP addresses. The election process´ provides dynamic fail over in the forwarding responsibility should the Master become unavailable. This allows any of the virtual router IP addresses on the LAN to be used as the default first hop router by end-hosts. The advantage gained from using VRRP is a higher availability default path without requiring configuration of dynamic routing or router discovery protocols on every end-host.
rp: ncia-nsii
status:
  uri: https://www.ietf.org/rfc/rfc3768.txt
  history: 
    - flag: added
      date: 2003-08-01
      rfcp: 4-29
      version: 0.5
    - flag: changed
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
uuid: 96a0a9af-9d4c-4eee-9184-1c0d7e500d33
coverdocument:
consumers:
  - bsp-Transport_Services
---
