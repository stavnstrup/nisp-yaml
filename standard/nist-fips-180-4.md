---
element: Standard
complete: true
nispid: nist-fips-180-4
url: /standard/nist-fips-180-4.html
nisptag: "NIST FIPS PUB 180-4"
orgid: nist
document:
  org: nist
  pubnum: "FIPS PUB 180-4"
  title: "Secure Hash Standard (SHS)"
  date: "2015-08-04"
  version: ""
applicability: >2
  This Standard specifies a Secure Hash Algorithm, SHA-1, for computing a condensed representation of a message or a data file. When a message of any length < 2**64 bits is input, the SHA-1 produces a 160-bit output called a message digest. The message digest can then be input to the Digital Signature Algorithm (DSA) which generates or verifies the signature for the message. Signing the message digest rather than the message often improves the efficiency of the process because the message digest is usually much smaller in size than the message. The same hash algorithm must be used by the verifier of a digital signature as was used by the creator of the digital signature.
rp: c3b-cap4
status:
  uri: http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf
  history: 
    - flag: added
      date: 2016-12-13
      rfcp: 9-12
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 3283a496-0035-4332-a34c-610d5a407cdb
coverdocument:
consumers:
  - fmn3-cryptographic-algorithms-profile
  - fmn4-20211022-prf-10
  - fmn5-20221202-prf-10
---
