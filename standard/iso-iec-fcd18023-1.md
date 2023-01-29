---
element: Standard
complete: true
nispid: iso-iec-fcd18023-1
url: /standard/iso-iec-fcd18023-1.html
nisptag: "ISO FCD 18023-1:2006"
orgid: iso-iec
document:
  org: iso-iec
  pubnum: "FCD 18023-1"
  title: "SEDRIS functional specification"
  date: "2006-05"
  version: ""
applicability: >2
  This part of ISO/IEC 18023 defines the semantics and structure used to represent environmental data along with the means to produce and access that data. This latter aspect is termed a transmittal which is the realization of an environment using the SEDRIS data representation model (DRM). The SEDRIS DRM is a mechanism that may be access through the application program interface (API) provided in this part of ISO/IEC 18023. An inherent aspect of SEDRIS is the ability to express information about a wide range of natural, man-made, or virtual environmental objects and their characteristics. These can include such things as celestial bodies, rivers, forests, wind, ocean characteristics, atmospheric temperature, avatars, ships, roads, space stations, buildings, and animals. The emphasis is placed on representing the characteristics of such objects while specifying the interrelationships among them.  ISO/IEC 18023 in its entirety specifies a Data Representation Model (DRM), an abstract transmittal format (ATF), the SEDRIS transmittal format binary encoding (STF), and an application program interface (API) that supports both the DRM and the transmittal formats in creating and accessing SEDRIS transmittals as components of a data interchange mechanism for environmental representations. Other components of the SEDRIS interchange mechanism required to completely and unambiguously describe environmental data are described in two other international standards. These International Standards are the ISO/IEC 18025 Environmental data coding specification (EDCS) and the ISO/IEC 18026 Spatial reference model (SRM).

    The SEDRIS interchange mechanism uses the DRM, in conjunction with the EDCS and the SRM, to provide a means for defining all of the data elements and their relationships necessary to create an environmental database. These components form the central core of successful data interchange. They allow the unambiguous description of environmental data. The DRM, through the registration process described in this part of ISO/IEC 18023, can be expanded to incorporate future environmental representation needs.

    The SEDRIS API is the interchange mechanism component that provides the means to create and access data in a SEDRIS transmittal. It allows data producing or consuming applications to interchange environmental data between different proprietary database systems or formats. The API provides a coherent and complete interface to the data in a SEDRIS transmittal. The API allows the underlying implementation of the SEDRIS transmittal format to be transparent to users.

  
rp: ncia-jisr
status:
  uri: http://www.iso.org/iso/iso_catalogue/catalogue_tc/catalogue_detail.htm?csnumber=38442
  history: 
    - flag: added
      date: 2003-03-19
      rfcp: 
      version: 0.5
    - flag: changed
      date: 2005-09-15
      rfcp: 
      version: 0.7
    - flag: changed
      date: 2007-08-03
      rfcp: 
      version: 2.0
    - flag: changed
      date: 2012-11-29
      rfcp: 
      version: 7.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: b5af3a56-fc2a-4bda-939c-3e20f515e14c
coverdocument:
consumers:
  - bsp-Modeling_and_Simulation_Services
---
