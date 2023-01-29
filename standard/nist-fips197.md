---
element: Standard
complete: true
nispid: nist-fips197
url: /standard/nist-fips197.html
nisptag: "NIST FIPS PUB 197"
orgid: nist
document:
  org: nist
  pubnum: "FIPS PUB 197"
  title: "Advanced Encryption Standard (AES)"
  date: "2001-11-26"
  version: ""
applicability: >2
  AES specifies an approved cryptographic algorithm that can be used to protect electronic data. AES is a symmetric block cipher that can encrypt (cipher) and decrypt (decipher) information. The AES algorithm is capable of using cryptographic keys of 128, 192 and 256 bits to encrypt and decrypt data in blocks of 128 bits. PKI components and applications should utilize AES for key wrap functions. It may also be applied to locally stored keys generated by the Root Certification Authority.
rp: fmn-cpwg
status:
  uri: http://csrc.nist.gov/publications/fips/fips197/fips-197.pdf
  history: 
    - flag: added
      date: 2005-07-26
      rfcp: 6-1
      version: 0.7
    - flag: changed
      date: 2005-09-08
      rfcp: 
      version: 0.7
    - flag: changed
      date: 2010-08-10
      rfcp: 
      version: 5.0
    - flag: deleted
      date: 2017-01-26
      rfcp: 9-21
      version: 10.0
    - flag: changed
      date: 2017-05-01
      rfcp: 9-6
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 825261fe-478f-4ac4-9e4f-82c7667201f1
coverdocument:
consumers:
  - fmn3-cryptographic-algorithms-profile
  - fmn4-20211022-prf-10
  - fmn5-20221202-prf-10
---