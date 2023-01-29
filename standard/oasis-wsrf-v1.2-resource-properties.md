---
element: Standard
complete: true
nispid: oasis-wsrf-v1.2-resource-properties
url: /standard/oasis-wsrf-v1.2-resource-properties.html
nisptag: "OASIS WS-ResourceProperties Ver 1.2"
orgid: oasis
document:
  org: oasis
  pubnum: "WS-ResourceProperties Ver 1.2"
  title: "Web Services Resource Properties"
  date: "2006-04-01"
  version: "1.2"
applicability: >2
    The relationship between Web services and stateful resources is defined in [WS-Resource]. This relationship is described as the implied resource pattern. In the implied resource pattern, messages to a Web service may include a component that identifies a stateful resource to be used in the execution of the message. We refer to the composition of a stateful resource and a Web service under the implied resource pattern as a WS�18 Resource.

    This document standardizes the means by which the definition of the properties of a WS�20 Resource may be declared as part of a Web service interface. The declaration of the WS�21 Resource’s properties represents a projection of or a view on the WS-Resource’s state.

    This projection is defined in terms of a resource properties document. This resource properties document serves to define a basis for access to the resource properties through Web service interfaces.

    This specification also defines a standard set of message exchanges that allow a requestor to query or update the property values of the WS-Resource. The set of properties defined in the resource properties document associated with the service interface defines the constraints on the valid contents of these message exchanges.

  
rp: fmn-cpwg
status:
  uri: http://docs.oasis-open.org/wsrf/wsrf-ws_resource_properties-1.2-spec-os.pdf
  history: 
    - flag: added
      date: 2022-05-06
      rfcp: 14-32
      version: 15.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: f22fd708-0758-4c13-862e-bd8c2bd63109
coverdocument:
consumers:
  - fmn5-20221202-prf-169
  - fmn5-20221202-prf-170
---
