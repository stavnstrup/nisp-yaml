---
element: Standard
complete: true
nispid: eia-rs-232
url: /standard/eia-rs-232.html
nisptag: "RS-232"
orgid: eia
document:
  org: eia
  pubnum: "TIA-232 (RS-232)"
  title: "Interface Between Data Terminal Equipment and Data Communications Equipment Employing Serial Binary Data Interchange (identical with ITU-T V.24/V.28:1991)"
  date: "2012-07-12"
  version: ""
applicability: >2
  RS-232 has been around as a standard for decades is an electrical interface between Data Terminal Equipment (DTE) and Data Circuit-Terminating Equipment (DCE) such as modems or DSUs. It appears under different incarnations such as RS-232C, RS-232D, V.24, V.28 or V.10 but essentially all these interfaces are interoperable. RS-232 is used for asynchronous data transfer as well as synchronous links such as SDLC, HDLC, Frame Relay and X.25.  In its simplest form, the RS-232-C interface consist of only two wires-one to carry data, plus a circuit common. The circuit common is the absolute voltage reference for all the interface circuitry, the point in the circuit from which all voltages are measured.

    A typical DTE device is an ordinary video terminal with a keyboard and a video display. Data on pin 2 of the DTE is transmitted, while the same data on pin 2 of a DCE (modem) is received data.

  
rp: ncia-nsii
status:
  uri: http://www.itu.int/rec/T-REC-V.24-200002-I/en
  history: 
    - flag: added
      date: 2001-11-20
      rfcp: 
      version: 0.3
    - flag: changed
      date: 2005-09-23
      rfcp: 
      version: 0.7
    - flag: changed
      date: 2010-08-09
      rfcp: 
      version: 5.0
    - flag: changed
      date: 2013-08-12
      rfcp: 
      version: 8.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 5c34f01d-85f3-41be-82a3-0cc969307b0a
coverdocument:
consumers:
---
