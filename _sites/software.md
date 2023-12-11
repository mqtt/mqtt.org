---
title: Software
index: 3
description: A collection of links to all important MQTT brokers/servers, MQTT client libraries, tools and plugins.
---

<section class="content-floating">
<h1>MQTT Software</h1>

<section class="accordion-wrapper software" style="margin-bottom: 50px;">
<!-- Servers Broker Start -->
   <button id="servers-brokers" class="accordion">Servers / Brokers</button>
   <div class="panel">
    <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/ably-logo.svg' | relative_url }}" class="software-logo" alt="Ably Logo" style="width: 110px; margin-left: 25px;">
         <div class="panel-item-description"><a href="https://www.ably.io/documentation/mqtt"><h3>Ably MQTT Broker</h3></a>
           <a href="https://www.ably.io/">Ably</a> provides an MQTT broker and protocol adapter that is able to translate back and forth between MQTT and Ably's own protocol. It provides support for WebSockets, HTTP, SSE, STOMP, AMQP, and many more. Ably provides an interoperable, globally-distributed realtime messaging infrastructure layer.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/akiro-logo.svg' | relative_url }}" class="software-logo" alt="Akiro MQTT Logo">
         <div class="panel-item-description"><a href="https://www.akiroio.com/"><h3>Akiro MQTT</h3></a>
            <a href="https://www.akiroio.com/">Akiro</a> MQTT Broker is a high scale MQTT broker with support for more than 20 Million active MQTT connections with over 1 Million messages per second. It's written in Java with Vert.X's async paradigm. <a href="https://github.com/Akiro-IO/akiro-clients">Akiro clients</a> can be used to communicate with the free to use <a href="https://www.akiroio.com/get-started">Akiro SaaS MQTT Broker</a>. Akiro supports MQTT, Websockets over MQTT, HTTP over MQTT, DLMS, OCPP with TLS support.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/activemq.png' | relative_url }}" class="software-logo" alt="ActiveMQ Logo">
         <div class="panel-item-description"><a href="http://activemq.apache.org/index.html"><h3>Apache ActiveMQ</h3></a>
            Details of “classic” ActiveMQ’s support for MQTT are available <a href="http://activemq.apache.org/mqtt.html">here</a>.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/activemq.png' | relative_url }}" class="software-logo" alt="ActiveMQ Artemis Logo">
         <div class="panel-item-description"><a href="http://activemq.apache.org/artemis/"><h3>Apache ActiveMQ Artemis</h3></a>
            The “next generation” of ActiveMQ, Artemis is a multi protocol messaging broker that supports MQTT.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mqtt-route.png' | relative_url }}" class="software-logo" alt="Bevywise Logo">
         <div class="panel-item-description"><a href="https://www.bevywise.com/mqtt-broker/"><h3>Bevywise MQTT Broker</h3></a>
         <a href="https://www.bevywise.com/mqtt-broker/">MQTTRoute</a> is a high performance broker.  The Secure MQTT Broker is written in C &amp; Python and works with all standard MQTT Clients. Bevywise MQTT Broker has a FREE and affordable premium version. MQTTRoute can be customized to write data to any data store using <a href="https://github.com/bevywise-networks/">standard connectors</a> or custom implementations. Try the <a href="https://www.bevywise.com/mqtt-broker/download.html">fully FREE version here</a>.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
          <img src="{{ 'assets/img/software/bifromq.png' | relative_url }}" class="software-logo" alt="BifroMQ Logo">
          <div class="panel-item-description">
          <a href="https://bifromq.io"><h3>BifroMQ</h3></a>
          <p><a href="https://bifromq.io">BifroMQ</a>, open-sourced by <b>Baidu</b>, is a distributed MQTT messaging middleware designed for high performance. Its standout feature is the native multi-tenancy support, which enhances resource sharing and workload isolation. The system's architecture integrates a distributed storage engine, tailored for environments with high load, reducing reliance on external middleware. BifroMQ is well-suited for developing large IoT networks and messaging systems, providing scalable, cloud-based, serverless solutions for extensive operations.</p>
           </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/mqtt-logo.svg' | relative_url }}" class="software-logo mqtt-logo" alt="Cassandana Logo">
         <div class="panel-item-description"><a href="https://github.com/mtsoleimani/cassandana/"><h3>Cassandana</h3></a>
         Cassandana is an open source MQTT message broker which is entirely written in Java. This project began its life as a fork of <a href="https://github.com/andsel/moquette">Moquette</a> , and later underwent some cleanup, optimization and adding extra features. Now it’s ready to work as an enterprise message broker.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/coreflux.png' | relative_url }}" class="software-logo" alt="Coreflux Logo">
         <div class="panel-item-description"><a href="https://www.coreflux.org"><h3>Coreflux</h3></a>
         Coreflux is a Data Hub, based on MQTT 3.1.1 and 5.0, designed to handle vast amounts of data from various sources, whether they be IoT devices, databases, applications, or external systems. The system can run flux assets that act as connectors, orchestrators, or model generators. Often considered an <b>MQTT Broker on Steroids</b>, you can check the <a href="https://docs.coreflux.org">documentation</a> for more information!
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/ejabberd.png' | relative_url }}" class="software-logo" alt="ejabberd Logo">
         <div class="panel-item-description"><a href="https://www.process-one.net/en/ejabberd"><h3>ejabberd</h3></a>
            ejabberd is an open-source MQTT broker written in Erlang and supported by ProcessOne. ejabberd introduced MQTT 5.0 broker services on top of its renowned XMPP server starting with <a href="https://www.process-one.net/blog/ejabberd-19-02-the-mqtt-edition/">version 19.02</a> through <code>mod_mqtt</code>. It relies on ejabberd infrastructure code that has been battle tested for 15+ years, like the clustering engine. ejabberd MQTT broker has been verified on large scale systems and can support millions of concurrent connections highly efficiently.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/emitter.png' | relative_url }}" class="software-logo" alt="Emitter Logo">
         <div class="panel-item-description"><a href="https://emitter.io"><h3>Emitter</h3></a>
           Emitter is clustered and open-source MQTT broker, written entirely in Go. It proposes several additional features on top of a traditional MQTT broker, as it includes custom per-topic security and shared-nothing scalable architecture which helps you avoid single points of failure. Full source-code available on <a href="https://github.com/emitter-io/emitter">GitHub</a>.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/emq.png' | relative_url }}" class="software-logo" alt="EMQX Logo">
         <div class="panel-item-description"><a href="https://www.emqx.com/en/products/emqx"><h3>EMQX</h3></a>
            <a href="https://www.emqx.io/">EMQX</a> is a fully open source, highly scalable, highly available distributed MQTT messaging broker for IoT, M2M and Mobile applications that can handle tens of millions of concurrent clients.<br/>
            Starting from 3.0 release, EMQX fully supports MQTT V5.0 protocol specifications and is backward compatible with MQTT V3.1 and V3.1.1, as well as other communication protocols such as MQTT-SN, CoAP, LwM2M, WebSocket and STOMP. The 3.0 release of the EMQX can scaled to 10+ million concurrent MQTT connections on one cluster.
            <a href="https://twitter.com/EMQTech">@EMQTech</a>
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/mqtt-logo.svg' | relative_url }}" class="software-logo mqtt-logo" alt="MQTT Logo">
         <div class="panel-item-description"><a href="https://github.com/alekras/erl.mqtt.server"><h3>Erl.mqtt.server</h3></a>
         erl.mqtt.server MQTT server is designed for communication in Machine to Machine (M2M) and Internet of Things (IoT) contexts and implements MQTT protocol versions 3.1 and 3.1.1. The server is written in Erlang as OTP application.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/everywhere-cloud.png' | relative_url }}" class="software-logo" alt="Eurotech Everywhere Logo">
         <div class="panel-item-description"><a href="https://www.eurotech.com/en/products/iot/iot-integration-platform/everyware-cloud"><h3>Eurotech Everywhere Cloud</h3></a>
         Eurotech Everywhere Device Cloud is a cloud-based service provided by <a href="http://www.eurotech.com">Eurotech</a>.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/mqtt-logo.svg' | relative_url }}" class="software-logo mqtt-logo" alt="MQTT Logo">
         <div class="panel-item-description"><a href="https://www.flashmq.org"><h3>FlashMQ</h3></a>
            FlashMQ is a lightweight, high performance Open Source MQTT server, capable of <a href="https://www.youtube.com/watch?v=vZWLitdCkJQ">1 million messages per second on a single 4 core server</a>.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/flespi.png' | relative_url }}" class="software-logo" alt="flespi Logo">
         <div class="panel-item-description"><a href="https://flespi.com/mqtt-broker"><h3>flespi</h3></a>
         flespi is a public and free cloud-based MQTT broker service with declared 3.1, 3.1.1, 5.0 protocols compliance. High-volume targeted architecture, isolated MQTT namespace, WebSockets/SSL support, configurable ACL, commercial and free SLA, managed by <a href="https://flespi.io/mqtt">HTTP REST API</a>.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/mqtt-logo.svg' | relative_url }}" class="software-logo mqtt-logo" alt="HBMQTT Logo">
         <div class="panel-item-description"><a href="https://github.com/beerfactory/hbmqtt"><h3>HBMQTT</h3></a>
            HBMQTT is an open-source implementation of MQTT broker and client. It uses Python 3.4+ asyncio library for providing a mono-threaded, non-blocking implementation of the protocol.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/hivemq.svg' | relative_url }}" class="software-logo" style="height:80px; margin-top: 5px;" alt="HiveMQ Logo">
         <div class="panel-item-description"><a href="https://www.hivemq.com"><h3>HiveMQ</h3></a>
         HiveMQ is a MQTT broker which was built from the ground up with maximum scalability and enterprise-ready security in mind. It comes with native web socket support and an open source plugin SDK to extend its functionality or integrate it with other components. A <a href="https://www.hivemq.com/public-mqtt-broker/">public test server</a> is also available.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/jmqtt.png' | relative_url }}" class="software-logo" alt="Jmqtt Logo">
         <div class="panel-item-description"><a href="https://github.com/Cicizz/jmqtt"><h3>Jmqtt</h3></a>
            Jmqtt is a MQTT broker which is implemented by Java and Netty, supports persistence and cluster.
         </div>
      </div>
      <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/ibm.png' | relative_url }}" class="software-logo" alt="IBM Logo">
         <div class="panel-item-description"><a href="https://www.ibm.com/cloud/app-connect"><h3>IBM Integration Bus</h3></a>
         IBM Integration Bus V9 has Telemetry feature built-in as optional licensed feature. IBM WebSphere MessageBroker V7 &amp; V8 also include it as optionally licensed feature. <a href="https://www.ibm.com/support/knowledgecenter/SSFKSJ_7.5.0/com.ibm.mm.tc.doc/tc00100_.htm">Really Small Message Broker</a> 75KB MQTT broker runtime free download as binaries from IBM alphaWorks, RSMB is a C implementation of a tiny MQTT server suitable for development, embedded systems, concentrators or small to medium sized deployments. It provides complete MQTT v3.1 support, bridging, and a C client API.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/ibm.png' | relative_url }}" class="software-logo" alt="IBM Logo">
         <div class="panel-item-description"><a href="https://www.eclipse.org/amlen/docs/welcome.html"><h3>Eclipse Amlen</h3></a>
            Eclipse Amlen (<a href="https://www.ibm.com/us-en/marketplace/watson-iot-platform-message-gateway">IBM WIoTP Message Gateway</a>opensourced IBM mqtt broker) is a scalable, highly available messaging broker for MQTT (including MQTT v5, HTML5 WebSockets, JMS. Also connects/bridges IBM MQ, IBM Integration Bus, Kafka with Amlen bridge. (Was formerly called IBM IoT MessageSight).
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/ibm.png' | relative_url }}" class="software-logo" alt="IBM Logo">
         <div class="panel-item-description"><a href="https://www.ibm.com/support/knowledgecenter/en/SSFKSJ_7.5.0/com.ibm.mq.pro.doc/q001030_.htm"><h3>IBM Websphere MQ Telemetry</h3></a>
         WebSphere MQ version 7.1 and above. It provides full MQTT v3.1 support, IBM MQ and JMS support. IBM WebSphere MQ Advanced includes the MQTT license at no charge. It ships with reference Java (MIDP and above), C and JavaScript (MQTT over WebSocket) clients.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/mqtt-logo.svg' | relative_url }}" class="software-logo mqtt-logo" alt="JoramMQ Logo">
         <div class="panel-item-description"><a href="http://mqtt.jorammq.com"><h3>JoramMQ</h3></a>
            JoramMQ is an offering by ScalAgent providing a message broker that fully supports MQTT 3.1, JMS 2.0, and AMQP 1.0. Interoperability between these standards is ensured by the message broker. MQTT can be used over TCP/IP, TLS (SSL), WebSocket, and secure WebSocket. JoramMQ is particularly appropriate for applications that need to scale with the number of MQTT clients while allowing the publishers to reliably transmit a large volume of messages with a low latency
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/litmus.png' | relative_url }}" class="software-logo" alt="Loop Logo">
         <div class="panel-item-description"><a href="http://litmusautomation.com/"><h3>Litmus Automation Loop</h3></a>
         Loop is a cloud based MQTT broker with scalability, high availability and security at core. Loop provides full MQTT 3.1 support and JMS connectivity. It can handle extremely large numbers of connected clients. On the other side it can be connected to any ERP, CRM and enterprise architecture with ESB or NoSQL databases for blazing fast data storage.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/mqtt-logo.svg' | relative_url }}" class="software-logo mqtt-logo" alt="Moquette Logo">
         <div class="panel-item-description"><a href="https://github.com/andsel/moquette"><h3>Moquette</h3></a>
         Moquette is a Java MQTT broker based on an eventing model with Netty.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mosca.png' | relative_url }}" class="software-logo" alt="Mosca Logo">
         <div class="panel-item-description"><a href="https://github.com/mcollina/mosca"><h3>Mosca</h3></a>
         As node.js MQTT broker can Mosca be plugged on top of Redis, AMQP, MQTT, or ZeroMQ.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mosquitto.png' | relative_url }}" class="software-logo" alt="Mosquitto Logo">
         <div class="panel-item-description"><a href="https://www.mosquitto.org"><h3>Mosquitto</h3></a>
            Mosquitto is an Open Source MQTT server. A public, hosted test server is also available (<a href="https://test.mosquitto.org/">more information</a>)
         </div>
      </div>
  <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mosquitto.png' | relative_url }}" class="software-logo" alt="Mosquitto Logo">
         <div class="panel-item-description"><a href="https://cedalo.com/mqtt-broker-pro-mosquitto/"><h3>Pro Edition for Eclipse Mosquitto (Server)</h3></a>
            A pro version of the world’s #1 MQTT broker, offering <a href="https://cedalo.com/mqtt-broker-pro-mosquitto/high-availability/">High Availability</a>, access to REST API, improved reliability, enhanced security, and professional support. An ideal solution for commercial use. <a href="https://cedalo.com/mqtt-broker-pro-mosquitto/trial-signup/">Access a free 14-day trial (cloud) now!</a>
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mqttnet.png' | relative_url }}" class="software-logo" alt="MQTTnet Logo">
         <div class="panel-item-description"><a href="https://github.com/chkr1011/MQTTnet/"><h3>MQTTnet</h3></a>
         MQTTnet is a .NET library for MQTT based communication. It provides a MQTT client and a MQTT server (broker).
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/mqtt-logo.svg' | relative_url }}" class="software-logo mqtt-logo" alt="MQTT Logo">
         <div class="panel-item-description"><a href="https://github.com/Wizzercn/MqttWk"><h3>MqttWk</h3></a>
            MqttWk is a Java MQTT broker based on NutzBoot + Netty + Redis + Kafka(Optional).The broker supports QoS 0, QoS 1 and QoS 2.It uses Netty for the protocol encoding and decoding part.Using NutzBoot to provide dependency injection and attribute configuration, using Redis to implement message caching and clustering, and using Kafka to implement message proxy.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/nanomq.svg' | relative_url }}" class="software-logo" alt="NanoMQ Logo">
         <div class="panel-item-description"><a href="https://nanomq.io/"><h3>NanoMQ</h3></a>
         A light-weight and blazing-fast MQTT Broker for the IoT Edge platform. NanoMQ is based on NNG's asynchronous I/O threading model. With an extension of MQTT support in the protocol layer and reworked transport layer. Plus an enhanced asynchronous I/O mechanism to maximize the throughput capacity.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/rabbitmq.png' | relative_url }}" class="software-logo" alt="RabbitMQ Logo">
         <div class="panel-item-description"><a href="http://rabbitmq.com/"><h3>RabbitMQ</h3></a>
         RabbitMQ is an AMQP message broker – with an <a href="http://www.rabbitmq.com/blog/2012/09/12/mqtt-adapter/">MQTT plugin</a> (bundled in version 3.x onwards). A public test server is also available (<a href="https://github.com/mqtt/mqtt.github.io/wiki/public_brokers">more information</a>).
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/solace.png' | relative_url }}" class="software-logo" alt="Solace Logo">
         <div class="panel-item-description"><a href="http://dev.solacesystems.com/tech/"><h3>Solace</h3></a>
         Solace Message Routers (available as hardware and software) are message brokers that support MQTT, JMS, and REST among other APIs, protocols and qualities of service for enterprise messaging, data collection and web/mobile streaming. They support very high connection counts and throughput with built-in buffering to handle bursty traffic, and offer enterprise-class monitoring, high availability and security.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/swiftmq.png' | relative_url }}" class="software-logo" alt="SwiftMQ Logo">
         <div class="panel-item-description"><a href="http://www.swiftmq.com/landing/router/index.html"><h3>SwiftMQ</h3></a>
         SwiftMQ Universal Router is an enterprise message system with integrated micro services and realtime streaming analytics platform (SwiftMQ Streams, SwiftMQ Dashboard). It supports MQTT 3.1/3.1.1, AMQP 1.0/0.9.1, JMS 1.1 and is fully interoperable between these protocols. It has a built-in Dynamic Routing Architecture to build large Federated Router Networks and Clusters. SwiftMQ High Availability Router is the High and Continuous Availability version of SwiftMQ Universal Router with active replication and transparent client failover.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/thingscale.png' | relative_url }}" class="software-logo" alt="ThingScale IoT Logo">
         <div class="panel-item-description"><a href="http://thingscale.io/index_en.html"><h3>ThingScale IoT message broker</h3></a>
         ThingScale IoT message broker is a fully-managed IoT messaging service provided by <a href="http://sensinics.co.jp">Sensinics,LLC</a>.<br/>
         ThingScale provides a messaging system for IoT connected devices. The API is used to retrieve events, users, devices, sessions, and channels in JSON format. ThingScale supports TLS payload encryption, scheme-less and cyclic data sampling, and trigger-based notifications. A 30days trial license is offered free of charge. MQTT is the preferred messaging protocol. <a href="https://sensinics.atlassian.net/wiki/spaces/TD/pages/76021778/Developer+Portal">Dev Portal</a> &amp; <a href="https://thingscale.docs.apiary.io/">API Portal</a>
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/vernemq.png' | relative_url }}" class="software-logo" alt="VerneMQ Logo">
         <div class="panel-item-description"><a href="http://verne.mq/"><h3>VerneMQ</h3></a>
         VerneMQ is an enterprise ready, high-performance, distributed MQTT message broker. It scales horizontally and vertically on commodity hardware to support a high number of concurrent publishers and consumers while maintaining low and predictable latency and fault tolerance. VerneMQ plugins can be developed in Erlang, Elixir, Lua, and any programming language that can implement HTTP WebHooks. VerneMQ uses modern broadcast protocols and LevelDB for state replication in a cluster. VerneMQ is Open Source and Apache2 licensed.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/vertx.svg' | relative_url }}" class="software-logo" alt="Vert.x Logo" style="padding: 5px 20px; box-sizing: border-box;">
         <div class="panel-item-description"><a href="https://github.com/GruppoFilippetti/vertx-mqtt-broker"><h3>Vert.x MQTT Broker</h3></a>
        Vert.x MQTT Broker is an open-source implementation of MQTT server. It implements protocol versions 3.1.1 and 3.1, supports QoS 2, and uses OAuth2 for authentication. It uses <a href="http://vertx.io/">vert.x</a> as library for tcp management, non-blocking / actor-model, clustering and auth plugin system.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/waterstream.png' | relative_url }}" class="software-logo" alt="Waterstrean Logo">
         <div class="panel-item-description"><a href="http://waterstream.io/"><h3>Waterstream</h3></a>
         Waterstream is the first and the only MQTT platform on the market leveraging Apache Kafka as its own storage and distribution engine. Every incoming MQTT message is immediately available in your microservices architecture or your analytics platform without any further processing. Vice-versa, every message written on a Kafka topic it’s sent to MQTT clients. All the necessary MQTT state, like subscriptions and QoS message status is also stored in Kafka—no need for additional storage.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item last">
         <img src="{{ 'assets/img/software/yunba.png' | relative_url }}" class="software-logo" alt="Yunba Logo">
         <div class="panel-item-description"><a href="http://yunba.io/"><h3>Yunba.io</h3></a>
         Yunba is a backend cloud platform that provides real-time message dispatch service to mobile applications and devices and uses MQTT as a transport protocol. The services include bi-directional push for instant-messaging, real-time analyzing, real-time online monitoring.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
        <img src="{{ 'assets/img/software/harksys.png' | relative_url }}" class="software-logo" alt="Hark Logo">
        <div class="panel-item-description"><a href="https://harksys.com/platform/hark-connect/"><h3>Hark Connect</h3></a>
          The <a href="https://harksys.com">Hark</a> broker is an MQTT broker written in C# for edge to cloud communication. This broker supports TLS/SSL for layered security and functions as a stand alone broker that can subscribe to topics from other applications (not just The Hark Platform). Hark's low-code solution supports an extremely large number of connections while maintaining security at its core.
        </div>
      </div>
   <!-- closing div -->
   </div>
   <!-- End of Servers / Brokers Panel -->
   <button id="cloud-brokers" class="accordion">Cloud Brokers</button>
   <div class="panel">
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/hivemq-cloud.svg' | relative_url }}" class="software-logo" style="height:95px; margin-top: 5px;" alt="HiveMQ Cloud Logo">
         <div class="panel-item-description"><a href="https://www.hivemq.com/mqtt-cloud-broker"><h3>HiveMQ Cloud️</h3></a>
         HiveMQ Cloud is a free cloud native IoT messaging broker that enables you to connect up to 100 devices. It supports the entire <a href="/mqtt-specification">MQTT specification</a>. For larger projects HiveMQ Cloud can scale up to support business critical solutions. <a href="https://console.hivemq.cloud/?utm_source=mqtt-org&utm_medium=cloud-brokers&utm_campaign=cloud">Sign up</a>.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/myqtthub.png' | relative_url }}" class="software-logo" alt="MyQTTHub Logo">
         <div class="panel-item-description"><a href="https://myqtthub.com/en/"><h3>MyQttHub.com</h3></a>
            Easily create your MQTT IoT project with MyQttHub.com, an open and scalable Cloud MQTT platform with professional support options.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/emqx-cloud.svg' | relative_url }}" class="software-logo" style="..." alt="EMQX Cloud Logo">
         <div class="panel-item-description"><a href="https://www.emqx.com/en/cloud"><h3>EMQX Cloud</h3></a>
         EMQX Cloud is a fully managed MQTT service for IoT. Connecting massive devices to the EMQX Cloud for reliable, real-time IoT data transmission, processing, and integration. Accelerate business that matters while avoiding the headaches of infrastructure management. <a href="https://www.emqx.com/en/try?product=cloud">Free trial now</a>.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mosquitto.png' | relative_url }}" class="software-logo" alt="Mosquitto Logo">
         <div class="panel-item-description"><a href="https://cedalo.com/mqtt-broker-pro-mosquitto/"><h3>Pro Edition for Eclipse Mosquitto (Cloud)</h3></a>
            A pro version of the world’s #1 MQTT broker, offering <a href="https://cedalo.com/mqtt-broker-pro-mosquitto/high-availability/">High Availability</a>, access to REST API, improved reliability, enhanced security, and professional support. An ideal solution for commercial use. <a href="https://cedalo.com/mqtt-broker-pro-mosquitto/trial-signup/">Access a free 14-day trial now!</a>
         </div>
      </div>
      <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mqtt-route.png' | relative_url }}" class="software-logo" alt="MQTTRoute Logo">
         <div class="panel-item-description"><a href="https://www.bevywise.com/hosted-mqtt-server/"><h3>CrystalMQ</h3></a>
            <a href="https://www.bevywise.com/hosted-mqtt-server/">CrystalMQ, the Cloud MQTT Broker</a> provides a completely managed service that can smoothly scale to meet the demands of large IoT applications and provides the reliability business-critical systems require without any intricate set up & deployment. Try the <a href="https://www.bevywise.com/hosted-mqtt-server/signup.html">hosted version for FREE</a>.
         </div>
      </div>
      <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/harksys.png' | relative_url }}" class="software-logo" alt="Hark Logo">
        <div class="panel-item-description"><a href="https://harksys.com/platform/"><h3>Hark Platform</h3></a>
          The <a href="https://harksys.com">Hark</a> Platform provides a cloud native hosted MQTT services with support for managing users, ACLs at a tennanted level. Additional features such as triggers, automations and integrations allow users to rapidly deploy IoT solutions in a serverless fashion. Use cases include sensors, industrial assets and other internet connected devices. <a href="https://harksys.com/contact/">Get a free trial.</a>
        </div>
      </div>
   <!-- closing div -->
   </div>
   <!-- Cloud Brokers End -->
   <!-- Client Libraries Start -->
   <button id="client-libraries" class="accordion">Client libraries</button>
   <div class="panel">
      <div class="subhead">Device-Specific</div>
      <ul>
         <li><a href="https://github.com/knolleary/pubsubclient">Arduino</a> (<a href="http://pubsubclient.knolleary.net/">more information</a>)</li>
         <li><a href="https://github.com/tuanpmt/espduino">Espduino</a> (tailored Arduino library for the ESP8266)</li>
         <li><a href="http://mbed.org/users/jwende/code/MQTT/">mbed (simple port of the Arduino pubsubclient)</a></li>
         <li><a href="http://mbed.org/users/Nim65s/code/niMQTT/">mbed (native implementation)</a></li>
         <li><a href="http://developer.mbed.org/teams/mqtt/code/MQTT/">mbed (Paho Embedded C++ port)</a></li>
         <li><a href="http://developer.mbed.org/teams/mqtt/code/MQTTPacket/">mbed (Paho Embedded C port)</a></li>
         <li><a href="https://github.com/njh/NanodeMQTT/">Nanode</a></li>
         <li><a href="https://github.com/danielan/NetduinoMQTT">Netduino</a></li>
         <li><a href="https://github.com/eclipse/paho.mqtt.m2mqtt">M2MQTT (works with .Net Micro Framework)</a></li>
      </ul>
      <div class="subhead">Actionscript</div>
      <ul>
         <li><a href="https://github.com/yangboz/as3MQTT">as3MQTT</a></li>
      </ul>
      <div class="subhead">Ada</div>
      <ul>
         <li><a href="https://github.com/persan/mosquitto-ada">mosquitto-ada</a> - A binding to libmosquitto</li>
         <li><a href="http://www.dmitry-kazakov.de/ada/components.htm#MQTT">Simple Components MQTT</a> - Pure Ada MQTT client and server/broker</li>
      </ul>
      <div class="subhead">Ballerina</div>
      <ul>
         <li><a href="https://github.com/ballerina-platform/module-ballerina-mqtt">Ballerina MQTT</a> - The Ballerina MQTT client library which supports MQTTv5. More details on the client APIs can be read <a href="https://lib.ballerina.io/ballerina/mqtt/latest">here</a></li>
      </ul>
      <div class="subhead">Bash</div>
      <ul>
         <li>see <a href="#shell-script">Shell Script</a>, below</li>
      </ul>
      <div class="subhead">C</div>
      <ul>
         <li><a href="https://www.eclipse.org/paho/clients/c/">Eclipse Paho C</a></li>
         <li><a href="https://www.eclipse.org/paho/clients/c/embedded/">Eclipse Paho Embedded C</a></li>
         <li><a href="http://mosquitto.org">libmosquitto</a></li>
         <li><a href="https://github.com/menudoproblema/libemqtt">libemqtt</a> - an embedded C client</li>
         <li><a href="https://github.com/LiamBindle/MQTT-C">MQTT-C</a> - A portable MQTT C client for embedded systems and PCs alike.</li>
         <li><a href="https://github.com/wolfSSL/wolfMQTT">wolfMQTT</a> - Embedded C client</li>
         <li><a href="https://github.com/RealTimeLogic/SharkSSL/blob/main/src/SharkMQTT.c">SharkMQTT</a> - Embedded C client - <a href="https://realtimelogic.com/products/sharkmqtt/">more information</a> - <a href="https://realtimelogic.com/ba/doc/en/C/shark/group__MQTTLib.html">documentation</a></li>
         <li><a href="https://github.com/curl/curl">libcurl</a> - libcurl has basic support for publish and subscribe.</li>
         <li><a href="https://gitlab.com/rts_nepal/embedded/lwIP_mbedtls_mqtt_c">MQTT over lwIP</a> - MQTT C client for embedded systems using FreeRTOS, lwIP and mbedtls</li>
         <li><a href="http://smartfactory.openapc.com">libsmartfactory</a> - easy to use library for different Smart Factory/Industry 4.0 technologies including a MQTT client implementation</li>
         <li><a href="https://github.com/zhaojh329/libumqtt">libumqtt</a> - A Lightweight and fully asynchronous MQTT client C library based on libev</li>
      </ul>
      <div class="subhead">C++</div>
      <ul>
      <li><a href="https://www.eclipse.org/paho/clients/cpp/">Eclipse Paho C++</a></li>
      <li><a href="http://mosquitto.org">libmosquittopp</a></li>
      <li><a href="https://www.eclipse.org/paho/clients/c/embedded/">Eclipse Paho Embedded C++</a></li>
      <li><a href="https://github.com/redboltz/mqtt_cpp">mqtt_cpp</a> - MQTT client and server library based on C++14 and Boost.Asio. It supports MQTT v3.1.1 and v5.</li>
      <li><a href="https://github.com/redboltz/async_mqtt">async_mqtt</a> - MQTT client and server library based on C++17 and Boost.Asio. It supports MQTT v3.1.1 and v5.0. This is an evolved mqtt_cpp.</li>
      <li><a href="https://github.com/X-Ryl669/eMQTT5">eMQTT5</a> - MQTT 5.0 client.</li>
      </ul>
      <div class="subhead">Clojure</div>
      <ul>
         <li><a href="http://clojuremqtt.info">Machine Head</a></li>
         <li><a href="https://github.com/xively/clj-mqtt/">Clojure MQTT Codec for Netty</a></li>
      </ul>
      <div class="subhead">Dart</div>
      <ul>
         <li><a href="http://pub.dartlang.org/packages/mqtt">mqtt.dart</a></li>
         <li><a href="https://pub.dev/packages/mqtt_client">mqtt_client</a></li>
      </ul>
      <div class="subhead">Delphi</div>
      <ul>
      <li><a href="https://github.com/jamiei/Delphi-TMQTT2">Delphi-TMQTT2</a></li>
      </ul>
      <div class="subhead">Erlang</div>
      <ul>
         <li><a href="https://github.com/squaremo/erlmqtt">erlmqtt</a></li>
         <li><a href="https://github.com/emqtt/emqttc">emqttc</a> - Erlang MQTT Client</li>
         <li><a href="http://code.google.com/p/mqtt4erl/">mqtt4erl</a></li>
         <li><a href="http://code.google.com/p/my-mqtt4erl/">my-mqtt4erl</a> - updated fork of mqtt4erl</li>
         <li><a href="https://github.com/alekras/mqtt_client">erl.mqtt.client</a> - Erlang MQTT client</li>
      </ul>
      <div class="subhead">Elixir</div>
      <ul>
         <li><a href="https://github.com/suvash/hulaaki">hulaaki</a> - An Elixir library (driver) for clients communicating with MQTT brokers(via the MQTT 3.1.1 protocol).</li>
         <li><a href="https://github.com/timbuchwaldt/exmqttc">Exmqttc</a> - Elixir wrapper for the emqttc library.</li>
         <li><a href="https://github.com/gausby/tortoise">tortoise</a> - An MQTT Client written in Elixir</li>
      </ul>
      <div class="subhead">Go</div>
      <ul>
         <li><a href="https://github.com/eclipse/paho.mqtt.golang">Eclipse Paho Go</a></li>
         <li><a href="https://github.com/jeffallen/mqtt">mqtt by jeffallen</a></li>
         <li><a href="https://github.com/pascaldekloe/mqtt">MQTT🤖</a></li>
         <li><a href="https://github.com/soypat/natiu-mqtt">natiu-mqtt</a> - Dead simple, small MQTT implementation well suited for embedded systems</li>
      </ul>
      <div class="subhead">Haskell</div>
      <ul>
         <li><a href="http://hackage.haskell.org/package/mqtt-hs">mqtt-hs</a></li>
         <li><a href="http://hackage.haskell.org/package/net-mqtt">net-mqtt</a> (3.1.1 and 5.0 client)</li>
      </ul>
      <div class="subhead">Java</div>
      <ul>
         <li><a href="https://github.com/apache/activemq/tree/master/activemq-client">ActiveMQ Client</a></li>
         <li><a href="https://projects.eclipse.org/projects/iot.paho/downloads">Eclipse Paho Java</a></li>
         <li><a href="https://github.com/fusesource/mqtt-client">Fusesource mqtt-client</a></li>
         <li><a href="http://www-933.ibm.com/support/fixcentral/swg/selectFix?product=ibm%2FWebSphere%2FWebSphere+MQ&amp;fixids=1.0.0.1-WS-MQCP-MA9B&amp;source=dbluesearch&amp;function=fixId&amp;parent=ibm/WebSphere"> "MA9B" zip of 1/2 dozen mobile clients source code.</a> Includes Android-optimized Java source that works with Android notifications, based on Paho</li>
         <li><a href="https://github.com/AlbinTheander/MeQanTT">MeQanTT</a></li>
         <li><a href="https://github.com/andsel/moquette">moquette</a></li>
         <li><a href="https://github.com/Wizzercn/MqttWk">MqttWk</a></li>
         <li><a href="https://github.com/hivemq/hivemq-mqtt-client">HiveMQ MQTT Client</a> - MQTT 5.0 and MQTT 3.1.1 compatible and feature-rich high-performance Java client library with different API flavours and backpressure support</li>
         <li><a href="http://www-01.ibm.com/support/docview.wss?rs=171&amp;uid=swg24006006&amp;loc=en_US&amp;cs=utf-8&amp;lang=en">IA92</a> - <em>deprecated</em> IBM IA92 support pack, use Eclipse Paho GUI client instead. A useful MQTT Java swing GUI for publishing &amp; subscribing. The Eclipse Paho GUI is identical but uses newer client code</li>
         <li><a href="https://github.com/Qatja">Qatja</a> is a Java client library for MQTT 3.1.1 with specific implementation for Android and Processing</li>
         <li><a href="https://github.com/Sentienz/akiro-clients">Sentienz Akiro MQTT Client</a> - MQTT 3.1.1 compatible <a href="https://theakiro.com/">Akiro MQTT broker</a> Java client with callbacks.</li>
         <li><a href="https://vertx.io/docs/vertx-mqtt/java/#_vert_x_mqtt_client">vertx-mqtt-client</a> is an open-source, high performance, non-blocking MQTT client built as a part of vert.x's JVM toolkit.</li>
         <li><a href="https://github.com/TwoGuysFromKabul/xenqtt">Xenqtt</a> - <a href="http://xenqtt.sf.net/">documentation</a> Includes a client library, mock broker for unit/integration testing, and applications to support enterprise needs like using a cluster of servers as a single client, an HTTP gateway, etc.</li>
         <li><a href="https://micronaut-projects.github.io/micronaut-mqtt/latest/guide/">Micronaut MQTT</a> - integration between <a href="https://micronaut.io">Micronaut Framework</a> and MQTT.etc.</li>         
      </ul>
      <div class="subhead">Javascript / Node.js</div>
      <ul>
         <li><a href="https://github.com/mcollina/ascoltatori">Ascoltatori</a> - a node.js pub/sub library that allows access to Redis, AMQP, MQTT, and ZeroMQ with the same API.</li>
         <li><a href="https://github.com/eclipse/paho.mqtt.javascript">Eclipse Paho HTML5 JavaScript over WebSocket.</a></li>
         <li><a href="http://www-01.ibm.com/support/docview.wss?rs=171&amp;uid=swg24033580&amp;loc=en_US&amp;cs=utf-8&amp;lang=en" >IBM-provided PhoneGap / Apache Cordova MQTT plug-in for Android</a> - JavaScript API is identical to Eclipse Paho HTML5 JavaScript</li>
         <li><a href="https://github.com/adamvr/MQTT.js">mqtt.js</a></li>
         <li><a href="https://github.com/yilun/node_mqtt_client">node_mqtt_client</a></li>
      </ul>
      <div class="subhead">LotusScript</div>
      <ul>
         <li><a href="https://tingenek.wordpress.com/2011/11/30/mqtt-with-lotus-notes/" >MQTT From LotusScript</a></li>
      </ul>
      <div class="subhead">Lua</div>
      <ul>
          <li><a href="https://github.com/RealTimeLogic/BAS-Resources/blob/main/src/core/.lua/mqttc.lua">Barracuda App Server's MQTT Client</a> - <a href="https://realtimelogic.com/products/lua-mqtt/">more information</a> - <a href="https://realtimelogic.com/ba/doc/?url=MQTT.html">documentation</a></li>
         <li><a href="http://git.eclipse.org/c/paho/org.eclipse.paho.mqtt.lua.git/" >Eclipse Paho Lua</a></li>
         <li><a href="https://github.com/xHasKx/luamqtt/">luamqtt - Pure-lua MQTT client</a></li>
         <li><a href="https://github.com/zhaojh329/libumqtt">libumqtt</a></li>
         <li><a href="https://luarocks.org/modules/karlp/lua-mosquitto" >lua-mosquitto</a></li>
      </ul>
      <div class="subhead">.NET / dotNET</div>
      <ul>
         <li><a href="https://github.com/hivemq/hivemq-mqtt-client-dotnet">HiveMQtt</a> - The Spectacular C# MQTT Client for .NET</li>
         <li><a href="https://github.com/mFourLabs/KittyHawkMQ">KittyHawkMQ</a></li>
         <li><a href="https://github.com/chkr1011/MQTTnet">MQTTnet</a></li>
         <li><a href="http://sourceforge.net/projects/mqttdotnet/">MqttDotNet</a></li>
         <li><a href="https://github.com/markallanson/nmqtt">nMQTT</a></li>
         <li><a href="https://github.com/eclipse/paho.mqtt.m2mqtt">M2MQTT</a></li>
         <li><a href="https://github.com/xljiulang/Paho.MqttDotnet/">Paho.MqttDotnet</a></li>
         <li><a href="https://github.com/ericvoid/StriderMqtt">StriderMqtt</a></li>
         <li><a href="https://github.com/xamarin/mqtt">xamarin mqtt</a></li>
      </ul>
      <div class="subhead">Objective-C</div>
      <ul>
         <li><a href="https://github.com/GrayWang/mqttIO-objC">mqttIO-objC</a></li>
         <li><a href="https://mosquitto.org">libmosquitto</a> - via wrappers (<a href="https:///github.com/njh/marquette">example</a>)</li>
         <li><a href="https://github.com/jmesnil/MQTTKit">MQTTKit</a> (<a href="https:///github.com/jmesnil/MQTTExample">sample app</a>)</li>
         <li><a href="http://www-933.ibm.com/support/fixcentral/swg/selectFix?product=ibm%2FWebSphere%2FWebSphere+MQ&amp;fixids=1.0.0.1-WS-MQCP-MA9B&amp;source=dbluesearch&amp;function=fixId&amp;parent=ibm/WebSphere">"MA9B" zip of 1/2 dozen mobile clients source code including Objective-C</a></li>
      </ul>
      <div class="subhead">OCaml</div>
      <ul>
         <li><a href="https://github.com/j0sh/ocaml-mqtt">ocaml-mqtt</a></li>
         <li><a href="https://github.com/philtomson/mqtt_client">mqtt_client</a></li>
      </ul>
      <div class="subhead">Perl</div>
      <ul>
         <li><a href="https://github.com/beanz/net-mqtt-perl">net-mqtt-perl</a></li>
         <li><a href="https://github.com/beanz/anyevent-mqtt-perl">anyevent-mqtt-perl</a></li>
         <li><a href="http://search.cpan.org/dist/WebSphere-MQTT-Client/">WebSphere-MQTT-Client</a></li>
         <li>Net::MQTT::Simple <a href="https://metacpan.org/pod/Net::MQTT::Simple">cpan</a> <a href="https://github.com/Juerd/Net-MQTT-Simple">github</a></li>
      </ul>
      <div class="subhead">PHP</div>
      <ul>
         <li><a href="https://github.com/bluerhinos/phpMQTT">phpMQTT</a></li>
         <li><a href="https://github.com/mgdm/Mosquitto-PHP">Mosquitto-PHP</a></li>
         <li><a href="https://github.com/sskaje/mqtt">sskaje's MQTT library</a></li>
         <li><a href="https://github.com/simps/mqtt">Simps/MQTT</a> - MQTT Protocol Analysis and Coroutine Client for PHP. Support for 3.1, 3.1.1 and 5.0 versions of the MQTT protocol.</li>
      </ul>
      <div class="subhead">Python</div>
      <ul>
         <li><a href="https://github.com/eclipse/paho.mqtt.python">Eclipse Paho Python</a> - originally the mosquitto Python client</li>
         <li><a href="https://github.com/wialon/gmqtt">gmqtt</a></li>
         <li><a href="https://github.com/iwanbk/nyamuk">nyamuk</a></li>
         <li><a href="https://github.com/adamvr/MQTT-For-Twisted-Python">MQTT for twisted python</a></li>
         <li><a href="https://github.com/beerfactory/hbmqtt">HBMQTT</a></li>
         <li><a href="https://github.com/eerimoq/mqttools">mqttools</a></li>
      </ul>
      <div class="subhead">REXX</div>
      <ul>
         <li><a href="https://github.com/DougieLawson/REXX_MQTT">REXX MQTT</a></li>
      </ul>
      <div class="subhead">Prolog</div>
      <ul>
         <li><a href="https://github.com/olsky/swi-mqtt-pack">MQTT Pack</a> - Mosquitto library as a SWI-Prolog pack</li>
      </ul>
      <div class="subhead">Qt</div>
      <ul>
         <li><a href="https://github.com/emqtt/qmqtt">qmqtt</a> - MQTT Client for Qt</li>
      </ul>
      <div class="subhead">Ruby</div>
      <ul>
         <li><a href="https://github.com/njh/ruby-mqtt">ruby-mqtt</a></li>
         <li><a href="https://rubygems.org/gems/em-mqtt">em-mqtt</a></li>
         <li><a href="https://github.com/xively/mosquitto">mosquitto</a></li>
      </ul>
      <div class="subhead">Rust</div>
      <ul>
         <li><a href="https://github.com/GunnarMorrigan/mqrstt">mqrstt</a> - Pure rust MQTTv5 client</li>
      </ul>
      <div class="subhead">Shell Script</div>
      <ul>
         <li><a href="https://github.com/raphaelcohn/bish-bosh">bish-bosh</a>, supports bash, ash (including BusyBox), pdksh and mksh.</li>
      </ul>
      <div class="subhead">Smalltalk</div>
      <ul>
         <li><a href="http://www.squeaksource.com/MQTTClient.html">MQTT client for Squeak</a>, for Squeak 5.1</li>
      </ul>
      <div class="subhead">Swift</div>
      <ul>
         <li><a href="https://github.com/emqtt/CocoaMQTT">CocoaMQTT</a> - An MQTT client for iOS and OS X written with Swift</li>
         <li><a href="https://github.com/adam-fowler/mqtt-nio">MQTT NIO</a> - A Swift NIO MQTT Client supporting v3.1.1 and v5.0</li>
      </ul>
      <div class="subhead">Tcl</div>
      <ul>
         <li><a href="https://github.com/Tingenek/tcl-mqtt">tcl-mqtt</a></li>
      </ul>
   </div>
   <!-- End of Client Libraries Panel -->
   <!-- Tools and Applications Start -->
   <button id="tools-applications" class="accordion">Tools and Applications</button>
   <div class="panel">
      <div class="subhead">Web</div>
         <ul>
            <li><a href="https://flowforge.com/">FlowForge</a> - is a hosted Node-RED platform that allows you to easily create MQTT applications using low-code and visual programming. </li>
            <li><a href="https://mqttboard.flespi.io">MQTT Board</a> - diagnostic oriented MQTT 5.0 client tool based on <a href="https://github.com/mqttjs">mqtt.js</a>. Available in <a href="https://github.com/flespi-software/mqtt-board">open source</a>.</li>
            <li><a href="https://mqtttiles.flespi.io">MQTT Tiles</a> - <a href="https://github.com/flespi-software/MQTT-Tiles">Open source</a> MQTT-based dashboard visualization tool.</li>
            <li><a href="http://test.mosquitto.org/ws.html">MQTT over websockets</a> (experimental) - from the mosquitto project.</li>
            <li><a href="http://www.hivemq.com/demos/websocket-client/">HiveMQ Websockets Client</a> - a websocket based client for your browser which supports publishing &amp; subscribing.</li>
            <li><a href="https://github.com/jpmens/mqtt-svg-dash">mqtt-svg-dash</a> - SVG "live" dashboard from MQTT.</li>
            <li><a href="https://github.com/fabaff/mqtt-panel">mqtt-panel</a> - a web interface for MQTT.</li>
            <li><a href="http://www.thingstud.io">ThingStudio</a> - ThingStudio allows you create real-time HTML5 user interfaces for MQTT devices by writing simple HTML templates.</li>
            <li><a href="https://github.com/andsel/moquette">Moquette</a> - an open source JAVA broker for MQTT protocol.</li>
            <li><a href="http://mqttlab.iotsim.io">IOTSIM.IO</a> - SaaS MQTT lab for web-based MQTT testing.</li>
            <li><a href="http://tools.emqx.io">MQTT WebSocket Toolkit</a> - MQTT WebSocket Toolkit adopts the form of chat interface, simplifies the page operation logic, and facilitates users to test and verify MQTT application scenarios quickly.</li>
            <li><a href="https://testclient-cloud.mqtt.cool/">MQTT.Cool Test Client</a> - A web interface for testing interaction between MQTT.Cool and any MQTT broker.</li>
         </ul>
         <div class="subhead">Mobile platforms</div>
         <ul>
            <li><a href="https://github.com/eclipse/paho.mqtt.android">MQTT on Android</a></li>
            <li><a href="https://github.com/emqx/CocoaMQTT">MQTT on iOS</a></li>
         </ul>
         <div class="subhead">Mobile tools</div>
         <ul>
            <li><a href="https://mymqtt.app">MyMQTT</a> - The simple Message Queuing Telemetry Transport client for Android and iOS</li>
         </ul>
         <div class="subhead">Desktop tools</div>
            <ul>
            <li><a href="https://mqtt-studio.com">MQTT Studio</a> - A practical desktop and web client designed for developers to efficiently create, test, and manage MQTT-based applications, enhancing their development and support workflows.</li>
            <li><a href="https://mqtt-explorer.com">MQTT Explorer</a> - MQTT client to visualize, publish, subscribe, plot topics. Visualizes topics in a topic hierarchy. Intended for service integration, maintenance and refactorings.</li>
            <li><a href="https://github.com/francoisvdm/TT3">TT3</a> - a full featured windows MQTT client application using Paho libs.  Several additional features like performance testing and alerts.</li>
            <li><a href="http://kamilfb.github.io/mqtt-spy/">mqtt-spy</a> - the most advanced open source utility for monitoring activity on MQTT topics; based on the Paho Java client; for details see the <a href="http://kamilfb.github.io/mqtt-spy/">project's home page</a>.</li>
            <li><a href="http://mqttfx.org/">MQTT.fx</a> - MQTT.fx is a MQTT Client written in Java based on Eclipse Paho.</li>
            <li><a href="https://github.com/gambitcomminc/mqtt-stats">mqtt-stats</a> - MQTT Topic Statistics</li>
            <li><a href="https://github.com/emqx/MQTTX">MQTT X</a> - MQTT X is a cross-platform MQTT desktop client open sourced by EMQ, which supports macOS, Linux, and Windows. MQTT X adopts the form of chat interface, which simplifies the page operation, facilitates the user to quickly test the MQTT/MQTTS connection, publish and subscribe to MQTT messages.</li>
            <li><a href="https://github.com/ptma/mqtt-insight">MqttInsight</a> - MqttInsight is an open source cross platform MQTT desktop client. Supports two message views: table and dialogue. And you can use scripts compatible with Node.js to extend message decoding, message forwarding, and other functions.</li>
         </ul>
         <div class="subhead">Command line tools</div>
            <ul>
               <li><a href="http://mosquitto.org">mosquitto_pub/mosquitto_sub</a> - Publish/Subscribe command line clients, provided with the mosquitto package.</li>
               <li><a href="http://kamilfb.github.io/mqtt-spy/">mqtt-spy-daemon</a> - a headless (command-line) version of mqtt-spy; for details see the <a href="http://kamilfb.github.io/mqtt-spy/">project's home page</a>.</li>
               <li><a href="https://github.com/hivemq/mqtt-cli/">MQTT CLI</a> is a useful command line interface for connecting various MQTT clients supporting MQTT 5.0 and 3.1.1 backed by the HiveMQ team.</li>
               <li><a href="https://everything.curl.dev/usingcurl/mqtt">curl</a> - Basic support for publish and subscribe.</li>
               <li><a href="https://nanomq.io">NanoMQ pub/sub</a> - A high performance command-line toolkit for MQTT debugging and benchmarking, provided with nanomq package, backed by EMQ.</li>
               <li><a href="https://github.com/volkanalkilic/ThingsOn.MQTT.Bench">ThingsOn MQTT Bench</a> - ThingsOn MQTT Bench is a simple Cross-platform .NET Core benchmark tool for MQTT brokers. It measures the maximum number of messages that can be sent to the broker in a specified amount of time.</li>
            </ul>
         <div class="subhead">Commercial Applications</div>
         <ul>
            <li><a href="https://www.hivemq.com/hivemq-swarm/">HiveMQ Swarm</a> - provides the distributed simulation environment to successfully test millions of MQTT clients, millions of MQTT messages and hundreds of thousands MQTT topic names.</li>
            <li><a href="https://www.gambitcomm.com/site/mqttsimulator.php">MIMIC MQTT Simulator</a> - Thousands of publishers and/or subscribers for rapid prototyping of IoT Applications, performance testing and tuning of deployments.</li>
            <li><a href="https://www.bevywise.com/iot-simulator/">Bevywise IoT Simulator</a> - IoT Simulator provides complete functional and performance testing tools for the MQTT Platform, Application &amp; Devices Development.</li>
            <li><a href="http://www-01.ibm.com/support/docview.wss?rs=171&amp;uid=swg24006006&amp;loc=en_US&amp;cs=utf-8&amp;lang=en">IA92</a> - IA92 support pack includes very useful MQTT Java swing GUI for publishing &amp; subscribing.</li>
             <li><a href="https://www.ioctrl.com/mqttdesk/">ioctrl -MqttDesk MQTT Client</a> - MqttDesk is a Cross-Platform MQTT desktop Client with an easy &amp; customizable Dashboard, Connections &amp; Widgets developed for Makers, Freelancers, Prototypes &amp; Enterprises by ioCtrl.</li>
             <li><a href="https://www.emqx.com/en/products/xmeter">XMeter</a> - Based on open-source Apache JMeter project and mqtt-jmeter plugin, XMeter provides a testing SaaS service to simulate millions of MQTT clients and MQTT messages.</li>            
         </ul>
         <div class="subhead">Desktop notification tools</div>
         <ul>
            <li><a href="https://chemicaloliver.net/technology/2010/08/15/first-steps-using-python-and-mqtt/">Ubuntu desktop notifications</a> using pynotify.</li>
            <li><a href="http://fabian-affolter.ch/blog/zenity-notifications-for-mqtt-messages/">Zenity notifications</a> for MQTT messages.</li>
            <li><a href="http://fabian-affolter.ch/blog/desktop-notifications-for-mqtt-messages/">Desktop notifications</a> for MQTT messages with DBUS.</li>
            <li><a href="http://fabian-affolter.ch/blog/mqtt-and-desktop-notifications/">Desktop notifications</a> with libnotify.</li>
         </ul>
         <div class="subhead">Gateways</div>
         <ul>
            <li><a href="http://xenqtt.sf.net">Xenqtt</a> - includes a client library, mock broker for unit/integration testing, and applications to support enterprise needs like using a cluster of servers as a single client, an HTTP gateway, etc.</li>
            <li><a href="https://github.com/jpmens/twitter2mqtt">twitter2mqtt</a> - a Twitter to MQTT gateway (1-shot) which is using mosquitto.</li>
            <li><a href="https://github.com/Lenka42/mqtt_bridge">mqtt_bridge</a> - retransmit MQTT messages between different brokers.</li>
            <li><a href="https://github.com/njh/mqtt-http-bridge">mqtt-http-bridge</a> - this simple web application provides a bridge between HTTP and MQTT using a RESTish interface.</li>
            <li><a href="https://github.com/knolleary/twitter-to-mqtt">twitter-to-mqtt</a> - A python daemon that uses the Twitter Streaming API to access tweets and republishes them to an MQTT topic.</li>
            <li><a href="https://www.opc-router.com/4_1-mqtt-client-opc-router-plug-in-en/">OPC Router</a> - MQTT Gateway (publisher/subscriber) with various plug-ins</li>
            <li><a href="https://github.com/Koenkk/zigbee2mqtt">zigbee2mqtt</a> - ZigBee gateway that exposes ZigBee certified devices (Philis Hue, Xiaomi Aqara, ...) via mqtt. Commonly used for home automation. <a href="https://www.zigbee2mqtt.io/information/supported_devices.html">list of supported devices</a></li>
            <li><a href="https://mqtt.cool">MQTT.Cool</a> - A web gateway that optimizes any MQTT broker when sending real-time data to web clients with automatic throttling.</li>
            <li><a href="https://neugates.io/">Neuron</a> - An open-source, lightweight IIoT connectivity server that convert industrial protocol to MQTT, SparkPlugB etc.</li>
            <li><a href="https://github.com/BlackZork/mqmgateway">MQM Gateway</a> - An open-source, lightweight C++ bidirectional Modbus RTU/TCP <=> MQTT Gateway with flexible data conversion on the fly</li>
         </ul>
         <div class="subhead">Misc</div>
            <ul>
            <li><a href="http://eclipse.org/paho">Eclipse Paho</a> - provides an Eclipse view which can interact with a broker for testing.</li>
            <li><a href="https://github.com/jpmens/mqtt-watchdir">mqtt-watchdir</a> - recursively watch a directory for modifications and publish file content to an MQTT broker.</li>
            <li><a href="https://github.com/volkanalkilic/Mqtt-File-Uploader">MQTT File Uploader</a> - MQTT File Uploader is a simple Cross-platform .NET Core application that watches local directories for changes and uploads new or modified files to an MQTT broker.</li>
            </ul>
   </div>
   <!-- Tools and Applications Panel -->
   <!-- Plugins to other software Start -->
   <button id="plugins" class="accordion">Plugins to other software</button>
   <div class="panel">
         <div class="subhead">Utility Plugins</div>
         <p>MQTT has been incorporated into various runtimes and frameworks via modules or plugins. The projects listed below therefore depend on additional packages and are not necessarily standalone or for general use. As with the list of clients, some may not provide full support for all of the features of the latest MQTT specification – check with the project in question.</p>
         <ul>
            <li><a href="http://tingenek.wordpress.com/2009/10/14/mqtt-ant-task/">Ant</a> – an Ant task (using the IA92 Java client)</li>
            <li><a href="https://code.google.com/p/moquette-mqtt/">moquette-mqtt</a> – an MQTT plugin for Apache Mina, written in Java</li>
            <li><a href="https://plugins.octoprint.org/plugins/mqtt/">MQTT</a> - An <a href="https://octoprint.org">OctoPrint</a> plugin to add support for subscribing and publishing to MQTT topics.</li>
            <li><a href="https://github.com/dmiller44/mule-module-mqtt">mule-module-mqtt</a> – a Mule ESB Connector</li>
            <li><a href="https://plugins.octoprint.org/plugins/mqttpublish/">OctoPrint-MQTTPublish</a> - An <a href="https://octoprint.org">OctoPrint</a> plugin to add buttons to the navbar to publish messages to an MQTT server.</li>
            <li><a href="https://plugins.octoprint.org/plugins/tasmota_mqtt/">OctoPrint-TasmotaMQTT</a> - An <a href="https://octoprint.org">OctoPrint</a> plugin to control Tasmota devices via the MQTT protocol.</li>
            <li><a href="http://blog.stephen-swann.co.uk/2012/06/tdi-and-mqtt-to-rsmb.html">TDI MQTT</a> – a Tivoli Directory Integrator plugin based on (the deprecated) IA92 SupportPac client</li>
            <li><a href="http://false.ekta.is/2011/06/mqtt-dissector-decoder-for-wireshark/">Wireshark</a> - a partial MQTT dissector/decoder for Wireshark</li>
            <li><a href="https://github.com/Johann-Angeli/wireshark-plugin-mqtt">Wireshark</a> - a full MQTT dissector/decoder for Wireshark</li>
            <li><a href="https://code.google.com/p/zmqtt/">zmqtt</a> – an MQTT module for Zotonic, an Erlang framework</li>
            <li><a href="https://github.com/emqx/mqtt-jmeter">mqtt-jmeter plugin</a> – An open source JMeter plugin for MQTT performance test, widely adopted within IoT platform testing domain.</li>
         </ul>
   </div>
   <!-- End of Plugins Panel -->
   <!-- Devices Start -->
   <button id="devices" class="accordion">Devices aka MQTT-enabled products that are "Things"</button>
   <div class="panel">
         <div class="subhead">MQTT Products that are "Things"</div>
         <p>On the discussion threads we talk about many products that use MQTT. Many of them don't publicly declare it. Others are programmable so are oblivious to MQTT being run on them.
         <br/>
         Here are some companies / devices we know about:
         </p>
         <ul>
            <li><a href="http://www.consert.com">Consert</a> - Toshiba Consert smart grid solutions</li>
            <li><a href="http://www.libelium.com/products/meshlium/">Libelium&gt;Meshlium</a> - Libelium, specifically Meshlium uses MQTT natively to communicate from the field.</li>
            <li><a href="http://www.eurotech.com">Eurotech</a> - SCADA, monitoring, controllers, etc</li>
            <li><a href="http://www.celllabs.com/">Cell Labs</a> - Automated Meter Reading</li>
            <li><a href="http://www.cirrus-link.com">Cirrus Link</a> - Arlen Nipper's company (helped to produce ODB2 GSM/GPS/MQTT dongles for Mobile Devices</li>
            <li><a href="http://www.choral.it">Choral</a> - Choral GPS/GSM tracking module (check which models have MQTT)</li>
            <li><a href="https://www.lindsay.com/lam/en/irrigation/brands/elecsys/our-solutions/monitoring-control-solutions/oil-gas-water/industrial-data-communications/">Elecsys</a> - Elecsys Industrial Communications Gateway and Remote Monitors</li>
            <li><a href="https://www.flukso.net/">Flukso</a> - Fluksometer, an electricity metering device with native MQTT support</li>
            <li><a href="http://raaareware.de/">rAAAreware</a> - MQTT modules for handheld measuring devices, MQTT displays, MQTT remote control</li>
            <li><a href="http://www.remakeelectric.com/">ReMake</a> - ReMake Electric electricity metering systems publish all readings to the on-device MQTT broker.</li>
            <li><a href="http://www.owasys.com">Owasys</a> - The owa11 model is an IP67 asset tracking and telemetry unit reporting location, events and IO information using MQTT</li>
            <li><a href="https://www.umh.app">United Manufacturing Hub</a> - The Open-Source toolkit to build your own reliable and secure Industrial IoT platform (strongly leverages MQTT in the Industrial IoT)</li>
         </ul>
   </div>
</section>
</section>


{% include community-contributions.html %}

<script>
   try {
     const acc = document.getElementsByClassName("accordion");
     for (let i = 0; i < acc.length; i++) {
       acc[i].addEventListener("click", function () {
         this.classList.toggle("active");
         const panel = this.nextElementSibling;
         if (panel.style.maxHeight) {
           panel.style.maxHeight = null;
         } else {
           panel.style.maxHeight = panel.scrollHeight + "px";
         }
       });
     }
   } catch (e) {
     //ignore exception
   }
</script>
