---
element: Standard
complete: true
nispid: ietf-rfc4028
url: /standard/ietf-rfc4028.html
nisptag: "IETF RFC 4028"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 4028"
  title: "Session Timers in the Session Initiation Protocol (SIP)"
  date: "2005-04"
  version: ""
applicability: >2
  This document defines an extension to the Session Initiation Protocol (SIP). This extension allows for a periodic refresh of SIP sessions through a re-INVITE or UPDATE request. The refresh allows both user agents and proxies to determine whether the SIP session is still active. The extension defines two new header fields  Session-Expires, which conveys the lifetime of the session, and Min-SE, which conveys the minimum allowed value for the session timer.
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc4028.txt
  history: 
    - flag: added
      date: 2012-09-02
      rfcp: 6-23
      version: 7.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-17
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: d73751ff-cb01-4f93-94b5-af04e88c35d1
coverdocument:
consumers:
  - fmn3-session-initiation-and-control-profile
  - fmn4-20211022-prf-84
  - fmn5-20221202-prf-84
---
