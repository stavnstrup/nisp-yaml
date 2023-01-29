---
element: Standard
complete: true
nispid: ietf-rfc826
url: /standard/ietf-rfc826.html
nisptag: "IETF RFC 826"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 826"
  title: "Ethernet Address Resolution Protocol"
  date: "1982-11"
  version: ""
applicability: >2
  The implementation of protocol P on a sending host S decides, through protocol P's routing mechanism, that it wants to transmit to a target host T located some place on a connected piece of 10Mbit Ethernet cable. To actually transmit the Ethernet packet a 48.bit Ethernet address must be generated. The addresses of hosts within protocol P are not always compatible with the corresponding Ethernet address (being different lengths or values). Presented here is a protocol that allows dynamic distribution of the information needed to build tables to translate an address A in protocol P's address space into a 48.bit Ethernet address. Generalizations have been made which allow the protocol to be used for non-10Mbit Ethernet hardware. Some packet radio networks are examples of such hardware. The protocol proposed here is the result of a great deal of discussion with several other people.
rp: ncia-nsii
status:
  uri: https://www.ietf.org/rfc/rfc0826.txt
  history: 
    - flag: added
      date: 1998-12-01
      rfcp: 
      version: 0.1
    - flag: changed
      date: 2005-09-16
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
uuid: 2b6652e0-3839-4897-bd6d-8fb3170860fd
coverdocument:
consumers:
  - fmn3-inter-autonomous-systems-ip-transport-profile
  - fmn4-20211022-prf-59
  - fmn5-20221202-prf-127
---
