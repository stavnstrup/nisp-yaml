---
element: Standard
complete: true
nispid: ietf-rfc5905
url: /standard/ietf-rfc5905.html
nisptag: "IETF RFC 5905"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 5905"
  title: "Network Time Protocol (NTP) Version 4: Protocol and Algorithms Specification"
  date: "2010-06"
  version: ""
applicability: >2
  The Network Time Protocol (NTP) is widely used to synchronize computer clocks in the Internet. This document describes NTP version 4 (NTPv4), which is backwards compatible with NTP version 3 (NTPv3), described in RFC 1305, as well as previous versions of the protocol. NTPv4 includes a modified protocol header to accommodate the Internet Protocol version 6 address family. NTPv4 includes fundamental improvements in the mitigation and discipline algorithms that extend the potential accuracy to the tens of microseconds with modern workstations and fast LANs. It includes a dynamic server discovery scheme, so that in many cases, specific server configuration is not required. It corrects certain errors in the NTPv3 design and implementation and includes an optional extension mechanism.
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc5905.txt
  history: 
    - flag: added
      date: 2000-04-13
      rfcp: 
      version: 0.2
    - flag: changed
      date: 2005-09-15
      rfcp: 
      version: 0.7
    - flag: deleted
      date: 2009-09-12
      rfcp: 
      version: 4.0
    - flag: added
      date: 2010-12-06
      rfcp: 
      version: 5.0
    - flag: changed
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
uuid: 7fd9069f-1e2f-4009-b525-115785fbe39c
coverdocument:
consumers:
  - fmn3-sp-time-synchronization
  - fmn4-20211022-prf-92
  - fmn5-20221202-prf-120
  - fmn5-20221202-prf-121
---
