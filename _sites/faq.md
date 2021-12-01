---
title: FAQ
index: 5
description: Frequently asked questions about MQTT and a dictionary of terms and acronyms.
---

<section class="content-floating">
<h1>FAQ</h1>
<div class="accordion-wrapper" style="margin-bottom: 50px;">
   <button class="accordion">What is MQTT?</button>
   <div class="panel">
      <p>MQTT is an OASIS standard for IoT connectivity. It is a publish/subscribe, extremely simple and lightweight messaging protocol, designed for constrained devices and low-bandwidth, high-latency or unreliable networks. The design principles are to minimise network bandwidth and device resource requirements whilst also attempting to ensure reliability and some degree of assurance of delivery. These principles also turn out to make the protocol ideal of the “Internet of Things” world of connected devices, and for mobile applications where bandwidth and battery power are at a premium.</p>
   </div>
   <button class="accordion">Who invented MQTT?</button>
   <div class="panel">
      <p>MQTT was invented by Dr Andy Stanford-Clark of IBM, and Arlen Nipper of Arcom (now Eurotech), in 1999.</p>
   </div>
   <button class="accordion">Where is MQTT in use?</button>
   <div class="panel">
      <p>MQTT has been widely implemented across a variety of industries since 1999. A few of the more interesting examples are listed on the <a href="/use-cases" alt="Use Cases" title="Use Cases">Use Case page.</a></p>
   </div>
   <button class="accordion">Is MQTT a standard?</button>
   <div class="panel">
      <p>v5.0 and v3.1.1 are now OASIS standards (v3.1.1 has also been ratified by ISO).</p>
   </div>
   <button class="accordion">Are there standard ports for MQTT to use?</button>
   <div class="panel">
      <p>Yes. TCP/IP port 1883 is reserved with IANA for use with MQTT. TCP/IP port 8883 is also registered, for using MQTT over SSL.</p>
   </div>
   <button class="accordion">Does MQTT support security?</button>
   <div class="panel">
      <p>You can pass a user name and password with an MQTT packet in V3.1 of the protocol. Encryption across the network can be handled with SSL, independently of the MQTT protocol itself (it is worth noting that SSL is not the lightest of protocols, and does add significant network overhead). Additional security can be added by an application encrypting data that it sends and receives, but this is not something built-in to the protocol, in order to keep it simple and lightweight.</p>
   </div>
   <button class="accordion">Where can I find out more?</button>
   <div class="panel">
      <p>The specification and other documentation are available via the <a href="{{ '/mqtt-specification' | relative_url }}">Specification page</a>. Ask questions via one of the methods on StackOverflow. Try code via one of the projects on the <a href="{{ '/software' | relative_url }}">Software page.</a></p>
   </div>
</div>

<h1>Terms and acronyms</h1>
<div class="accordion-wrapper" style="margin-bottom: 50px;">
   <button class="accordion">Broker</button>
   <div class="panel">
      <p>A <a href="http://en.wikipedia.org/wiki/Message_broker">broker</a> is a server that routes published messages to subscribers.</p>
   </div>
   <button class="accordion">Bridge</button>
   <div class="panel">
      <p>A connection between two MQTT brokers</p>
   </div>
   <button class="accordion">RSMB</button>
   <div class="panel">
      <p>Really Small Message Broker from IBM, now part of the Eclipse Mosquitto project</p>
   </div>
   <button class="accordion">LWT</button>
   <div class="panel">
      <p><a href="https://www.hivemq.com/blog/mqtt-essentials-part-9-last-will-and-testament/">Last Will and Testament.</a></p>
   </div>
   <button class="accordion">M2M</button>
   <div class="panel">
      <p><a href="http://en.wikipedia.org/wiki/Machine-to-Machine" rel="nofollow">Machine-to-Machine</a></p>
   </div>
   <button class="accordion">M2M IWG</button>
   <div class="panel">
      <p><a href="https://blogs.eclipse.org/post/ian-skerrett/m2m-industry-working-group-has-been-created">Machine-to-Machine Industry Working Group</a> at Eclipse</p>
   </div>
   <button class="accordion">IoT</button>
   <div class="panel">
      <p><a href="http://en.wikipedia.org/wiki/Internet_of_things" rel="nofollow">Internet of Things</a></p>
   </div>
   <button class="accordion">Paho</button>
   <div class="panel">
      <p>Eclipse Paho messaging project.</p>
   </div>
   <button class="accordion">QoS</button>
   <div class="panel">
      <p><a href="https://www.hivemq.com/blog/mqtt-essentials-part-6-mqtt-quality-of-service-levels/">Quality of Service</a> levels</p>
   </div>
</div>
</section>

{% include accordion-js.html %}
