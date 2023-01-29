---
element: Standard
complete: true
nispid: nato-stanag5518ed1
url: /standard/nato-stanag5518ed1.html
nisptag: "STANAG 5518 Ed 1"
orgid: nato
document:
  org: nato
  pubnum: "STANAG 5518 Ed 1"
  title: "Standard for Joint Range Extension Application Protocol (JREAP)"
  date: "2014-03-14"
  version: "Ed 1"
applicability: >2
  This document defines a generalized application protocol, designated as the Joint Range Extension Applications Protocol (JREAP). The JREAP enables tactical data to be transmitted over digital media and networks not originally designed for tactical data exchange.  Formatted tactical digital messages are embedded inside of JREAP messages as data fields within available commercial and Government protocols, such as those used over satellites and terrestrial links. Specialized management messages are also provided to transport data not contained in the formatted messages, in order to support TDL-unique functions. Capabilities are provided that include 

  

  *  extending the range-limited tactical networks to beyond LOS while reducing their dependence upon relay platforms;

  *  reducing the loading on stressed networks;

  *  providing backup communications in the event of the loss of the normal link, and 4) providing a connection to a platform that may not be equipped with the specialized communications equipment for that TDL.

    For media that do not support OSI network and transport layers, the JREAP provides network and transport layer functionality. For media supporting OSI network and transport layers, the JREAP is encapsulated within those layers. JREAP software can be integrated into a host system or into a stand-alone processor. The appropriate interface terminals are required at each end of any JREAP alternate media link.

  
rp: c3b-cap1-tdlcat
status:
  uri: https://nso.nato.int/
  history: 
    - flag: added
      date: 2005-11-20
      rfcp: 6-17
      version: 0.7
    - flag: changed
      date: 2012-09-03
      rfcp: 6-55
      version: 7.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-14
      version: 10.0
    - flag: changed
      date: 2017-03-03
      rfcp: 9-46
      version: 10.0
uuid: 48d07ce8-1a12-4ca4-8ee0-7bafd7723d9a
coverdocument:
consumers:
---
