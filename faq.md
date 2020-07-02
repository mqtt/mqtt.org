---
layout: default
title: FAQ
permalink: /faq
---

# What is MQTT?
MQTT is an OASIS standard for IoT connectivity. 
It is a publish/subscribe, extremely simple and lightweight messaging protocol, designed for constrained devices and low-bandwidth, high-latency or unreliable networks. 
The design principles are to minimise network bandwidth and device resource requirements whilst also attempting to ensure reliability and some degree of assurance of delivery. 
These principles also turn out to make the protocol ideal of the “Internet of Things” world of connected devices, and for mobile applications where bandwidth and battery power are at a premium.

## Who invented MQTT?
MQTT was invented by Dr Andy Stanford-Clark of IBM, and Arlen Nipper of Arcom (now Eurotech), in 1999.

## Where is MQTT in use?
MQTT has been widely implemented across a variety of industries since 1999. A few of the more interesting examples are listed on the Use Case page.

## Is MQTT a standard?
v5.0 and v3.1.1 are now OASIS standards (v3.1.1 has also been ratified by ISO).

## Are there standard ports for MQTT to use?
Yes. TCP/IP port 1883 is reserved with IANA for use with MQTT. TCP/IP port 8883 is also registered, for using MQTT over SSL.

## Does MQTT support security?
You can pass a user name and password with an MQTT packet in V3.1 of the protocol. Encryption across the network can be handled with SSL, independently of the MQTT protocol itself (it is worth noting that SSL is not the lightest of protocols, and does add significant network overhead). 
Additional security can be added by an application encrypting data that it sends and receives, but this is not something built-in to the protocol, in order to keep it simple and lightweight.

## Where can I find out more?
The specification and other documentation are available via the Specification page. 
Ask questions via one of the methods on StackOverflow. 
Try code via one of the projects on the Software page.