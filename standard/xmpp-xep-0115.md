---
element: Standard
complete: true
nispid: xmpp-xep-0115
url: /standard/xmpp-xep-0115.html
nisptag: "XMPP XEP-0115 (2008/02)"
orgid: xmpp
document:
  org: xmpp
  pubnum: "XEP-0115 (2008/02)"
  title: "XEP-0115: Entity Capabilities (2008/02)"
  date: "2008-02-26"
  version: "1.5"
applicability: >2
  This document defines an XMPP protocol extension for broadcasting and dynamically discovering client, device, or generic entity capabilities. In order to minimize network impact, the transport mechanism is standard XMPP presence broadcast (thus forestalling the need for polling related to service discovery data), the capabilities information can be cached either within a session or across sessions, and the format has been kept as small as possible.
rp: fmn-cpwg
status:
  uri: http://xmpp.org/extensions/xep-0115.html
  history: 
    - flag: added
      date: 2013-10-22
      rfcp: 7-27
      version: 8.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-17
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 1691605d-2f85-4cc4-91e8-93fc66e96f24
coverdocument:
consumers:
  - fmn3-basic-text-based-collaboration-profile
---
