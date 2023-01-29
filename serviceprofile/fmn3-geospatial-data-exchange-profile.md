---
element: Serviceprofile
nispid: fmn3-geospatial-data-exchange-profile
url: /serviceprofile/fmn3-geospatial-data-exchange-profile.html
sptype: coi
title: FMN Spiral 3.0 Geospatial Data Exchange Service Profile
profilespec:
  org: fmn
  pubnum: 
  title: FMN Spiral 3 Standards Profile
  date: 2018-10-26
  version: 3
description: Geospatial data are being produced by different organisations and need to be exchanged between different participants using standardized exchange formats. These datasets would then be loaded into specialised geospatial information systems (GIS) and published via standardized Web Services (e.g. WMS or WMTS for raster data/maps).
taxonomy:
  - T-54a19444-8cd5-4766-9140-6cdc53aafb79-X
refgroup:
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: ogc-07-147r2
    description: File based storage and exchange of digital geospatial vector data 
  - obligation: recommended
    lifecycle: current
    standards: 
    - refid: ogc-12-128r12
    description: File geodatabases store geospatial datasets and can hold any number of these large, individual datasets. File geodatabases can be used across multiple platforms. Users are rapidly adopting file geodatabases in place of using legacy shapefiles.
  - obligation: recommended
    lifecycle: current
    standards: 
    - refid: nga-mil-prf-89038
    - refid: nga-rpf
    - refid: iso-iec-15444-1
    description: File exchange of xdigital raster data 
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: osgeo-geotiff
    - refid: ogc-05-047r3
    description: File based storage and exchange of digital geospatial mapping (raster) data.
status:
  uri: 
  history: 
    - flag: added
      date: 2018-11-26
      rfcp: 11-57
      version: 12.0
uuid: 04b0d3b5-1244-4ec7-ae75-11af96966fe3
parents:
  - refid: fmn3-pr-geospatial
    type: profile
    title: FMN Spiral 3 Geospatial Profile
---
