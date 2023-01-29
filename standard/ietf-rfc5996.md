---
element: Standard
complete: true
nispid: ietf-rfc5996
url: /standard/ietf-rfc5996.html
nisptag: "IETF RFC 5996"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 5996"
  title: "Internet Key Exchange Protocol Version 2 (IKEv2)"
  date: "2010-09"
  version: ""
applicability: >2
  This document describes version 2 of the Internet Key Exchange (IKE) protocol. IKE is a component of IPsec used for performing mutual authentication and establishing and maintaining Security Associations (SAs).  IKE performs mutual authentication between two parties and establishes an IKE security association (SA) that includes shared secret information that can be used to efficiently establish SAs for Encapsulating Security Payload (ESP) or Authentication Header (AH) and a set of cryptographic algorithms to be used by the SAs to protect the traffic that they carry. In this document, the term suite or cryptographic suite refers to a complete set of algorithms used to protect an SA. An initiator proposes one or more suites by listing supported algorithms that can be combined into suites in a mix-and-match fashion. IKE can also negotiate use of IP Compression (IPComp) [IP-COMP] in connection with an ESP or AH SA. The SAs for ESP or AH that get set up through that IKE SA we call Child SAs.

  
rp: c3b-cap4
status:
  uri: https://www.ietf.org/rfc/rfc5996.txt
  history: 
    - flag: added
      date: 1999-01-15
      rfcp: 
      version: 0.1
    - flag: changed
      date: 2000-07-17
      rfcp: 
      version: 0.2
    - flag: changed
      date: 2005-09-23
      rfcp: 
      version: 0.7
    - flag: changed
      date: 2010-10-30
      rfcp: 
      version: 5.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-13
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 4b2fa6f0-27e3-4884-8250-5598660fc3e8
coverdocument:
consumers:
---
