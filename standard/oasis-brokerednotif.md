---
element: Standard
complete: true
nispid: oasis-brokerednotif
url: /standard/oasis-brokerednotif.html
nisptag: "WS-BrokeredNotification"
orgid: oasis
document:
  org: oasis
  pubnum: "WS-BrokeredNotification"
  title: "Web Services Brokered Notification Ver 1.3"
  date: "2006-10-01"
  version: "1.3"
applicability: >2
  The Event-driven, or Notification-based, interaction pattern is a commonly used pattern for inter-object communications. Examples exist in many domains, for example in publish/subscribe systems provided by Message Oriented Middleware vendors, or in system and device management domains. This notification pattern is increasingly being used in a Web services context.  WS-Notification is a family of related specifications that define a standard Web services approach to notification using a topic-based publish/subscribe pattern. It includes  standard message exchanges to be implemented by service providers that wish to participate in Notifications, standard message exchanges for a notification broker service provider (allowing publication of messages from entities that are not themselves service providers), operational requirements expected of service providers and requestors that participate in notifications, and an XML model that describes topics. The WS-Notification family of documents includes three normative specifications  WS-BaseNotification, WS-BrokeredNotification, and WS-Topics.

  
rp: ncia-ces
status:
  uri: http://docs.oasis-open.org/wsn/wsn-ws_brokered_notification-1.3-spec-os.pdf
  history: 
    - flag: added
      date: 2013-07-28
      rfcp: 7-27
      version: 8.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
    - flag: changed
      date: 2022-12-20
      rfcp: 14-62
      version: 15.0
uuid: 4effdd0f-fd3e-4898-9b36-8165ed9741b3
coverdocument:
consumers:
  - bsp-SOA_Platform_Services
  - sip-notif-cache-notification-cache
  - sip-pubsub-notif-brooker-publishsubscribe-notification-broker-with-subscription-manager
  - sip-pubsub-publish-subscribe
  - fmn5-20221202-prf-170
---
