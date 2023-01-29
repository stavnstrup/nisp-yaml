---
element: Standard
complete: true
nispid: ietf-rfc2557
url: /standard/ietf-rfc2557.html
nisptag: "IETF RFC 2557"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 2557"
  title: "MIME Encapsulation of Aggregate Documents, such as HTML (MHTML)"
  date: "1993-03"
  version: ""
applicability: >2
  HTML [RFC 1866] defines a powerful means of specifying multimedia documents. These multimedia documents consist of a text/html root resource (object) and other subsidiary resources (image, video clip, applet, etc. objects) referenced by Uniform Resource Identifiers (URIs) within the text/html root resource. When an HTML multimedia document is retrieved by a browser, each of these component resources is individually retrieved in real time from a location, and using a protocol, specified by each URI.  In order to transfer a complete HTML multimedia document in a single e-mail message, it is necessary to  a) aggregate a text/html root resource and all of the subsidiary resources it references into a single composite message structure, and b) define a means by which URIs in the text/html root can reference subsidiary resources within that composite message structure.

  
rp: ncia-ces
status:
  uri: https://www.ietf.org/rfc/rfc2557.txt
  history: 
    - flag: added
      date: 2010-12-05
      rfcp: 
      version: 5.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: f7d9d452-713c-4be1-a367-6d25121583c2
coverdocument:
consumers:
  - archive-archive-web-archive
---
