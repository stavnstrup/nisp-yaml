---
element: Standard
complete: true
nispid: xmpp-xep-0160
url: /standard/xmpp-xep-0160.html
nisptag: "XMPP XEP-0160 (2016/01)"
orgid: xmpp
document:
  org: xmpp
  pubnum: "XEP-0160 (2016/01)"
  title: "XEP-0160: Best Practices for Handling Offline Messages (2016/01)"
  date: "2016-01-24"
  version: ""
applicability: >2
  XMPP Core and XMPP IM specify general rules for handling XML stanzas, but explicitly do not address how to handle message stanzas sent to recipients (e.g., IM users or other nodes) that are offline, except to say that a server MUST return a <service-unavailable/> error if offline message storage or message forwarding is not enabled (see RFC 6121). This document fills the gap by specifying best practices for storage and delivery of so-called offline messages.
rp: fmn-cpwg
status:
  uri: https://xmpp.org/extensions/xep-0160.html
  history: 
    - flag: added
      date: 2017-04-30
      rfcp: 9-6
      version: 10.0
    - flag: changed
      date: 2018-12-06
      rfcp: 11-57
      version: 12.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 29f9b5dd-1f98-45ef-98a8-705892bba91f
coverdocument:
consumers:
  - fmn3-basic-text-based-collaboration-profile
  - fmn4-20211022-prf-3
  - fmn5-20221202-prf-3
---
