---
element: Standard
complete: true
nispid: xmpp-xep-0220
url: /standard/xmpp-xep-0220.html
nisptag: "XMPP XEP-0220 (2013/09)"
orgid: xmpp
document:
  org: xmpp
  pubnum: "XEP-0220 (2013/09)"
  title: "XEP-0220: Server Dialback (2013/09)"
  date: "2013-09-27"
  version: "1.0"
applicability: >2
  This specification defines the Server Dialback protocol, which is used between XMPP servers to provide identity verification. Server Dialback uses the Domain Name System (DNS) as the basis for verifying identity; the basic approach is that when a receiving server accepts a server-to-server connection from an initiating server, it does not process XMPP stanzas over the connection until it has verified the initiating server's identity. Additionally, the protocol is used to negotitate whether the receiving server is accepting stanzas for the target domain. Although Server Dialback does not provide strong authentication and is subject to DNS poisoning attacks, it has effectively prevented most address spoofing on the XMPP network since its development in the year 2000.
rp: fmn-cpwg
status:
  uri: http://xmpp.org/extensions/xep-0220.html
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
uuid: 148080ef-cf56-4b9f-b8ca-190f19439d09
coverdocument:
consumers:
  - sip-bcs-basic-collaboration
  - sip-mesg-col-serv-core-and-advanced-instant-messaging-collaboration
---
