---
element: Serviceprofile
nispid: fmn3-web-feeds-profile
url: /serviceprofile/fmn3-web-feeds-profile.html
sptype: coi
title: FMN Spiral 3.0 Web Feeds Service Profile
profilespec:
  org: fmn
  pubnum: 
  title: FMN Spiral 3 Standards Profile
  date: 2018-10-26
  version: 3
description: The Web Feeds Profile provides standards and guidance for the delivery of content to feed aggregators (web sites as well as directly to user agents).
taxonomy:
  - T-06d559b4-1bdf-40cc-904f-4e745a170f24-X
refgroup:
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: ietf-rfc4287
    - refid: ietf-rfc5023
    - refid: rss-2.0
    description: Web content providers must support at least one of the two standards (RSS and/or Atom).
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: ietf-rfc4287
    - refid: ietf-rfc5023
    - refid: rss-2.0
    description: Receivers of web content such as news aggregators or user agents must support both the RSS and the ATOM standard.
status:
  uri: 
  history: 
    - flag: added
      date: 2018-11-26
      rfcp: 11-57
      version: 12.0
uuid: 0624f61f-db54-4d34-b7ae-d9f5bb4775c0
parents:
  - refid: fmn3-pr-webhost
    type: profile
    title: FMN Spiral 3 Web Hosting Profile
---
