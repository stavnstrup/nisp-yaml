---
element: Standard
complete: true
nispid: xmpp-xep-0138
url: /standard/xmpp-xep-0138.html
nisptag: "XMPP XEP-0138"
orgid: xmpp
document:
  org: xmpp
  pubnum: "XEP-0138"
  title: "XEP-0138: Stream Compression"
  date: "2009-05-27"
  version: "2.0"
applicability: >2
  This document defines an XMPP protocol extension for negotiating compression of XML streams, especially in situations where standard TLS compression cannot be negotiated. The protocol provides a modular framework that can accommodate a wide range of compression algorithms; the ZLIB compression algorithm is mandatory-to-implement, but implementations may support other algorithms in addition.
rp: ncia
status:
  uri: http://xmpp.org/extensions/xep-0138.html
  history: 
    - flag: added
      date: 2013-09-04
      rfcp: 
      version: 8.0
    - flag: deleted
      date: 2017-01-26
      rfcp: 9-21
      version: 10.0
    - flag: changed
      date: 2017-04-18
      rfcp: 9-15
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 42ddf6e2-a42e-4a17-aef9-a32a2b81e2e7
coverdocument:
consumers:
  - sip-bcs-basic-collaboration
  - sip-mesg-col-serv-core-and-advanced-instant-messaging-collaboration
---
