---
element: Serviceprofile
nispid: fmn3-web-services-profile
url: /serviceprofile/fmn3-web-services-profile.html
sptype: coi
title: FMN Spiral 3.0 Web Services Profile
profilespec:
  org: fmn
  pubnum: 
  title: FMN Spiral 3 Standards Profile
  date: 2018-10-26
  version: 3
description: The Web Services Profile provides standards and guidance for transport-neutral mechanisms to address structured exchange of information in a decentralized, distributed environment via web services.
taxonomy:
  - T-06d559b4-1bdf-40cc-904f-4e745a170f24-X
refgroup:
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: w3c-note-soap-20000508
    - refid: w3c-note-wsdl-20010315
    - refid: w3c-note-wsdl20-soap11-binding-20070626
    - refid: w3c-address
    description: 
  - obligation: conditional
    lifecycle: current
    standards: 
    - refid: acm-2002-rest-toit
    description: 
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: w3c-cr-cors-20130129
    description: Provide the elements a web service needs to deliver a suitable UI service, such as remote portlet functionality.
  - obligation: recommended
    lifecycle: current
    standards: 
    - refid: oasis-relmes
    description: Reliable messaging for web services, describes a protocol that allows messages to be transferred reliably between nodes implementing this protocol in the presence of software component, system, or network failures.
status:
  uri: 
  history: 
    - flag: added
      date: 2018-11-26
      rfcp: 11-57
      version: 12.0
uuid: 27c7d548-a9f7-4fe3-bd79-6c7791ee7f87
parents:
  - refid: fmn3-pr-webhost
    type: profile
    title: FMN Spiral 3 Web Hosting Profile
---
