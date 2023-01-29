---
element: Standard
complete: true
nispid: xmpp-xep-0220-1.1
url: /standard/xmpp-xep-0220-1.1.html
nisptag: "XMPP XEP-0220 (2014/08)"
orgid: xmpp
document:
  org: xmpp
  pubnum: "XEP-0220 (2014/08)"
  title: "XEP-0220: Server Dialback (2014/08)"
  date: "2014-08-05"
  version: "1.1"
applicability: >2
  This specification defines the Server Dialback protocol, which is used between XMPP servers to provide identity verification. Server Dialback uses the Domain Name System (DNS) as the basis for verifying identity; the basic approach is that when a receiving server accepts a server-to-server connection from an initiating server, it does not process XMPP stanzas over the connection until it has verified the initiating server's identity. Additionally, the protocol is used to negotitate whether the receiving server is accepting stanzas for the target domain. Although Server Dialback does not provide strong authentication and is subject to DNS poisoning attacks, it has effectively prevented most address spoofing on the XMPP network since its development in the year 2000.
rp: fmn-cpwg
status:
  uri: http://xmpp.org/extensions/xep-0220.html
  history: 
    - flag: added
      date: 2018-11-02
      rfcp: 11-57
      version: 12.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 01218209-a608-43d7-ac4c-726362232ada
coverdocument:
consumers:
  - fmn3-basic-text-based-collaboration-profile
---
