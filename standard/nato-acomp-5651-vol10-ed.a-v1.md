---
element: Standard
complete: false
nispid: nato-acomp-5651-vol10-ed.a-v1
url: /standard/nato-acomp-5651-vol10-ed.a-v1.html
nisptag: "AComP-5651 (Study) Ed A Ver 1 - Vol 10"
orgid: nato
document:
  org: nato
  pubnum: "AComP-5651 (Study) Ed A Ver 1 - Vol 10"
  title: "HDR WF (ESSOR) LLC Layer Specification and Rationale (SSS) / Interface Control Document (ICD)"
  date: ""
  version: "1"
applicability: >2
    The LLC SSS defines 8 functional modules 

  

  *  LLC-QS   Queuing, scheduling and active queue management

  *  LLC-SAR   Segmentation and reassembly, to adapt incoming data to a suitable size for the transmission opportunities inside the WF. LLC provide an end-to-end SAR.

  *  LLC-FWD   Waveform internal message forwarding of unicast, broadcast and multicast messages, Multicast and broadcast duplicate detection

  *  LLC-ARQ   procedures to retransmit data on a hop-by-hop basis to increase the end-to-end probability of correct reception (ARQ based on selective NACK for unicast traffic)

  *  LLC-TM   Traffic metering, measurements of arrival rates and other relevant metrics provided for the MAC, NET and management layers

  *  LLC-FRI   Fragmentation and interleaving

  *  LLC-PTT   Queuing of vocoder frames exchanged in the PTT groups and PTT PDU construction

  *  LLC-MGT

  
rp: c3b-cap1-bloscat
status:
  uri: https://nso.nato.int/protected/nsdd/main/standards/ap-details/3013/EN
  history: 
    - flag: added
      date: 2022-05-06
      rfcp: 14-32
      version: 15.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 46ec8d06-095b-4d28-b461-80f83618a1e9
coverdocument:
  - nato-stanag5651ed1
consumers:
  - fmn5-20221202-prf-150
---
