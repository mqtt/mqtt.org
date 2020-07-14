---
layout: home
title: MQTT - The Standard for IoT Messaging 
permalink: /
---

<div class="width-container">
   <h2>Why MQTT?</h2> 
   <section id="keyfeature-list">
   <div class="keyfeature">
      <h3>Lightweight and Efficient</h3>
      <p>MQTT clients are very small, require minimal resources so can be used on small microcontrollers. MQTT message headers are small to optimize network bandwidth.
      </p>
   </div>
   <div class="keyfeature mid">
      <h3>Bi-directional Communications</h3>
      <p>MQTT allows for messaging between device to cloud and cloud to device. This makes for easy broadcasting messages to groups of things.
      </p>
   </div>
   <div class="keyfeature last">
      <h3>Scale to Millions of Things</h3>
      <p>MQTT can scale to connect with millions of IoT devices.
      </p>
   </div>
   <div class="keyfeature">
      <h3>Reliable Message Delivery</h3>
      <p>Reliability of message delivery is important for many IoT use cases. This is why MQTT has 3 defined quality of service levels: 0 - at most once, 1- at least once, 2 - exactly once
      </p>
   </div>
   <div class="keyfeature mid">
      <h3>Support for Unreliable Networks</h3>
      <p>Many IoT devices connect over unreliable cellular networks. MQTT’s support for persistent sessions reduces the time to reconnect the client with the broker.
      </p>
   </div>
   <div class="keyfeature last">
      <h3>Security Enabled<br/>&nbsp;</h3>
      <p>MQTT makes it easy to encrypt messages using TLS and authenticate clients using modern authentication protocols, such as OAuth.
      </p>
   </div>
</section>
<h2>MQTT Publish / Subscribe Architecture</h2> 
   <section id="pub-sub-graphic">
      <img src="{{ 'assets/img/mqtt-publish-subscribe.png' | relative_url }}" alt="MQTT: publish / subscribe architecture" title="MQTT: publish / subscribe architecture">
   </section>
</div>

<section id="mqtt-in-action">
<h2>MQTT in Action</h2>
<p>MQTT is used in a wide variety of industries</p>
   <div class="flex-wrap-centered">
      <a href="{{ '/use-cases#automotive' | relative_url }}"><div class="mqtt-in-action-box" style="background-image: url('{{ 'assets/img/automotive.jpg' | relative_link }}');">Automotive</div></a>
      <a href="{{ '/use-cases#logistics' | relative_url }}"><div class="mqtt-in-action-box" style="background-image: url('{{ 'assets/img/logistics.jpg' | relative_link }}');">Logistics</div></a>
      <a href="{{ '/use-cases#manufacturing' | relative_url }}"><div class="mqtt-in-action-box" style="background-image: url('{{ 'assets/img/manufacturing.jpg' | relative_link }}');"><span style="color: #000">Manufacturing</span></div></a>
      <a href="{{ '/use-cases#smarthome' | relative_url }}"><div class="mqtt-in-action-box" style="background-image: url('{{ 'assets/img/smart-home.jpg' | relative_link }}');">Smart Home</div></a>
      <a href="{{ '/use-cases#consumer-products' | relative_url }}"><div class="mqtt-in-action-box" style="background-image: url('{{ 'assets/img/consumer-products.jpg' | relative_link }}');"><span style="color: #000">Consumer Products</span></div></a>
      <a href="{{ '/use-cases#transportation' | relative_url }}"><div class="mqtt-in-action-box" style="background-image: url('{{ 'assets/img/transportation.jpg' | relative_link }}');">Transportation</div></a>
   </div>
</section>


