---
element: Standard
complete: true
nispid: ietf-rfc2047
url: /standard/ietf-rfc2047.html
nisptag: "IETF RFC 2047"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 2047"
  title: "Multipurpose Internet Mail Extensions (MIME) Part Three: Message Header Extensions for Non-ASCII Text"
  date: "1996-11"
  version: ""
applicability: >2
  RFC 822 1982 defines a message representation protocol specifying considerable detail about US-ASCII message headers, and leaves the message content, or message body, as flat US-ASCII text. This set of documents, collectively called the Multipurpose Internet Mail Extensions, or MIME, redefines the format of messages to allow for (1) textual message bodies in character sets other than US-ASCII, (2) an extensible set of different formats for non-textual message bodies, (3) multi-part message bodies, and (4) textual header information in character sets other than US-ASCII. Because RFC 822 1982 said so little about message bodies, these documents are largely orthogonal to (rather than a revision of) RFC 822 1982. The initial document (RFC 2045 1996) specifies the various headers used to describe the structure of MIME messages. The second document, RFC 2046 1996, defines the general structure of the MIME media typing system and defines an initial set of media types. The third document, RFC 2047 1996, describes extensions to RFC 822 1982 to allow non-US-ASCII text data in Internet mail header fields. The fourth document, RFC 2048 1996, specifies various IANA registration procedures for MIME-related facilities. The fifth and final document, RFC 2049 1996, describes MIME conformance criteria as well as providing some illustrative examples of MIME message formats, acknowledgements, and the bibliography.
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc2047.txt
  history: 
    - flag: added
      date: 1998-11-10
      rfcp: 
      version: 0.1
    - flag: changed
      date: 2000-03-13
      rfcp: 
      version: 0.2
    - flag: changed
      date: 2001-11-21
      rfcp: 
      version: 0.3
    - flag: changed
      date: 2005-09-15
      rfcp: 
      version: 0.7
    - flag: changed
      date: 2017-01-14
      rfcp: 9-17
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: d7122e8b-05d3-4370-8bda-dee77274f46e
coverdocument:
consumers:
  - fmn3-content-encapsulation-profile
  - fmn4-20211022-prf-9
  - fmn5-20221202-prf-9
---
