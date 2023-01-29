---
element: Standard
complete: true
nispid: oasis-ws-discovery-1.1
url: /standard/oasis-ws-discovery-1.1.html
nisptag: "WS-Discovery v1.1"
orgid: oasis
document:
  org: oasis
  pubnum: "wsdd-discovery-1.1-spec"
  title: "Web Services Dynamic Discovery Version 1.1"
  date: "2009-07-01"
  version: "1.1"
applicability: >2
  This specification defines a discovery protocol to locate services. In an ad hoc mode of operation, probes are sent to a multicast group, and target services that match return a response directly to the requester. To scale to a large number of endpoints and to extend the reach of the protocol, this protocol defines a managed mode of operation and a multicast suppression behavior if a discovery proxy is available on the network. To minimize the need for polling, target services that wish to be discovered send an announcement when they join and leave the network.
rp: ncia-ces
status:
  uri: http://docs.oasis-open.org/ws-dd/discovery/1.1/os/wsdd-discovery-1.1-spec-os.pdf
  history: 
    - flag: added
      date: 2012-07-15
      rfcp: 6-6
      version: 7.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
uuid: 7265ca2d-b326-4488-8da9-3a9a4af07829
coverdocument:
consumers:
  - bsp-Service_Discovery_Services
---
