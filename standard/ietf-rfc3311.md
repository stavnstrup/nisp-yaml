---
element: Standard
complete: true
nispid: ietf-rfc3311
url: /standard/ietf-rfc3311.html
nisptag: "IETF RFC 3311"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 3311"
  title: "The Session Initiation Protocol (SIP) UPDATE Method"
  date: "2002-09"
  version: ""
applicability: >2
  UPDATE allows a client to update parameters of a session (such as the set of media streams and their codecs) but has no impact on the state of a dialog. In that sense, it is like a re-INVITE, but unlike re-INVITE, it can be sent before the initial INVITE has been completed. This makes it very useful for updating session parameters within early dialogs.
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc3311.txt
  history: 
    - flag: added
      date: 2015-11-02
      rfcp: 8-5
      version: 9.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-17
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: a26d8ff0-ebfd-4d41-9459-f97183f2fd09
coverdocument:
consumers:
  - fmn3-session-initiation-and-control-profile
  - fmn4-20211022-prf-84
  - fmn5-20221202-prf-84
---
