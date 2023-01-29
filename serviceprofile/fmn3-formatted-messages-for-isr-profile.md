---
element: Serviceprofile
nispid: fmn3-formatted-messages-for-isr-profile
url: /serviceprofile/fmn3-formatted-messages-for-isr-profile.html
sptype: coi
title: FMN Spiral 3.0 Formatted Messages for ISR Profile
profilespec:
  org: fmn
  pubnum: 
  title: FMN Spiral 3 Standards Profile
  date: 2018-10-26
  version: 3
description: The Formatted Messages Profile provides standard for formatted messages that are typically used to exchange Intelligence, Surveillance, and Reconnaissance (ISR) products in military operations. These formatted messages may be used as payload/attachment in combination with various transport mechanisms such as informal messaging (e-mail), text collaboration (chat) or for publication as files on websites. In addition, some of these formatted messages are also supported by federated ISR Libraries.
taxonomy:
  - T-e683e3a2-ef50-4da3-b286-2ecf23e21aae-X
  - T-9f408558-029b-4625-ab8a-3dfcdb677800-X
  - T-f6a4c0a6-787d-43c2-bd3e-48eeb41d4827-X
  - T-06d559b4-1bdf-40cc-904f-4e745a170f24-X
  - T-da4a7c62-0dd4-4b5b-a4cc-8b2a84a737ae-X
refgroup:
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: nato-app-11-ed.d-v2
    description: To support the exchange of information needed to govern and facilitate the collection of Intelligence, Surveillance and Reconnaissance (ISR) information and production of intelligence the following message formats defined in APP-11 MUST be supported (MTF Identifier, MTF Index Ref Number)  Intelligence Request (INTREQ, J021)Information Requirement Management & Collection Management Exchange (ICE, J033)Information Requirement Management & Collection Management Exchange (ICE, J033)
  - obligation: recommended
    lifecycle: current
    standards: 
    description: The following XML Schema defined by MAJIIC 2 SHOULD be supported  ISR Spot Report (ISRSPOTREP) This report is to be used for quick reporting allowing a free-text description of the results. MAJIIC 2 Bravo.1
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: nato-aedp-12-ed.a-v1
    - refid: nato-aedp-16
    - refid: nato-aedp-04-ed.2-v1
    - refid: nato-aedp-07-ed.2-v1
    - refid: nato-nnstd-misp-2015.1
    description: To support the sharing of JISR Products the following message formats defined in various AEDPs MUST be supported  ISR TrackMeasurement and Signature Intelligence Report (MASINTREP)ImageryGround Moving Target Indicator (GMTI)Motion Imagery Corrigendum to FMN Spiral 3 Standard Profile  AEDP-08 Ed. 3 has been replaced by NNSTD MISP-2015.1 with STANAG 4609 Ed 4.
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: nato-app-11-ed.d-v2
    - refid: nato-stanag3377ed6
    description: To support the sharing of JISR Products the following message formats defined in APP-11 and STANAG 3377 MUST be supported (MTF Identifier, MTF Index Ref Number)  Target Track Report (TRACKREP, J071)Mission Report (MISREP, F031)Inflight Report (INFLIGHTREP, J009)
status:
  uri: 
  history: 
    - flag: added
      date: 2018-11-02
      rfcp: 11-57
      version: 12.0
uuid: 68368c87-fdef-4f61-92c2-2c77c0c674ee
parents:
  - refid: fmn3-pr-formatted-messages
    type: profile
    title: FMN Spiral 3 Formatted Messages Profile
  - refid: fmn3-pr-intell
    type: profile
    title: FMN Spiral 3 Intelligence Profile
---
