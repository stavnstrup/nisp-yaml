---
element: Serviceprofile
nispid: fmn3-formatted-messages-intelligence-profile
url: /serviceprofile/fmn3-formatted-messages-intelligence-profile.html
sptype: coi
title: FMN Spiral 3.0 Formatted Messages for Intelligence Profile
profilespec:
  org: fmn
  pubnum: 
  title: FMN Spiral 3 Standards Profile
  date: 2018-10-26
  version: 3
description: The Formatted Messages Profile provides standard for formatted messages that are typically used to exchange Intelligence Products in military operations. These formatted messages may be used as payload/attachment in combination with various transport mechanisms such as informal messaging (e-mail), text collaboration (chat) or for publication as files on websites.
taxonomy:
  - T-e683e3a2-ef50-4da3-b286-2ecf23e21aae-X
  - T-9f408558-029b-4625-ab8a-3dfcdb677800-X
  - T-f6a4c0a6-787d-43c2-bd3e-48eeb41d4827-X
  - T-06d559b4-1bdf-40cc-904f-4e745a170f24-X
refgroup:
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: nato-app-11-ed.d-v2
    description: To support exploitation the following APP-11 message formats MUST be supported (MTF Identifier, MTF Index Ref Number)  Air Intelligence Report (AIRINTREP, F001)Counter-Intelligence and Security Report (CIINTREP, J112)Counter-Intelligence and Security Summary (CIINTSUM, J113)Counter-Intelligence and Security Supplementary Report (CISUPINTREP, J115)Detailed Document Report (DEDOCREP, J089)First Hostile Act Report (First Hostile Act)Intelligence Report (INTREP, J110)Intelligence Summary (INTSUM, J111)Maritime Intelligence Report (MARINTREP, J016)Maritime Intelligence Summary (MARINTSUM, J015)Supplementary Intelligence Report (SUPINTREP, J114)
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: nato-ajp-2.5-ed.a
    description: To support the exchange of Intelligence Products the following AJP-2.5 message formats MUST be supported (MTF Identifier)  Human Intelligence Report (HUMINTREP)Human Intelligence Summary (HUMINTSUM)Interrogation Report (INTGREP)
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: nato-app-11-ed.d-v2
    description: To support the exchange of information needed to govern and facilitate the collection of Intelligence, Surveillance and Reconnaissance (ISR) information and production of intelligence the following message formats defined in APP-11 MUST be supported (MTF Identifier, MTF Index Ref Number)  Intelligence Request (INTREQ, J021)Information Requirement Management & Collection Management Exchange (ICE, J033)
  - obligation: recommended
    lifecycle: current
    standards: 
    description: To support exploitation the following MAJIIC 2 message formats SHOULD be supported Electronic Order of Battle (EOB)Pentagram Report (PentagramREP)MAJIIC 2 Bravo.1
status:
  uri: 
  history: 
    - flag: added
      date: 2018-11-02
      rfcp: 11-57
      version: 12.0
uuid: 9405a58f-f28d-4742-bfd6-c2f41fdc0b08
parents:
  - refid: fmn3-pr-formatted-messages
    type: profile
    title: FMN Spiral 3 Formatted Messages Profile
  - refid: fmn3-pr-intell
    type: profile
    title: FMN Spiral 3 Intelligence Profile
---
