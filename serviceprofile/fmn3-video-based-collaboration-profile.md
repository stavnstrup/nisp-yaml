---
element: Serviceprofile
nispid: fmn3-video-based-collaboration-profile
url: /serviceprofile/fmn3-video-based-collaboration-profile.html
sptype: coi
title: FMN Spiral 3.0 Video-based Collaboration Service Profile
profilespec:
  org: fmn
  pubnum: 
  title: FMN Spiral 3 Standards Profile
  date: 2018-10-26
  version: 3
description: The Video-based Collaboration Profile provides standards and guidance for the implementation and configuration of Video Tele Conferencing (VTC) systems and services in a federated mission network.
taxonomy:
  - T-53151cf1-2071-4aa5-a73a-07bb4dc5de9c-X
refgroup:
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: itu-t-g.722.1-corr1-06.08
    - refid: itu-t-g.711
    description: The following standards are required for audio coding in VTC.
  - obligation: mandatory
    lifecycle: current
    standards: 
    - refid: itu-t-h.264
    - refid: ietf-rfc6184
    description: The following standards are required for video coding in VTC.
  - obligation: conditional
    lifecycle: current
    standards: 
    - refid: ietf-rfc4582
    description: Not required at this time, but when available it can be implemented between dedicated network segments after approval from the MN administrative authority.
status:
  uri: 
  history: 
    - flag: added
      date: 2018-11-27
      rfcp: 11-57
      version: 12.0
uuid: 8dc0b976-0901-41fc-84fb-f046805b5e08
parents:
  - refid: fmn3-pr-video-based-collab
    type: profile
    title: FMN Spiral 3 Video-based Collaboration Profile
---
