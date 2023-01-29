---
element: Standard
complete: true
nispid: itu-t-g.729
url: /standard/itu-t-g.729.html
nisptag: "ITU-T G.729"
orgid: itu-t
document:
  org: itu-t
  pubnum: "G.729"
  title: "Coding of speech at 8 kbit/s using conjugate-structure algebraic-code-excited linear prediction (CS-ACELP)"
  date: "2012-06-29"
  version: ""
applicability: >2
  Rec. ITU-T G.729 contains the description of an algorithm for the coding of speech signals at 8 kbit/s using Conjugate-Structure Algebraic-Code-Excited Linear-Prediction (CS-ACELP). This coder is designed to operate with a digital signal obtained by first performing telephone bandwidth filtering (Rec. ITU-T G.712) of the analogue input signal, then sampling it at 8000 Hz, followed by conversion to 16-bit linear PCM for the input to the encoder. The output of the decoder should be converted back to an analogue signal by similar means. Other input/output characteristics, such as those specified by Rec. ITU-T G.711 for 64 kbit/s PCM data, should be converted to 16-bit linear PCM before encoding, or from 16-bit linear PCM to the appropriate format after decoding. The bitstream from the encoder to the decoder is defined within this Recommendation.
rp: fmn-cpwg
status:
  uri: http://www.itu.int/rec/T-REC-G.729/e
  history: 
    - flag: added
      date: 2012-09-02
      rfcp: 6-29
      version: 7.0
    - flag: changed
      date: 2012-11-25
      rfcp: 
      version: 7.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-17
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: d10147a8-9ec9-4a04-ae9b-4960e97b7570
coverdocument:
consumers:
  - bsp-Infrastructure_Services
  - fmn3-audio-based-collaboration-profile
  - fmn3-standalone-voice-services-call-signaling-profile
  - fmn4-20211022-prf-1
  - fmn4-20211022-prf-86
  - fmn5-20221202-prf-1
  - fmn5-20221202-prf-86
---
