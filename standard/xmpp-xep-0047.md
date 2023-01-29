---
element: Standard
complete: true
nispid: xmpp-xep-0047
url: /standard/xmpp-xep-0047.html
nisptag: "XMPP XEP-0047"
orgid: xmpp
document:
  org: xmpp
  pubnum: "XEP-0047"
  title: "XEP-0047: In-Band Bytestreams"
  date: "2012-06-22"
  version: ""
applicability: >2
  This document describes In-Band Bytestreams (IBB), an XMPP protocol extension that enables two entities to establish a virtual bytestream over which they can exchange Base64-encoded chunks of data over XMPP itself. Because IBB provides a generic bytestream, its usage is open-ended. To date it has been used as a fallback method for sending files (see SI File Transfer (XEP-0096) and Jingle File Transfer (XEP-0234)) when out-of-band methods such as SOCKS5 Bytestreams (XEP-0065) are not available. However, IBB could also be useful for any kind of relatively low-bandwidth activity, such as games, shell sessions, or encrypted text.
rp: fmn-cpwg
status:
  uri: https://xmpp.org/extensions/xep-0047.html
  history: 
    - flag: added
      date: 2017-04-30
      rfcp: 9-6
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 867da4a7-ce12-4026-bed7-489b35d2689c
coverdocument:
consumers:
  - fmn3-basic-text-based-collaboration-profile
  - fmn4-20211022-prf-3
---
