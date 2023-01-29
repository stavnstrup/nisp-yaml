---
element: Standard
complete: true
nispid: ogc-georss-schema-gml-1.1
url: /standard/ogc-georss-schema-gml-1.1.html
nisptag: "GeoRSS Schema 1.1"
orgid: ogc
document:
  org: ogc
  pubnum: "GeoRSS Schema 1.1"
  title: "GML application schema for the Simple and GML serializations of GeoRSS"
  date: "2006-12"
  version: ""
applicability: >2
    The Simple serialization of GeoRSS is designed to be maximally concise, in both representation and conception. Each of the four GeoRSS objects require only a single tag.

    This simplicity comes at the cost of direct upward compatibility with GML. However, it is straightforward to devise transformations from this Simple serialization to the GML serialization through the GML model. For many needs, GeoRSS Simple will be sufficient.

    Some publishers and users may prefer to seperate lat/long pairs by a comma rather than whitespace. This is permissible in Simple; GeoRSS parsers should just treat commas as whitespace.

    The first example shows GeoRSS Simple within an Atom 1.0 entry. This serialization applies just as well to an RSS 2.0 or RSS 1.0 item; it can also be associated with the entire feed. The rest of the examples show only the encoding of the objects and attributes.

  
rp: fmn-cpwg
status:
  uri: https://schemas.opengis.net/georss/1.0/schema-1.1/georss.xsd
  history: 
    - flag: added
      date: 2019-12-12
      rfcp: 12-025
      version: 13.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: d79fb626-43f9-46ab-8a42-5fb32248cd44
coverdocument:
consumers:
  - fmn4-20211022-prf-47
  - fmn5-20221202-prf-47
---
