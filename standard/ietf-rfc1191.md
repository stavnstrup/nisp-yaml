---
element: Standard
complete: true
nispid: ietf-rfc1191
url: /standard/ietf-rfc1191.html
nisptag: "IETF RFC 1191"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 1191"
  title: "Path MTU Discovery"
  date: "1990-11"
  version: ""
applicability: >2
  This memo describes a technique for dynamically discovering the maximum transmission unit (MTU) of an arbitrary internet path. It specifies a small change to the way routers generate one type of ICMP message. For a path that passes through a router that has not been so changed, this technique might not discover the correct Path MTU, but it will always choose a Path MTU as accurate as, and in many cases more accurate than, the Path MTU that would be chosen by current practice.
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc1191.txt
  history: 
    - flag: added
      date: 2019-12-12
      rfcp: 12-025
      version: 13.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: e25d963f-d9df-4168-9e33-9dec328d2a05
coverdocument:
consumers:
  - fmn4-20211022-prf-59
  - fmn4-20211022-prf-88
  - fmn5-20221202-prf-88
  - fmn5-20221202-prf-127
  - fmn5-20221202-prf-154
---
