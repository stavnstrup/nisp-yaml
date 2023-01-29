---
element: Standard
complete: true
nispid: iso-iec-10021
url: /standard/iso-iec-10021.html
nisptag: "ISO 10021:1999"
orgid: iso-iec
document:
  org: iso-iec
  pubnum: "10021"
  title: "Message Handling Systems (MHS)"
  date: "1999"
  version: ""
applicability: >2
  The ISO/ITU-T X.400 Message Handling Systems (MHS) is a suite of protocols that define a standard for store-and-forward messaging. X.400 provides message creation, routing, and delivery services. X.400 divides an electronic mail system into a client, called a User Agent (UA) in ISO parlance, and a server, called a Message Transfer Agent (MTA). Essentially, the User Agent is a mail box; it interfaces directly with the user. It is responsible for message preparation, submission, and reception for the user. It also provides text editing, presentation services, security, message priority, and delivery notification. The User Agent is an interface, not an end-user application, so it does not define the specifics of how it interacts with the user. The product developer decides those issues.The Message Transfer Agent routes and relays the messages. Its responsibilities include establishing the store-and-forward path, ensuring channel security, and routing the message through the media. An MTA's operation is relatively straightforward. The User Agent sends its message to the local Message Transfer Agent. The MTA checks the message for syntax errors, then delivers the message to a local User Agent, or if the message is not local, it forwards it to the next MTA. That MTA repeats the process until the message is successfully delivered. A collection of MTAs is known as Message Transfer System (MTS). The MTS is usually specialized to a particular vendor's product.X.400 also uses Distribution Lists (DLs), which are like routing lists commonly used in offices. The Message Store (MS) provides a facility for message storage, submission, and retrieval. It complements the User Agent for devices that are not always available, such as PCs or terminals. Essentially, it is a database of messages.The Access Units (AUs) provide connections to other types of communications systems, such as telex and postal services. AUs defined in the 1988 spec are the Telematic Agent for Teletex terminals, Telex Agent for Telex service, and Physical Delivery Agent for connection to the traditional postal service.
rp: ncia-ces
status:
  uri: http://www.iso.org/iso/iso_catalogue/catalogue_tc/catalogue_detail.htm?csnumber=31632
  history: 
    - flag: added
      date: 1997-10-07
      rfcp: 
      version: 0.1
    - flag: changed
      date: 2000-03-17
      rfcp: 
      version: 0.2
    - flag: changed
      date: 2002-10-11
      rfcp: 
      version: 0.4
    - flag: changed
      date: 2005-09-15
      rfcp: 
      version: 0.7
    - flag: changed
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: c37b3239-741e-4aea-8293-9cc6c34c994a
coverdocument:
consumers:
---
