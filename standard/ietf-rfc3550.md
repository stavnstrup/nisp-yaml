---
element: Standard
complete: true
nispid: ietf-rfc3550
url: /standard/ietf-rfc3550.html
nisptag: "IETF RFC 3550"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 3550"
  title: "RTP: A Transport Protocol for Real-Time Applications"
  date: "2003-07"
  version: ""
applicability: >2
  This memorandum describes RTP, the real-time transport protocol. RTP provides end-to-end network transport functions suitable for applications transmitting real-time data, such as audio, video or simulation data, over multicast or unicast network services. RTP does not address resource reservation and does not guarantee quality-of-service for real-time services. The data transport is augmented by a control protocol (RTCP) to allow monitoring of the data delivery in a manner scalable to large multicast networks, and to provide minimal control and identification functionality. RTP and RTCP are designed to be independent of the underlying transport and network layers. The protocol supports the use of RTP-level translators and mixers.
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc3550.txt
  history: 
    - flag: added
      date: 2012-09-02
      rfcp: 6-24
      version: 7.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-17
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 48d7e4e1-37b2-4612-934e-c72f03964dac
coverdocument:
consumers:
  - bsp-Infrastructure_Services
  - fmn3-media-streaming-profile
  - fmn4-20211022-prf-69
  - fmn5-20221202-prf-69
---
