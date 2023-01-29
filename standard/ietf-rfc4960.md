---
element: Standard
complete: true
nispid: ietf-rfc4960
url: /standard/ietf-rfc4960.html
nisptag: "IETF RFC 4960"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 4960"
  title: "Stream Control Transmission Protocol"
  date: "2007-09"
  version: ""
applicability: >2
  This document describes the Stream Control Transmission Protocol (SCTP). SCTP is designed to transport Public Switched Telephone Network (PSTN) signaling messages over IP networks, but is capable of broader applications.  SCTP is a reliable transport protocol operating on top of a connectionless packet network such as IP. It offers the following services to its users 

    

  *  acknowledged error-free non-duplicated transfer of user data,

  *  data fragmentation to conform to discovered path MTU size,

  *  sequenced delivery of user messages within multiple streams, with an option for order-of-arrival delivery of individual user messages,

  *  optional bundling of multiple user messages into a single SCTP packet, and

  *  network-level fault tolerance through supporting of multi-homing at either or both ends of an association.



    The design of SCTP includes appropriate congestion avoidance behavior and resistance to flooding and masquerade attacks.

  
rp: ncia-nsii
status:
  uri: https://www.ietf.org/rfc/rfc4960.txt
  history: 
    - flag: added
      date: 2007-02-21
      rfcp: 
      version: 1.0
    - flag: changed
      date: 2010-10-30
      rfcp: 
      version: 5.0
    - flag: changed
      date: 2011-06-14
      rfcp: 5-22
      version: 6.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 5207a82a-ac43-4859-9576-95e990b7a018
coverdocument:
consumers:
---
