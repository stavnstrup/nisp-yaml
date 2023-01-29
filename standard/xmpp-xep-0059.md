---
element: Standard
complete: true
nispid: xmpp-xep-0059
url: /standard/xmpp-xep-0059.html
nisptag: "XMPP XEP-0059"
orgid: xmpp
document:
  org: xmpp
  pubnum: "XEP-0059"
  title: "XEP-0059: Result Set Management"
  date: "2006-09-20"
  version: "1.0"
applicability: >2
  This specification defines an XMPP protocol extension that enables an entity to page through and otherwise manage the receipt of large result sets. The protocol can be used in the context of any XMPP protocol that might send large result sets (such as service discovery, multi-user chat, and publish-subscribe). While the requesting entity in such an interaction can explicitly request the use of result set management, an indication that result set management is in use can also be proactively included by the responding entity when returning a limited result set in response to a query.
rp: ncia
status:
  uri: https://xmpp.org/extensions/xep-0059.html
  history: 
    - flag: added
      date: 2017-12-06
      rfcp: 11-29
      version: 11.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: d5d9a19d-91fe-4d6e-9f4b-98de380780dd
coverdocument:
consumers:
  - fmn4-20211022-prf-2
  - fmn5-20221202-prf-2
  - fmn5-20221202-prf-175
---
