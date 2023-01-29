---
element: Standard
complete: true
nispid: xmpp-xep-0060
url: /standard/xmpp-xep-0060.html
nisptag: "XMPP XEP-0060 (2010/07)"
orgid: xmpp
document:
  org: xmpp
  pubnum: "XEP-0060 (2010/07)"
  title: "XEP-0060: Publish-Subscribe (2010/07)"
  date: "2010-07-12"
  version: "1.13"
applicability: >2
  This specification defines an XMPP protocol extension for generic publish-subscribe functionality. The protocol enables XMPP entities to create nodes (topics) at a pubsub service and publish information at those nodes; an event notification (with or without payload) is then broadcasted to all entities that have subscribed to the node. Pubsub therefore adheres to the classic Observer design pattern and can serve as the foundation for a wide variety of applications, including news feeds, content syndication, rich presence, geolocation, workflow systems, network management systems, and any other application that requires event notifications.
rp: ncia
status:
  uri: http://xmpp.org/extensions/xep-0060.html
  history: 
    - flag: added
      date: 2013-09-04
      rfcp: 
      version: 8.0
    - flag: deleted
      date: 2017-01-26
      rfcp: 9-21
      version: 10.0
    - flag: changed
      date: 2017-04-19
      rfcp: 9-15
      version: 10.0
    - flag: changed
      date: 2018-11-27
      rfcp: 
      version: 12.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 5be5cc23-2023-4fad-a7a7-e38c8656efc1
coverdocument:
consumers:
  - binding-xmpp-extensible-message-and-presence-protocol-xmpp-binding
  - fmn3-basic-text-based-collaboration-profile
  - sip-mesg-col-serv-core-and-advanced-instant-messaging-collaboration
---
