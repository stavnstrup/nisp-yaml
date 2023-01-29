---
element: Standard
complete: true
nispid: opengroup-p702
url: /standard/opengroup-p702.html
nisptag: "Open Group P702"
orgid: opengroup
document:
  org: opengroup
  pubnum: "P702"
  title: "Single Sign On"
  date: "1997-06-14"
  version: ""
applicability: >2
  High value business information is increasingly being maintained within multiple data processing systems in distributed system architectures. Security for each system demands effective access controls whilst administrators are faced with significant overheads for handling multiple accounts for each user. XXSO-PAM provides a standard interface between applications and sign-on systems so that whatever the underlying technology of the application's authentication technology, they will plug-and-play with a coordinating primary single sign-on system. This enables applications and their host systems to continue to maintain their own account databases, but it also enables those applications to move towards use of the more strategic distributed security services, enabling migration from multiple uncoordinated security systems to a coherent security architecture for all applications. PAM also simplifies some aspects of security management. The XSSO-PAM Specification therefore supports a practical approach which enables sign-on (SSO) for applications in a distributed environment.
rp: c3b-cap4
status:
  uri: https://www2.opengroup.org/ogsys/catalog/p702
  history: 
    - flag: added
      date: 2002-10-11
      rfcp: 
      version: 0.4
    - flag: changed
      date: 2003-08-01
      rfcp: 
      version: 0.5
    - flag: changed
      date: 2005-09-23
      rfcp: 
      version: 0.7
    - flag: changed
      date: 2017-01-14
      rfcp: 9-13
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: c037f744-c873-4674-b9b5-0c88a0afd882
coverdocument:
consumers:
  - bsp-Security_Token_Services
---
