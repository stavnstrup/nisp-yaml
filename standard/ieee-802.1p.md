---
element: Standard
complete: true
nispid: ieee-802.1p
url: /standard/ieee-802.1p.html
nisptag: "IEEE 802.1p-2004"
orgid: ieee
document:
  org: ieee
  pubnum: "802.1p"
  title: "IEEE QoS"
  date: "2004-06-09"
  version: ""
applicability: >2
  IEEE P802.1p is the name of a task group active during 1995-98 responsible for adding traffic class expediting and dynamic multicast filtering to the IEEE 802.1D standard. Essentially, they provided a mechanism for implementing Quality of Service (QoS) at the Media Access Control (MAC) level. The group's work with the new priority classes and Generic Attribute Registration Protocol (GARP) was not published separately but was incorporated into a major revision of the standard, IEEE 802.1D-1998. It also required a short amendment extending the frame size of the Ethernet standard by four bytes which was published as IEEE 802.3ac in 1998.  The QoS technique developed by the working group, also known as class of service (CoS), is a 3-bit field called the Priority Code Point (PCP) within an Ethernet frame header when using VLAN tagged frames as defined by IEEE 802.1Q. It specifies a priority value of between 0 and 7 inclusive that can be used by QoS disciplines to differentiate traffic. Although this technique is commonly referred to as IEEE 802.1p, there is no standard or amendment by that name published by the IEEE. Rather the technique is incorporated into IEEE 802.1Q standard which specifies the tag inserted into an Ethernet frame.

  
rp: ncia-nsii
status:
  uri: http://www.ieee802.org/1/pages/802.1D.html
  history: 
    - flag: added
      date: 2012-09-02
      rfcp: 6-33
      version: 7.0
    - flag: changed
      date: 2013-06-18
      rfcp: 
      version: 8.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 46ebd498-b433-4ffb-af2b-2b34442d9f66
coverdocument:
consumers:
  - bsp-SOA_Platform_SMC_Services
---
