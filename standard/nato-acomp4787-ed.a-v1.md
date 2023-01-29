---
element: Standard
complete: true
nispid: nato-acomp4787-ed.a-v1
url: /standard/nato-acomp4787-ed.a-v1.html
nisptag: "AComp-4787 Ed A Ver 1"
orgid: nato
document:
  org: nato
  pubnum: "AComp-4787 Ed A Ver 1"
  title: "Networking and Information Infrastructure (NII) Internet Protocol (IP) Network Encryptor – Interoperability Specification (NINE ISPEC)"
  date: "2018-01-25"
  version: ""
applicability: >2
    AComP-4787 Ed1 contains several sections out of which following form basis for interoperability in the context of FMN SP5 

  

  *  Core Specification

  *  Threshold requirements considered Minimum Interoperability Requirements.



  *  Gateway Extension

  *  Understand that NINE devices for FMN are gateway devices.



  *  Generic Discovery Client Extension

  *  The initiation of the discovery process is required when a packet transmitted to a SA endpoint is marked as unreachable; this is foreseen in NINE Core as part of the “Peer NINE Reachability Detection”. The support of this feature is essential for devices since it ensures the reachability of the NINE endpoints.



  *  Reachability Extension

  *  NINE “Reachability” Extension defines the required mechanism to discover, maintain and advertise subnets of networks which are available at the PlainText interface (including through SAs) using routing protocols (like RIPv2 and RIPng).



  *  Traffic Protection - Suite B Cryptography Core

  
rp: c3b-cap1-loscat
status:
  uri: https://nso.nato.int/protected/nsdd/main/standards/ap-details/2307/EN
  history: 
    - flag: added
      date: 2022-05-06
      rfcp: 14-32
      version: 15.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-65
      version: 15.0
uuid: 81beb07f-ef37-4bd7-b380-f81c1f0d4d1d
coverdocument:
  - nato-stanag4787ed1
consumers:
  - fmn5-20221202-prf-174
---
