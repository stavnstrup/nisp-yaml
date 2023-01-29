---
element: Standard
complete: true
nispid: ietf-rfc792
url: /standard/ietf-rfc792.html
nisptag: "IETF RFC 792"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 792"
  title: "Internet Control Message Protocol (ICMP)"
  date: "1981-09"
  version: ""
applicability: >2
  The Internet Protocol is not designed to be absolutely reliable. The purpose of these control messages is to provide feedback about problems in the communication environment, not to make IP reliable. There are still no guarantees that a datagram will be delivered or a control message will be returned. Some datagrams may still be undelivered without any report of their loss. The higher level protocols that use IP must implement their own reliability procedures if reliable communication is required.
rp: ncia-nsii
status:
  uri: https://www.ietf.org/rfc/rfc0792.txt
  history: 
    - flag: added
      date: 1998-09-01
      rfcp: 
      version: 0.1
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
uuid: 45ac9270-c34a-4a54-9cc3-38b59f13cdac
coverdocument:
consumers:
---
