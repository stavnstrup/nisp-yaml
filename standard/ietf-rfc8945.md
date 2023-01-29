---
element: Standard
complete: true
nispid: ietf-rfc8945
url: /standard/ietf-rfc8945.html
nisptag: "IETF RFC 8945"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 8945"
  title: "Secret Key Transaction Authentication for DNS (TSIG)"
  date: "2020-11"
  version: ""
applicability: >2
    This document describes a protocol for transaction-level authentication using shared secrets and one-way hashing. It can be used to authenticate dynamic updates to a DNS zone as coming from an approved client or to authenticate responses as coming from an approved name server.

    No recommendation is made here for distributing the shared secrets; it is expected that a network administrator will statically configure name servers and clients using some out-of-band mechanism.

    This document obsoletes RFCs 2845 and 4635.

  
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/doc/rfc/rfc8945.txt
  history: 
    - flag: added
      date: 2022-05-06
      rfcp: 14-32
      version: 15.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 392b5234-0e34-40c6-8eb1-43007568e4c5
coverdocument:
consumers:
  - fmn5-20221202-prf-122
---
