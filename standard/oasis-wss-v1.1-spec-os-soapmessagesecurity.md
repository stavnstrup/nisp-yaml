---
element: Standard
complete: true
nispid: oasis-wss-v1.1-spec-os-soapmessagesecurity
url: /standard/oasis-wss-v1.1-spec-os-soapmessagesecurity.html
nisptag: "WSS"
orgid: oasis
document:
  org: oasis
  pubnum: "wss-v1.1-spec-os-SOAPMessageSecurity"
  title: "Web Services Security: SOAP Message Security 1.1"
  date: "2006-02-01"
  version: "1.1"
applicability: >2
  WS-Security describes enhancements to SOAP messaging to provide quality of protection through message integrity, message confidentiality, and single message authentication. These mechanisms can be used to accommodate a wide variety of security models and encryption technologies.  WS-Security also provides a general-purpose mechanism for associating security tokens with messages. No specific type of security token is required by WS-Security. It is designed to be extensible (e.g. support multiple security token formats). For example, a client might provide proof of identity and proof that they have a particular business certification.

    Additionally, WS-Security describes how to encode binary security tokens. Specifically, the specification describes how to encode X.509 certificates and Kerberos tickets as well as how to include opaque encrypted keys. It also includes extensibility mechanisms that can be used to further describe the characteristics of the credentials that are included with a message.

  
rp: ncia-ces
status:
  uri: http://docs.oasis-open.org/wss/v1.1
  history: 
    - flag: added
      date: 2004-05-25
      rfcp: 5-19
      version: 0.6
    - flag: changed
      date: 2012-09-04
      rfcp: 6-60
      version: 7.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
uuid: d8dab608-97ad-4fc7-b387-cbef9ac49fbe
coverdocument:
consumers:
  - binding-crypto-cryptographic-artefact-binding
  - bsp-Message-Oriented_Middleware_Services
  - sip-policy-enforce-policy-enforcement-points
  - sip-token-security-token
  - fmn5-20221202-prf-138
  - fmn5-20221202-prf-143
---
