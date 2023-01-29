---
element: Standard
complete: true
nispid: ietf-rfc4568
url: /standard/ietf-rfc4568.html
nisptag: "IETF RFC 4568"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 4568"
  title: "Session Description Protocol (SDP) Security Descriptions for Media Streams"
  date: "2006-07"
  version: ""
applicability: >2
  This document defines a Session Description Protocol (SDP) cryptographic attribute for unicast media streams. The attribute describes a cryptographic key and other parameters that serve to configure security for a unicast media stream in either a single message or a roundtrip exchange. The attribute can be used with a variety of SDP media transports, and this document defines how to use it for the Secure Real-time Transport Protocol (SRTP) unicast media streams. The SDP crypto attribute requires the services of a data security protocol to secure the SDP message.
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc4568.txt
  history: 
    - flag: added
      date: 2017-04-30
      rfcp: 9-6
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 7bd3462e-3c07-418f-9307-654e52944be2
coverdocument:
consumers:
  - fmn3-srtp-based-media-infrastructure-security-profile
  - fmn4-20211022-prf-79
  - fmn5-20221202-prf-79
---
