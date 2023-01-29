---
element: Serviceprofile
nispid: fmn3-geospatial-web-feeds-profile
url: /serviceprofile/fmn3-geospatial-web-feeds-profile.html
sptype: coi
title: FMN Spiral 3.0 Geospatial Web Feeds Service Profile
profilespec:
  org: fmn
  pubnum: 
  title: FMN Spiral 3 Standards Profile
  date: 2018-10-26
  version: 3
description: The Geospatial Web Feeds Profile provides standards and guidance for the delivery of geospatial content to web sites and to user agents, including the encoding of location as part of web feeds. Feed processing software is required to either read or ignore these extensions and shall not fail if these extensions are present, so there is no danger of breaking someone's feed reader (or publisher) by including this element in a feed.
taxonomy:
  - T-06d559b4-1bdf-40cc-904f-4e745a170f24-X
refgroup:
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: ogc-11-044
    description: GeoRSS Simple encoding for "georss point", "georss line", "georss polygon", "georss box".
  - obligation: recommended
    lifecycle: current
    standards: 
    - refid: ogc-06-050r3
    description: GeoRSS GML Profile 1.0 a GML subset for point "gml Point", line "gml LineString", polygon "gml Polygon", and box "gml Envelope". In Atom feeds, location shall be specified using Atom 1.0's official extension mechanism in combination with the GeoRSS GML Profile 1.0 whereby a "georss where" element is added as a child of the element.
status:
  uri: 
  history: 
    - flag: added
      date: 2018-11-26
      rfcp: 11-57
      version: 12.0
uuid: 3bc3d5e6-fbc4-4a5a-bd62-d49c1c4f4f96
parents:
  - refid: fmn3-pr-geospatial
    type: profile
    title: FMN Spiral 3 Geospatial Profile
---
