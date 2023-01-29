---
element: Standard
complete: true
nispid: cceb-acp133c
url: /standard/cceb-acp133c.html
nisptag: "ACP 133(C)"
orgid: cceb
document:
  org: cceb
  pubnum: "ACP 133(C)"
  title: "Common Directory Services and Procedures"
  date: "2007"
  version: ""
applicability: >2
  The function of this document, Allied Communication Publication (ACP) 133, is to define the Directory services, architecture(s), protocols, schema, policies, and procedures to support Allied communications, including Military Message Handling System (MMHS) services based on ACP 123, in both the strategic and tactical environments. The Directory services are based on the International Telecommunication Union Telecommunication Standardization Sector (ITU-T) X.500 Series of Recommendations and the International Organization for Standardization (ISO) / International Electrotechnical Commission (IEC) 9594. These Directory specifications will be referred to as X.500 in this document. Note that familiarity with X.500 is assumed.  The Allied Directory Services defined in this document are based on the X.500 Directory recommendations. It is expected that an evolutionary period will be necessary for existing directory services to become ACP 133-compliant. In this sense, ACP 133 is viewed as a “target”. The manner, means, and duration of such evolution are outside the scope of ACP 133.

    This ACP applies to communication among the Allied Directory domains and within a domain for combined operations. It defines a common Directory schema which shall be supported by all Allies for international and combined operations. It offers support for Internet mail users and transitional support for ACP 127/Joint Army, Navy, Air Force Procedure (JANAP) 128. The Directory has the potential to support different views of directory information such as white pages and yellow pages services.

    Local interfaces and requirements, such as the specifics of terminal display and local caching, are part of this publication where required to ensure interoperability. ACP 133 includes requirements for which directory information must be displayed to the user, but the format of the display is outside the scope of this document.

    This third version of ACP 133 defines the services, schema, and protocols required of X.500 Directory System Agents (DSAs) and Directory User Agents (DUAs) to support electronic mail (e-mail), S/MIME, Message Handling System (MHS), MMHS, ACP 127 interworking and traditional communications. It also identifies security mechanisms that meet the security requirements for strong authentication, confidentiality, integrity, availability, and privilege/label management. As national systems and products mature, this document will be expanded to include more procedural guidance for managing the directory, support for other applications, and additional guidance for operation of tactical, mobile and deployed directories.

    In order to maximize the number of products supporting ACP 133, the schema definition has been split into a core schema, to which all products must conform, plus optional schema sections relating to PKI Infrastructures and legacy (ACP 127 / JANAP 128) messaging. In addition, LDAP has been added as an alternative Directory Access Protocol, thus reflecting its almost universal adoption over X.500 DAP for general user access to the Directory. Where possible, to maximize compatibility with existing COTS Directory Products, the ACP 133 schema has been redefined to utilize standard attribute syntaxes in preference to proprietary ones used in earlier versions of this document.

  
rp: acp
status:
  uri: https://nhqc3s.hq.nato.int/Pages/Browse.aspx
  history: 
    - flag: added
      date: 1999-02-02
      rfcp: 
      version: 0.1
    - flag: changed
      date: 2000-03-14
      rfcp: 
      version: 0.2
    - flag: changed
      date: 2001-11-20
      rfcp: 
      version: 0.3
    - flag: changed
      date: 2005-09-15
      rfcp: 
      version: 0.7
    - flag: changed
      date: 2008-12-10
      rfcp: 
      version: 3.0
    - flag: changed
      date: 2010-11-16
      rfcp: 
      version: 5.0
    - flag: changed
      date: 2019-10-11
      rfcp: 12-14j
      version: 13.0
    - flag: changed
      date: 2020-01-21
      rfcp: 12-032
      version: 13.0
    - flag: changed
      date: 2020-01-24
      rfcp: 12-034
      version: 13.0
uuid: f6fec31a-2331-459f-82b6-8286b2671c47
coverdocument:
consumers:
  - bsp-Directory_Storage_Services
  - sip-entr-dir-enterprise-directory
---
