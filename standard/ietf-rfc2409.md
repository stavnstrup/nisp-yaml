---
element: Standard
complete: true
nispid: ietf-rfc2409
url: /standard/ietf-rfc2409.html
nisptag: "IETF RFC 2409"
orgid: ietf
document:
  org: ietf
  pubnum: "RFC 2409"
  title: "The Internet Key Exchange (IKE)"
  date: "1998-11"
  version: ""
applicability: >2
  IPsec is designed to provide interoperable, high quality, cryptographically-based security for IPv4 and IPv6. The set of security services offered includes access control, connectionless integrity, data origin authentication, protection against replays (a form of partial sequence integrity), confidentiality (encryption), and limited traffic flow confidentiality. These services are provided at the IP layer, offering protection for IP and/or upper layer protocols. These objectives are met through the use of two traffic security protocols, the Authentication Header (AH) and the Encapsulating Security Payload (ESP), and through the use of cryptographic key management procedures and protocols. The set of IPsec protocols employed in any context, and the ways in which they are employed, will be determined by the security and system requirements of users, applications, and/or sites/organizations.  IPsec provides security services at the IP layer by enabling a system to select required security protocols, determine the algorithm(s) to use for the service(s), and put in place any cryptographic keys required to provide the requested services. IPsec can be used to protect one or more paths between a pair of hosts, between a pair of security gateways, or between a security gateway and a host.

    A basic and mandatory element of IPSec is the usage of Security Associations. A Security Association (SA) is a simplex connection that affords security services to the traffic carried by it. Security services are afforded to an SA by the use of AH, or ESP, but not both. If both AH and ESP protection is applied to a traffic stream, then two (or more) SAs are created to afford protection to the traffic stream. To secure typical, bi-directional communication between two hosts, or between two security gateways, two Security Associations (one in each direction) are required.

    The key management protocol must be robust in order to handle public key generation for the Internet community at large and private key requirements for those private networks with that requirement. The Internet Security Association and Key Management Protocol (ISAKMP) defines the procedures for authenticating a communicating peer, creation and management of Security Associations, key generation techniques, and threat mitigation (e.g. denial of service and replay attacks). All of these are necessary to establish and maintain secure communications (via IP Security Service or any other security protocol) in an Internet environment.

  
rp: fmn-cpwg
status:
  uri: https://www.ietf.org/rfc/rfc2409.txt
  history: 
    - flag: added
      date: 1999-01-15
      rfcp: 
      version: 0.1
    - flag: changed
      date: 2000-07-17
      rfcp: 
      version: 0.2
    - flag: changed
      date: 2005-09-23
      rfcp: 
      version: 0.7
    - flag: deleted
      date: 2010-10-30
      rfcp: 
      version: 5.0
    - flag: changed
      date: 2015-10-29
      rfcp: 8-5
      version: 9.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-17
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 51461039-3c2f-4086-adb1-1bf2a817e5f1
coverdocument:
consumers:
---
