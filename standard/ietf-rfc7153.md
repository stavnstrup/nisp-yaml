---
element: Standard
complete: true
nispid: ietf-rfc7153
url: /standard/ietf-rfc7153.html
nisptag: "IETF RFC 7153"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 7153"
  title: "IANA Registries for BGP Extended Communities"
  date: "2014-03"
  version: ""
applicability: >2
  This document reorganizes the IANA registries for the type values and sub-type values of the BGP Extended Communities attribute and the BGP IPv6-Address-Specific Extended Communities attribute. This is done in order to remove interdependencies among the registries, thus making it easier for IANA to determine which codepoints are available for assignment in which registries. This document also clarifies the information that must be provided to IANA when requesting an allocation from one or more of these registries. These changes are compatible with the existing allocations and thus do not affect protocol implementations. The changes will, however, impact the IANA Considerations sections of future protocol specifications.
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc7153.txt
  history: 
    - flag: added
      date: 2017-05-01
      rfcp: 9-6
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: eaa8e964-1dac-4059-b404-80b635b7c798
coverdocument:
consumers:
  - fmn3-inter-autonomous-systems-routing-profile
  - fmn4-20211022-prf-61
  - fmn5-20221202-prf-61
---
