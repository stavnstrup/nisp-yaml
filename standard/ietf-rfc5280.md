---
element: Standard
complete: true
nispid: ietf-rfc5280
url: /standard/ietf-rfc5280.html
nisptag: "IETF RFC 5280"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 5280"
  title: "Internet X.509 Public Key Infrastructure Certificate and Certificate Revocation List (CRL) Profile"
  date: "2008-05"
  version: ""
applicability: >2
  This document profiles the X.509 v3 certificate and X.509 v2 CRL for use in the Internet. An overview of the approach and model are provided as an introduction. The X.509 v3 certificate format is described in detail, with additional information regarding the format and semantics of Internet name forms (e.g., IP addresses). Standard certificate extensions are described and one new Internet-specific extension is defined. A required set of certificate extensions is specified. The X.509 v2 CRL format is described and a required extension set is defined as well. An algorithm for X.509 certificate path validation is described. Supplemental information is provided describing the format of public keys and digital signatures in X.509 certificates for common Internet public key encryption algorithms (i.e., RSA, DSA, and Diffie-Hellman). ASN.1 modules and examples are provided in the appendices.
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc5280.txt
  history: 
    - flag: added
      date: 2010-12-05
      rfcp: 
      version: 5.0
    - flag: changed
      date: 2011-06-14
      rfcp: 5-20
      version: 6.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-17
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 00bc89ae-3f33-4cb8-b9be-70bb7e861292
coverdocument:
consumers:
  - binding-crypto-cryptographic-artefact-binding
  - bsp-Security_Token_Services
  - fmn3-digital-certificate-profile
  - fmn4-20211022-prf-12
  - sip-for-tls-profile
---
