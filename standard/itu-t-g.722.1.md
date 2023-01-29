---
element: Standard
complete: true
nispid: itu-t-g.722.1
url: /standard/itu-t-g.722.1.html
nisptag: "ITU-T G.722.1"
orgid: itu-t
document:
  org: itu-t
  pubnum: "G.722.1"
  title: "Low-complexity coding at 24 and 32 kbit/s for hands-free operation in systems with low frame loss"
  date: "2005-05-14"
  version: ""
applicability: >2
    This Recommendation describes a digital wideband coder algorithm that provides an audio bandwidth of 50 Hz to 7 kHz, operating at a bit rate of 24 kbit/s or 32 kbit/s. The digital input to the coder may be 14-, 15- or 16-bit 2's complement format at a sample rate of 16 kHz (handled in the same way as in ITU-T Rec. G.722). The analogue and digital interface circuitry at the encoder input and decoder output should conform to the same specifications described in ITU-T Rec. G.722.

    The algorithm is based on transform technology, using a Modulated Lapped Transform (MLT). It operates on 20-ms frames (320 samples) of audio. Because the transform window (basis function length) is 640 samples and a 50 per cent (320 samples) overlap is used between frames, the effective look-ahead buffer size is 20 ms. Hence the total algorithmic delay of 40 ms is the sum of the frame size plus look-ahead. All other delays are due to computational and network transmission delays.

  
rp: fmn-cpwg
status:
  uri: http://www.itu.int/rec/T-REC-G.722.1
  history: 
    - flag: added
      date: 2021-01-15
      rfcp: 13-019
      version: 14.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 0594d2f0-b5fd-48f2-a3d0-96c62a05d2df
coverdocument:
consumers:
  - fmn4-20211022-prf-1
  - fmn4-20211022-prf-85
  - fmn4-20211022-prf-86
  - fmn4-20211022-prf-94
  - fmn5-20221202-prf-94
  - fmn5-20221202-prf-1
  - fmn5-20221202-prf-85
  - fmn5-20221202-prf-86
---
