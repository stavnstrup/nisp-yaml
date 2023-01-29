---
element: Standard
complete: true
nispid: ietf-rfc4411
url: /standard/ietf-rfc4411.html
nisptag: "IETF RFC 4411"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 4411"
  title: "Extending the Session Initiation Protocol (SIP) Reason Header for Preemption Events"
  date: "2006-02"
  version: ""
applicability: >2
  This document proposes an IANA Registration extension to the Session Initiation Protocol (SIP) Reason Header to be included in a BYE Method Request as a result of a session preemption event, either at a user agent (UA), or somewhere in the network involving a reservation-based protocol such as the Resource ReSerVation Protocol (RSVP) or Next Steps in Signaling (NSIS). This document does not attempt to address routers failing in the packet path; instead, it addresses a deliberate tear down of a flow between UAs, and informs the terminated UA(s) with an indication of what occurred.
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc4411.txt
  history: 
    - flag: added
      date: 2017-04-30
      rfcp: 9-6
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 7679ac52-6d3c-4a60-92df-aa24185973d7
coverdocument:
consumers:
  - fmn3-priority-and-pre-emption-profile
  - fmn4-20211022-prf-72
  - fmn5-20221202-prf-72
---
