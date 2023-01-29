---
element: Standard
complete: true
nispid: opengroup-c702
url: /standard/opengroup-c702.html
nisptag: "Open Group C702"
orgid: opengroup
document:
  org: opengroup
  pubnum: "C702"
  title: "X/Open Network File System (C702 Protocols for Inter-working: XNFS, Version 3W)"
  date: "1998-02-14"
  version: ""
applicability: >2
  XNFS includes the following standard NFS protocol specifications 

  *  RFC 3010 1989, NFS  Network File System protocol specification

  *  RFC 1014 1987, XDR  External data representation standard

  *  RFC 1057 1988, RPC  Remote procedure call protocol specification

    While XDR and RPC are written as general-purpose specifications, their primary use is in the context of NFS. The XNFS specification also defines a number of additional protocols concerned with network monitoring and management and other features. XNFS allows UNIX workstations to access and share files located on remote platforms without the need to download/upload them (i.e. it supports a virtual filestore).

    X/Open intends to adopt IEEE P1003.1f when it becomes a standard. P1003.1f is a draft POSIX operating system API for network transparent file access (TFA).

  
rp: ncia-ces
status:
  uri: http://www.opengroup.org/onlinepubs/009629799/chap7.htm
  history: 
    - flag: added
      date: 1996-03-13
      rfcp: 
      version: 0.1
    - flag: changed
      date: 2000-03-21
      rfcp: 
      version: 0.2
    - flag: changed
      date: 2003-08-01
      rfcp: 
      version: 0.5
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
uuid: 6a6bfb0c-0661-43f7-877d-6b2cf20154f4
coverdocument:
consumers:
  - bsp-Infrastructure_Networking_Services
---
