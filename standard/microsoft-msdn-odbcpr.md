---
element: Standard
complete: true
nispid: microsoft-msdn-odbcpr
url: /standard/microsoft-msdn-odbcpr.html
nisptag: "MS ODBC 3.8 Programmer's Reference"
orgid: microsoft
document:
  org: microsoft
  pubnum: "MSDN-ODBCPR 3.8"
  title: "Open Database Connectivity (ODBC) 3.8 Programmer's Reference"
  date: "1996-10"
  version: "3.8"
applicability: >2
  Open Database Connectivity (ODBC) is a widely accepted application programming interface (API) for database access. It is based on the Call-Level Interface (CLI) specifications from Open Group and ISO/IEC for database APIs and uses Structured Query Language (SQL) as its database access language.  ODBC is designed for maximum interoperability - that is, the ability of a single application to access different database management systems (DBMSs) with the same source code. Database applications call functions in the ODBC interface, which are implemented in database-specific modules called drivers. The use of drivers isolates applications from database-specific calls in the same way that printer drivers isolate word processing programs from printer-specific commands. Because drivers are loaded at run time, a user only has to add a new driver to access a new DBMS; it is not necessary to recompile or relink the application.

  
rp: ncia-ces
status:
  uri: http://msdn.microsoft.com/en-us/library/ms714177.aspx
  history: 
    - flag: added
      date: 1997-05-21
      rfcp: 
      version: 0.1
    - flag: changed
      date: 2000-03-21
      rfcp: 
      version: 0.2
    - flag: changed
      date: 2005-09-08
      rfcp: 
      version: 0.7
    - flag: changed
      date: 2009-09-08
      rfcp: 
      version: 4.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: a47d2944-ac6c-4c15-9141-b116aeebcd58
coverdocument:
consumers:
  - bsp-Relational_Database_Storage_Services
---
