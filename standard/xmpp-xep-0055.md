---
element: Standard
complete: true
nispid: xmpp-xep-0055
url: /standard/xmpp-xep-0055.html
nisptag: "XMPP XEP-0055"
orgid: xmpp
document:
  org: xmpp
  pubnum: "XEP-0055"
  title: "XEP-0055: Jabber Search"
  date: "2009-09-15"
  version: ""
applicability: >2
  This specification documents a protocol currently used to search information repositories on the Jabber network. To date, the jabber iq search protocol has been used mainly to search for people who have registered with user directories (e.g., the Jabber User Directory hosted at users.jabber.org). However, the jabber iq search protocol is not limited to user directories, and could be used to search other Jabber information repositories (such as chatroom directories) or even to provide a Jabber interface to conventional search engines. The basic functionality is to query an information repository regarding the possible search fields, to send a search query, and to receive search results. Note well that there is currently no mechanism for paging through results or limiting the number of hits, and that the allowable search fields are limited to those defined in the XML schema; however, extensibility MAY be provided via the Data Forms (XEP-0004) protocol.
rp: fmn-cpwg
status:
  uri: http://xmpp.org/extensions/xep-0055.html
  history: 
    - flag: added
      date: 2017-04-20
      rfcp: 9-15
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 4faca012-5c36-4a5c-8339-bc859228e9a9
coverdocument:
consumers:
  - fmn3-basic-text-based-collaboration-profile
  - fmn4-20211022-prf-3
  - sip-mesg-col-serv-core-and-advanced-instant-messaging-collaboration
  - fmn5-20221202-prf-176
---
