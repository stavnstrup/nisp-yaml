---
element: Standard
complete: true
nispid: nato-tide-sd-sp
url: /standard/nato-tide-sd-sp.html
nisptag: "TIDE Service Discovery"
orgid: nato
document:
  org: nato
  pubnum: "TIDE/TIDE-ID-SP"
  title: "TIDE Service Discovery"
  date: "2008-10-31"
  version: ""
applicability: >2
  The current solution within TIDE community to announce and discover services is based on Multicast DNS and DNS Service Discovery. It was proven to work efficiently in LAN networks where multicast DNS is used. In the WAN environment where for the proper registration and discovery a control over regular DNS servers is required the solution approach a barrier. In most scenarios, because of the sites security policies, the required access to DNS servers is not granted. As one of the possible ways to overcome this obstacle was introduction of bridging solutions. The problem with this approach is scalability.
rp: ncia-ces
status:
  uri: https://tide.act.nato.int/mediawiki/tidepedia/index.php/TIDE_Service_Discovery
  history: 
    - flag: added
      date: 2010-12-04
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
uuid: 04a2470b-0f95-4cef-9172-d29b5058861e
coverdocument:
consumers:
  - bsp-Service_Discovery_Services
  - bsp-Service_Discovery_Services
---
