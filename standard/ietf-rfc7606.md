---
element: Standard
complete: true
nispid: ietf-rfc7606
url: /standard/ietf-rfc7606.html
nisptag: "IETF RFC 7606"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 7606"
  title: "Revised Error Handling for BGP UPDATE Messages"
  date: "2015-08"
  version: ""
applicability: >2
  According to the base BGP specification, a BGP speaker that receives an UPDATE message containing a malformed attribute is required to reset the session over which the offending attribute was received. This behavior is undesirable because a session reset would impact not only routes with the offending attribute but also other valid routes exchanged over the session. This document partially revises the error handling for UPDATE messages and provides guidelines for the authors of documents defining new attributes. Finally, it revises the error handling procedures for a number of existing attributes.
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc7606.txt
  history: 
    - flag: added
      date: 2017-05-01
      rfcp: 9-6
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: b3d380f6-4aa1-4836-aa7f-9bf2b4490d2f
coverdocument:
consumers:
  - fmn3-inter-autonomous-systems-routing-profile
  - fmn4-20211022-prf-61
  - fmn5-20221202-prf-61
---
