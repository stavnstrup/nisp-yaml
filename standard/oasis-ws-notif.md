---
element: Standard
complete: true
nispid: oasis-ws-notif
url: /standard/oasis-ws-notif.html
nisptag: "WS-Notif. 1.3"
orgid: oasis
document:
  org: oasis
  pubnum: "ws-notif"
  title: "WS-BaseNotification"
  date: "2006-10-01"
  version: "1.3"
applicability: >2
  WS-Notification is a family of related specifications that define a standard Web services approach to notification using a topic-based publish/subscribe pattern. It includes  standard message exchanges to be implemented by service providers that wish to participate in Notifications, standard message exchanges for a notification broker service provider (allowing publication of messages from entities that are not themselves service providers), operational requirements expected of service providers and requestors that participate in notifications, and an XML model that describes topics. The WS-Notification family of documents includes three normative specifications  WS-BaseNotification, [WS-BrokeredNotification], and [WS-Topics].
rp: ncia-ces
status:
  uri: http://docs.oasis-open.org/wsn/wsn-ws_base_notification-1.3-spec-os.pdf
  history: 
    - flag: added
      date: 2010-09-22
      rfcp: 
      version: 5.0
    - flag: changed
      date: 2017-01-14
      rfcp: 9-19
      version: 10.0
uuid: a28cff2e-4d3c-4bf0-8125-ed81598ddc1f
coverdocument:
consumers:
  - bsp-SOA_Platform_Services
  - sip-notif-cache-notification-cache
  - sip-pubsub-notif-brooker-publishsubscribe-notification-broker-with-subscription-manager
  - sip-pubsub-notif-consumer-publishsubscribe-notification-consumer
  - sip-pubsub-publish-subscribe
  - fmn5-20221202-prf-169
  - fmn5-20221202-prf-170
---
