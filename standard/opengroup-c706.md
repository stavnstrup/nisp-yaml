---
element: Standard
complete: true
nispid: opengroup-c706
url: /standard/opengroup-c706.html
nisptag: "Open Group C706"
orgid: opengroup
document:
  org: opengroup
  pubnum: "C706"
  title: "DCE 1.1: Remote Procedure Call"
  date: "1997-08-14"
  version: ""
applicability: >2
  Distributed computing services include specifications for remote procedure calls and distributed real-time support in heterogeneous networks (as opposed to single node support as specified in operating system services). Distributed access services include functional support for submitting, starting, and stopping processes among processors in a heterogeneous network. OSF RPC includes support for naming, dynamic binding, and security (authentication, data privacy, and integrity protection).  The so-called authenticated RPC works with the authentication and authorisation service provided by the DCE security service. It is implemented as a set of RPC routines, which ensure a secure communication between client and server. When a client establishes authenticated RPC it can specify the level of protection to be applied to its communications with the server 

  

  *  no protection

  *  encryption of all user data in each cell

  *  integrity verification of the data

  *  authentication of the origin of data

  
rp: ncia-ces
status:
  uri: https://www2.opengroup.org/ogsys/catalog/C706
  history: 
    - flag: added
      date: 1996-03-13
      rfcp: 
      version: 0.1
    - flag: changed
      date: 2001-11-21
      rfcp: 
      version: 0.3
    - flag: changed
      date: 2005-09-08
      rfcp: 
      version: 0.7
    - flag: changed
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 366df477-3f46-4016-beec-957a7c0a95ea
coverdocument:
consumers:
  - bsp-Infrastructure_Networking_Services
---
