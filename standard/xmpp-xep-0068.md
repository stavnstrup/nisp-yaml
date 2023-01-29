---
element: Standard
complete: true
nispid: xmpp-xep-0068
url: /standard/xmpp-xep-0068.html
nisptag: "XMPP XEP-0068"
orgid: xmpp
document:
  org: xmpp
  pubnum: "XEP-0068"
  title: "XEP-0068: Field Standardization for Data Forms"
  date: "2012-05-28"
  version: ""
applicability: >2
  XMPP extensions that reuse Data Forms (XEP-0004), such as Multi-User Chat (XEP-0045) and Ad-Hoc Commands (XEP-0050), typically need a way to gather data from both humans (using a GUI format) and computer processes (using a pre-defined but flexible format). The 'jabber x data' namespace provides an adequate mechanism for both of these uses, as long as computer processes can rely on the var= names on a particular type of form. This document defines a mechanism for the XMPP Registrar to standardize the field names in such forms, thus enabling XMPP clients to process forms as they have to this point while giving protocol authors a way to specify a mechanism for non-GUI processors to determine the semantic meanings of forms and their constituent fields.
rp: ncia
status:
  uri: https://xmpp.org/extensions/xep-0068.html
  history: 
    - flag: added
      date: 2017-04-20
      rfcp: 9-15
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: c024b895-6732-4bfc-a65e-306e855e0d76
coverdocument:
consumers:
  - fmn4-20211022-prf-118
  - sip-mesg-col-serv-core-and-advanced-instant-messaging-collaboration
  - fmn5-20221202-prf-2
  - fmn5-20221202-prf-118
  - fmn5-20221202-prf-175
---
