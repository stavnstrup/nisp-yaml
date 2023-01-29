---
element: Serviceprofile
nispid: fmn3-web-content-profile
url: /serviceprofile/fmn3-web-content-profile.html
sptype: coi
title: FMN Spiral 3.0 Web Content Service Profile
profilespec:
  org: fmn
  pubnum: 
  title: FMN Spiral 3 Standards Profile
  date: 2018-10-26
  version: 3
description: The Web Content Profile provides standards and guidance for the processing, sharing and presentation of web content on federated mission networks. Web presentation services must be based on a fundamental set of basic and widely understood protocols, such as those listed below. Recommendations in the FMN Spiral 2 Service Interface Profile for Web Applications are intended to improve the experience of Web applications and to make information and services available to users irrespective of their device and Web browser. However, it does not mean that exactly the same information is available in an identical representation across all devices  the context of mobile use, device capability variations, bandwidth issues and mobile network capabilities all affect the representation. Some services and information are more suitable for and targeted at particular user contexts. While services may be most appropriately experienced in one context or another, it is considered best practice to provide as reasonable experience as is possible given device limitations and not to exclude access from any particular class of device, except where this is necessary because of device limitations.
taxonomy:
  - T-06d559b4-1bdf-40cc-904f-4e745a170f24-X
refgroup:
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: ietf-rfc2854
    - refid: w3c-rec-html5-20141028
    - refid: ietf-rfc4329
    - refid: w3c-rec-css3-mediaqueries-20120619
    - refid: w3c-rec-css3-selectors-20110929
    description: Publishing information including text, multi-media, hyperlink features, scripting languages and style sheets on the network.
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: w3c-rec-css2-2011067
    - refid: w3c-rec-css-style-attr-20131107
    - refid: w3c-rec-css-namespaces-3-20140320
    - refid: w3c-rec-css3-color-20110607
    description: Providing a common style sheet language for describing presentation semantics (that is, the look and formatting) of documents written in markup languages like HTML.
status:
  uri: 
  history: 
    - flag: added
      date: 2018-11-26
      rfcp: 11-57
      version: 12.0
uuid: 6ff72bda-d1e2-4ca7-bc49-d1c6d2e220ce
parents:
  - refid: fmn3-pr-webhost
    type: profile
    title: FMN Spiral 3 Web Hosting Profile
---
