---
element: Standard
complete: true
nispid: ecma-368
url: /standard/ecma-368.html
nisptag: "ECMA-368"
orgid: ecma
document:
  org: ecma
  pubnum: "ECMA-368"
  title: "High Rate Ultra-Wide Band PHY and MAC Standard"
  date: "2008-12"
  version: ""
applicability: >2
  Ultra-Wideband (UWB) is a technology for transmitting information spread over a large bandwidth (>500 MHz) that should, in theory and under the right circumstances, be able to share spectrum with other users.  One of the valuable aspects of UWB radio technology is the ability for a UWB radio system to determine 'time of flight' of the direct path of the radio transmission between the transmitter and receiver to a high resolution. With a two-way time transfer technique distances can be measured to high resolution as well as to high accuracy by compensating for local clock drifts and inaccuracies.

    Another valuable aspect of pulse-based UWB is that the pulses are very short in space (less than 60 cm for a 500 MHz wide pulse, less than 23 cm for a 1.3 GHz bandwidth pulse), so most signal reflections do not overlap the original pulse, and thus the traditional multi-path fading of narrow band signals does not exist. However, there still is inter-pulse interference for fast pulse systems which can be mitigated by coding techniques.

  
rp: ncia-nsii
status:
  uri: http://www.ecma-international.org/publications/files/ECMA-ST/ECMA-368.pdf
  history: 
    - flag: added
      date: 2007-02-23
      rfcp: 
      version: 1.0
    - flag: changed
      date: 2012-11-05
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
uuid: d4a74c5a-a1d4-4445-b127-df0173d312cc
coverdocument:
consumers:
  - bsp-Communications_Services
---
