---
element: Standard
complete: true
nispid: nato-stanag4643ed1
url: /standard/nato-stanag4643ed1.html
nisptag: "STANAG 4643 Ed 1"
orgid: nato
document:
  org: nato
  pubnum: "STANAG 4643 Ed 1"
  title: "TACOMS: Connection Oriented Network Protocols"
  date: "2010-06-18"
  version: ""
applicability: >2
  TACOMS distinguishes between two Traffic Handling Classes (THCs)  Connectionless (CL) and Connection Oriented (CO). These are described in Section 4.3.1 of STANAG 4637 (TACOMS Head STANAG).  The CL THC handles IP packets while the CO THC handles calls using H.323 protocols over the IOP1. This STANAG specifies the protocols necessary to support the user services in the CO THC.

    Annex A defines the numbering plan for the CO user services.

    Annex E defines the H.323-based call signalling for the CO THC over the IOP1, including the manner in which the numbering (from the numbering plan) is used in the call establishment process.

    Separate routing protocols are defined for the CO and CL THCs. The routing protocols for the CO THC apply to the IOPs and are based on BGP-4. However, in addition to basic IP packet routing, the protocols specify a behaviour enabling calls to be routed between call handlers, as well as procedures for selecting gateways to external networks. The CO routing protocols are defined in Annex C.

    TACOMS is based on transparency of user applications and does not generally specify these applications. However, in order to obtain user interoperability on a minimum set of services, TACOMS specifies a set of CO user services for voice, video and transparent data.

    TACOMS standardises four types of voice coding schemes to be used for voice interoperability. These are

    

  *  MELPe 2K4 (mandatory);

  *  G.711 PCM 64 kb/s (mandatory);

  *  CVSD 16 (optional). There is a selector for the type of integration used for CVSD voice coding in STANAG 4209. The double integration option is assumed; and

  *  G.729 (optional).



    Nations might use other coding schemes within their NEs, but one of the schemes mentioned in paragraph 7 should be presented at IOPs.

    The protocols for coding (voice, video and multimedia), and for negotiation of codecs, transcoding, and data rates, are defined in Annex D.

  
rp: c3b-cap1-nscat
status:
  uri: https://nso.nato.int/
  history: 
    - flag: added
      date: 2005-07-31
      rfcp: 6-11
      version: 0.7
    - flag: changed
      date: 2009-07-28
      rfcp: 
      version: 4.0
    - flag: changed
      date: 2010-11-02
      rfcp: 
      version: 5.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-14
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: aadff38c-0d19-420f-ab82-d4c35a431d84
coverdocument:
consumers:
---
