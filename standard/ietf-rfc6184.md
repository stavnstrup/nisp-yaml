---
element: Standard
complete: true
nispid: ietf-rfc6184
url: /standard/ietf-rfc6184.html
nisptag: "IETF RFC 6184"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 6184"
  title: "RTP Payload Format for H.264 Video"
  date: "2011-05"
  version: ""
applicability: >2
  This memo describes an RTP Payload format for the ITU-T Recommendation H.264 video codec and the technically identical ISO/IEC International Standard 14496-10 video codec, excluding the Scalable Video Coding (SVC) extension and the Multiview Video Coding extension, for which the RTP payload formats are defined elsewhere. The RTP payload format allows for packetization of one or more Network Abstraction Layer Units (NALUs), produced by an H.264 video encoder, in each RTP payload. The payload format has wide applicability, as it supports applications from simple low bitrate conversational usage, to Internet video streaming with interleaved transmission, to high bitrate video-on-demand.
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc6184.txt
  history: 
    - flag: added
      date: 2017-04-27
      rfcp: 9-6
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 63cdc79e-e218-4d3f-ad5e-d97b8f7669fe
coverdocument:
consumers:
  - fmn3-video-based-collaboration-profile
  - fmn4-20211022-prf-94
  - fmn5-20221202-prf-94
---
