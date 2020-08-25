---
title: Software
index: 3
description: A collection of links to all important MQTT brokers/servers, MQTT client libaries, tools and plugins.
---

<section class="content-floating">
<h1>MQTT Software</h1>

<section class="accordion-wrapper software" style="margin-bottom: 50px;">
   <button class="accordion">Servers / Brokers</button>
   <div class="panel">
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mqtt.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://theakiro.com/"><h3>Akiro by Sentienz</h3></a>
            Akiro MQTT Broker by <a href="https://sentienz.com/">Sentienz</a> is a high scale MQTT broker and needs a 10 node cluster for 10 Million active MQTT connections. It's written in Java with Vert.X's async paradigm.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/activemq.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="http://activemq.apache.org/index.html"><h3>Apache ActiveMQ</h3></a>
            Details of “classic” ActiveMQ’s support for MQTT are available <a href="http://activemq.apache.org/mqtt.html">here</a>.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/activemq.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="http://activemq.apache.org/artemis/"><h3>Apache ActiveMQ Artemis</h3></a>
            The “next generation” of ActiveMQ, Artemis is a multi protocol messaging broker that supports MQTT.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mqtt-route.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://www.bevywise.com/mqtt-broker/"><h3>Bevywise MQTT Broker</h3></a>
         MQTTRoute is a high performance broker.  The Secure MQTT Broker is written in C &amp; Python and works with all standard MQTT Clients. Bevywise MQTT Broker has a FREE and affordable premium version. MQTTRoute can be customized to write data to any data store using <a href="https://github.com/bevywise-networks/">standard connectors</a> or custom implementations. Try the <a href="http://mqttroute.com/">publicly hosted MQTTRoute</a>.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mqtt.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://github.com/mtsoleimani/cassandana/"><h3>Cassandana</h3></a>
         Cassandana is an open source MQTT message broker which is entirely written in Java. This project began its life as a fork of <a href="https://github.com/andsel/moquette">Moquette</a> , and later underwent some cleanup, optimization and adding extra features. Now it’s ready to work as an enterprise message broker.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/ejabberd.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://www.process-one.net/en/ejabberd"><h3>ejabberd</h3></a>
            ejabberd is an open-source MQTT broker written in Erlang and supported by ProcessOne. ejabberd introduced MQTT 5.0 broker services on top of its renowned XMPP server starting with <a href="https://www.process-one.net/blog/ejabberd-19-02-the-mqtt-edition/">version 19.02</a> through <code>mod_mqtt</code>. It relies on ejabberd infrastructure code that has been battle tested for 15+ years, like the clustering engine. ejabberd MQTT broker has been verified on large scale systems and can support millions of concurrent connections highly efficiently.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/emitter.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://emitter.io"><h3>Emitter</h3></a>
           Emitter is clustered and open-source MQTT broker, written entirely in Go. It proposes several additional features on top of a traditional MQTT broker, as it includes custom per-topic security and shared-nothing scalable architecture which helps you avoid single points of failure. Full source-code available on <a href="https://github.com/emitter-io/emitter">GitHub</a>.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/emq.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://www.emqx.io/products/broker"><h3>EMQ X</h3></a>
            EMQ X MQTT Broker is a fully open source, highly scalable, highly available distributed MQTT messaging broker for IoT, M2M and Mobile applications that can handle tens of millions of concurrent clients.<br/>
            Starting from 3.0 release, EMQ X broker fully supports MQTT V5.0 protocol specifications and backward compatible with MQTT V3.1 and V3.1.1, as well as other communication protocols such as MQTT-SN, CoAP, LwM2M, WebSocket and STOMP. The 3.0 release of the EMQ X broker can scaled to 10+ million concurrent MQTT connections on one cluster.
            <a href="https://twitter.com/emqtt">@emqtt</a>
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mqtt.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://github.com/alekras/erl.mqtt.server"><h3>Erl.mqtt.server</h3></a>
         erl.mqtt.server MQTT server is designed for communication in Machine to Machine (M2M) and Internet of Things (IoT) contexts and implements MQTT protocol versions 3.1 and 3.1.1. The server is written in Erlang as OTP application.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/everywhere-cloud.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://www.eurotech.com/en/products/iot/iot-integration-platform/everyware-cloud"><h3>Eurotech Everywhere Cloud</h3></a>
         Eurotech Everywhere Device Cloud is a cloud-based service provided by <a href="http://www.eurotech.com">Eurotech</a>.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/flespi.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://flespi.com/mqtt-broker"><h3>flespi</h3></a>
         flespi is a public and free cloud-based MQTT broker service with declared 3.1, 3.1.1, 5.0 protocols compliance. High-volume targeted architecture, isolated MQTT namespace, WebSockets/SSL support, configurable ACL, commercial and free SLA, managed by <a href="https://flespi.io/mqtt">HTTP REST API</a>.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mqtt.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://github.com/beerfactory/hbmqtt"><h3>HBMQTT</h3></a>
            HBMQTT is an open-source implementation of MQTT broker and client. It uses Python 3.4+ asyncio library for providing a mono-threaded, non-blocking implementation of the protocol.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/hivemq.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://www.hivemq.com"><h3>HiveMQ</h3></a>
         HiveMQ is a MQTT broker which was built from the ground up with maximum scalability and enterprise-ready security in mind. It comes with native web socket support and an open source plugin SDK to extend its functionality or integrate it with other components. A public test server is also available (<a href="https://github.com/mqtt/mqtt.github.io/wiki/public_brokers">more information</a>).
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/jmqtt.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://github.com/Cicizz/jmqtt"><h3>Jmqtt</h3></a>
            Jmqtt is a MQTT broker which implemented by java and netty,support persistence and cluster.
         </div>
      </div>
      <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/ibm.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://www.ibm.com/cloud/app-connect"><h3>IBM Integration Bus</h3></a>
         IBM Integration Bus V9 has Telemetry feature built-in as optional licensed feature. IBM WebSphere MessageBroker V7 &amp; V8 also include it as optionally licensed feature. <a href="https://www.ibm.com/support/knowledgecenter/SSFKSJ_7.5.0/com.ibm.mm.tc.doc/tc00100_.htm">Really Small Message Broker</a> 75KB MQTT broker runtime free download as binaries from IBM alphaWorks, RSMB is a C implementation of a tiny MQTT server suitable for development, embedded systems, concentrators or small to medium sized deployments. It provides complete MQTT v3.1 support, bridging, and a C client API.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/ibm.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://www.ibm.com/us-en/marketplace/watson-iot-platform-message-gateway"><h3>IBM WIoTP Message Gateway</h3></a>
            IBM WIoTP Message Gateway is a scalable, hightly available messaging broker for MQTT (including MQTT v5, HTML5 WebSockets, JMS. Also connects/bridges IBM MQ, IBM Integration Bus. (Was formerly called IBM IoT MessageSight).
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/ibm.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://www.ibm.com/support/knowledgecenter/en/SSFKSJ_7.5.0/com.ibm.mq.pro.doc/q001030_.htm"><h3>IBM Websphere MQ Telemetry</h3></a>
         WebSphere MQ version 7.1 and above. It provides full MQTT v3.1 support, IBM MQ and JMS support. IBM WebSphere MQ Advanced includes the MQTT license at no charge. It ships with reference Java (MIDP and above), C and JavaScript (MQTT over WebSocket) clients.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mqtt.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="http://mqtt.jorammq.com"><h3>JoramMQ</h3></a>
            JoramMQ is an offering by ScalAgent providing a message broker that fully supports MQTT 3.1, JMS 2.0, and AMQP 1.0. Interoperability between these standards is ensured by the message broker. MQTT can be used over TCP/IP, TLS (SSL), WebSocket, and secure WebSocket. JoramMQ is particularly appropriate for applications that need to scale with the number of MQTT clients while allowing the publishers to reliably transmit a large volume of messages with a low latency
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/litmus.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="http://litmusautomation.com/"><h3>Litmus Automation Loop</h3></a>
         Loop is a cloud based MQTT broker with scalability, high availability and security at core. Loop provides full MQTT 3.1 support and JMS connectivity. It can handle extremely large numbers of connected clients. On the other side it can be connected to any ERP, CRM and enterprise architecture with ESB or NoSQL databases for blazing fast data storage.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mqtt.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://github.com/andsel/moquette"><h3>Moquette</h3></a>
         Moquette is a Java MQTT broker based on an eventing model with Netty.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mosca.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://github.com/mcollina/mosca"><h3>Mosca</h3></a>
         As node.js MQTT broker can Mosca be plugged on top of Redis, AMQP, MQTT, or ZeroMQ.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mosquitto.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://www.mosquitto.org"><h3>Mosquitto</h3></a>
            Mosquitto is an Open Source MQTT server. A public, hosted test server is also available (more information)
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/myqtthub.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://myqtthub.com/"><h3>MyQttHub.com</h3></a>
            Mosquitto is an Open Source MQTT server. A public, hosted test server is also available (more information).
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mqttnet.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://github.com/chkr1011/MQTTnet/"><h3>MQTTnet</h3></a>
         MQTTnet is a .NET library for MQTT based communication. It provides a MQTT client and a MQTT server (broker).
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mqtt.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://github.com/Wizzercn/MqttWk"><h3>MqttWk</h3></a>
            MqttWk is a Java MQTT broker based on NutzBoot + Netty + Redis + Kafka(Optional).The broker supports QoS 0, QoS 1 and QoS 2.It uses Netty for the protocol encoding and decoding part.Using NutzBoot to provide dependency injection and attribute configuration, using Redis to implement message caching and clustering, and using Kafka to implement message proxy.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/rabbitmq.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="http://rabbitmq.com/"><h3>RabbitMQ</h3></a>
         RabbitMQ is an AMQP message broker – with an <a href="http://www.rabbitmq.com/blog/2012/09/12/mqtt-adapter/">MQTT plugin</a> (bundled in version 3.x onwards). A public test server is also available (<a href="https://github.com/mqtt/mqtt.github.io/wiki/public_brokers">more information</a>).
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/solace.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="http://dev.solacesystems.com/tech/"><h3>Solace</h3></a>
         Solace Message Routers (available as hardware and software) are message brokers that support MQTT, JMS, and REST among other APIs, protocols and qualities of service for enterprise messaging, data collection and web/mobile streaming. They support very high connection counts and throughput with built-in buffering to handle bursty traffic, and offer enterprise-class monitoring, high availability and security.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/swiftmq.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="http://www.swiftmq.com/landing/router/index.html"><h3>SwiftMQ</h3></a>
         SwiftMQ Universal Router is an enterprise message system with integrated micro services and realtime streaming analytics platform (SwiftMQ Streams, SwiftMQ Dashboard). It supports MQTT 3.1/3.1.1, AMQP 1.0/0.9.1, JMS 1.1 and is fully interoperable between these protocols. It has a built-in Dynamic Routing Architecture to build large Federated Router Networks and Clusters. SwiftMQ High Availability Router is the High and Continuous Availability version of SwiftMQ Universal Router with active replication and transparent client failover.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/thingscale.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="http://thingscale.io/index_en.html"><h3>ThingScale IoT message broker</h3></a>
         ThingScale IoT message broker</a> is a fully-managed IoT messaging service provided by <a href="http://sensinics.co.jp">Sensinics,LLC</a>.<br/>
         ThingScale provides a messaging system for IoT connected devices. The API is used to retrieve events, users, devices, sessions, and channels in JSON format. ThingScale supports TLS payload encryption, scheme-less and cyclic data sampling, and trigger-based notifications. A 30days trial license is offered free of charge. MQTT is the preferred messaging protocol. <a href="https://sensinics.atlassian.net/wiki/spaces/TD/pages/76021778/Developer+Portal">Dev Portal</a> &amp; <a href="https://thingscale.docs.apiary.io/">API Portal</a>
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/vernemq.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="http://verne.mq/"><h3>VerneMQ</h3></a>
         VerneMQ is an enterprise ready, high-performance, distributed MQTT message broker. It scales horizontally and vertically on commodity hardware to support a high number of concurrent publishers and consumers while maintaining low and predictable latency and fault tolerance. VerneMQ plugins can be developed in Erlang, Elixir, Lua, and any programming language that can implement HTTP WebHooks. VerneMQ uses modern broadcast protocols and LevelDB for state replication in a cluster. VerneMQ is Open Source and Apache2 licensed.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item">
         <img src="{{ 'assets/img/software/mqtt.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="https://github.com/GruppoFilippetti/vertx-mqtt-broker"><h3>Vert.x MQTT Broker</h3></a>
        Vert.x MQTT Broker is an open-source implementation of MQTT server. It implements protocol versions 3.1.1 and 3.1, supports QoS 2, and uses OAuth2 for autentication. It uses <a href="http://vertx.io/">vert.x</a> as library for tcp managemnet, non-blocking / actor-model, clustering and auth plugin system.
         </div>
      </div>
   <!-- Entry -->
      <div class="panel-item last">
         <img src="{{ 'assets/img/software/yunba.png' | relative_url }}" class="software-logo">
         <div class="panel-item-description"><a href="http://yunba.io/"><h3>Yunba.io</h3></a>
         Yunba is a backend cloud platform that provides real-time message dispatch service to mobile applications and devices and uses MQTT as a transport protocol, The services include bi-directional push for Instant-Messaging; real-time analyzing; real-time online monitoring.
         </div>
      </div>
   <!-- closing div -->
   </div>
   <!-- End of Broker / Server Panel -->
   <!-- Client Libraries Start -->
   <button class="accordion">Client libraries</button>
   <div class="panel">
      <div class="subhead">Device-Specific</div>
      <ul>
         <li><a href="https://github.com/knolleary/pubsubclient">Arduino</a> (<a href="http://pubsubclient.knolleary.net/">more information</a>)</li>
         <li><a href="https://github.com/tuanpmt/espduino">Espduino</a> (tailored Arduino library for the ESP8266)</li>
         <li><a href="http://mbed.org/users/jwende/code/MQTT/">mbed (simple port of the Arduino pubsubclient)</a></li>
         <li><a href="http://mbed.org/users/Nim65s/code/niMQTT/">mbed (native implementation)</a></li>
         <li><a href="http://developer.mbed.org/teams/mqtt/code/MQTT/">mbed (Paho Embedded C++ port)</a></li>
         <li><a href="http://developer.mbed.org/teams/mqtt/code/MQTTPacket/">mbed (Paho Embedded C port)</a></li>
         <li><a href="http://github.com/njh/NanodeMQTT/">Nanode</a></li>
         <li><a href="https://github.com/danielan/NetduinoMQTT">Netduino</a></li>
         <li><a href="https://github.com/eclipse/paho.mqtt.m2mqtt">M2MQTT (works with .Net Micro Framework)</a></li>
      </ul>
      <div class="subhead">Actionscript</div>
      <ul>
         <li><a href="https://github.com/yangboz/as3MQTT">as3MQTT</a></li>
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
         <li><a href="https://github.com/gausby/tortoise">tortoise</a> - A MQTT Client written in Elixir</li>
      </ul>
      <div class="subhead">Go</div>
      <ul>
         <li><a href="https://github.com/eclipse/paho.mqtt.golang">Eclipse Paho Go</a></li>
         <li><a href="https://github.com/jeffallen/mqtt">mqtt by jeffallen</a></li>
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
         <li><a href="http://git.eclipse.org/c/paho/org.eclipse.paho.mqtt.lua.git/" >Eclipse Paho Lua</a></li>
         <li><a href="https://github.com/xHasKx/luamqtt/">luamqtt - Pure-lua MQTT client</a></li>
         <li><a href="https://github.com/zhaojh329/libumqtt">libumqtt</a></li>
         <li><a href="https://luarocks.org/modules/karlp/lua-mosquitto" >lua-mosquitto</a></li>
      </ul>
      <div class="subhead">.NET / dotNET</div>
      <ul>
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
         <li><a href="http://github.com/bluerhinos/phpMQTT">phpMQTT</a></li>
         <li><a href="https://github.com/mgdm/Mosquitto-PHP">Mosquitto-PHP</a></li>
         <li><a href="http://github.com/sskaje/mqtt">sskaje's MQTT library</a></li>
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
      </ul>
      <div class="subhead">Tcl</div>
      <ul>
         <li><a href="https://github.com/Tingenek/tcl-mqtt">tcl-mqtt</a></li>
      </ul>
   </div>
   <!-- End of Client Libraries Panel -->
   <!-- Tools and Applications Start -->
   <button class="accordion">Tools and Applications</button>
   <div class="panel">
      <div class="subhead">Web</div>
         <ul>
            <li><a href="https://mqttboard.flespi.io">MQTT Board</a> - diagnostic oriented MQTT 5.0 client tool based on <a href="https://github.com/mqttjs">mqtt.js</a>. Available in <a href="https://github.com/flespi-software/mqtt-board">open source</a>.</li>
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
         <div class="subhead">Desktop tools</div>
            <ul>
            <li><a href="https://mqtt-explorer.com">MQTT Explorer</a> - MQTT client to visualize, publish, subscribe, plot topics. Visualizes topics in a topic hierarchy. Intended for service integration, maintenance and refactorings.</li>
            <li><a href="https://github.com/francoisvdm/TT3">TT3</a> - a full featured windows MQTT client application using Paho libs.  Several additional features like performance testing and alerts.</li>
            <li><a href="http://kamilfb.github.io/mqtt-spy/">mqtt-spy</a> - the most advanced open source utility for monitoring activity on MQTT topics; based on the Paho Java client; for details see the <a href="http://kamilfb.github.io/mqtt-spy/">project's home page</a>.</li>
            <li><a href="http://mqttfx.org/">MQTT.fx</a> - MQTT.fx is a MQTT Client written in Java based on Eclipse Paho.</li>
            <li><a href="https://github.com/gambitcomminc/mqtt-stats">mqtt-stats</a> - MQTT Topic Statistics</li>
            <li><a href="https://github.com/emqx/MQTTX">MQTT X</a> - MQTT X is a cross-platform MQTT desktop client open sourced by EMQ, which supports macOS, Linux, and Windows. MQTT X adopts the form of chat interface, which simplifies the page operation, facilitates the user to quickly test the MQTT/MQTTS connection, publish and subscribe to MQTT messages.</li>
         </ul>
         <div class="subhead">Command line tools</div>
            <ul>
               <li><a href="http://mosquitto.org">mosquitto_pub/mosquitto_sub</a> - Publish/Subscribe command line clients, provided with the mosquitto package.</li>
               <li><a href="http://kamilfb.github.io/mqtt-spy/">mqtt-spy-daemon</a> - a headless (command-line) version of mqtt-spy; for details see the <a href="http://kamilfb.github.io/mqtt-spy/">project's home page</a>.</li>
               <li><a href="https://github.com/hivemq/mqtt-cli/">MQTT CLI</a> is a useful command line interface for connecting various MQTT clients supporting MQTT 5.0 and 3.1.1 backed by the HiveMQ team.</li>  
            </ul>
         <div class="subhead">Commercial Applications</div>
         <ul>
            <li><a href="https://www.gambitcomm.com/site/mqttsimulator.php">MIMIC MQTT Simulator</a> - Thousands of publishers and/or subscribers for rapid prototyping of IoT Applications, performance testing and tuning of deployments.</li>
            <li><a href="https://www.bevywise.com/iot-simulator/">Bevywise IoT Simulator</a> - IoT Simulator provides complete functional and performance testing tools for the MQTT Platform, Application &amp; Devices Development.</li>
            <li><a href="http://www-01.ibm.com/support/docview.wss?rs=171&amp;uid=swg24006006&amp;loc=en_US&amp;cs=utf-8&amp;lang=en">IA92</a> - IA92 support pack includes very useful MQTT Java swing GUI for publishing &amp; subscribing.</li>
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
            <li><a href="https://github.com/njh/mqtt-http-bridge">mqtt-http-bridge</a> - this simple web application provides a bridge between HTTP and MQTT using a RESTish interface.</li>
            <li><a href="https://github.com/knolleary/twitter-to-mqtt">twitter-to-mqtt</a> - A python daemon that uses the Twitter Streaming API to access tweets and republishes them to an MQTT topic.</li>
            <li><a href="https://www.opc-router.com/4_1-mqtt-client-opc-router-plug-in-en/">OPC Router</a> - MQTT Gateway (publisher/subscriber) with various plug-ins</li>
            <li><a href="https://github.com/Koenkk/zigbee2mqtt">zigbee2mqtt</a> - ZigBee gateway that exposes ZigBee certified devices (Philis Hue, Xiaomi Aqara, ...) via mqtt. Commonly used for home automation. <a href="https://www.zigbee2mqtt.io/information/supported_devices.html">list of supported devices</a></li>
            <li><a href="https://mqtt.cool">MQTT.Cool</a> - A web gateway that optimizes any MQTT broker when sending real-time data to web clients with automatic throttling.</li>
         </ul>
         <div class="subhead">Misc</div>
            <ul>
            <li><a href="http://eclipse.org/paho">Eclipse Paho</a> - provides an Eclipse view which can interact with a broker for testing.</li>
            <li><a href="https://github.com/jpmens/mqtt-watchdir">mqtt-watchdir</a> - recursively watch a directory for modifications and publish file content to an MQTT broker.</li>
            <li><a href="https://bitbucket.org/oojah/mqttfs">mqttfs</a> - mqttfs allows you to mount a directory as effectively a link to an MQTT topic hierarchy on an MQTT server.</li>
            </ul>
   </div>
   <!-- Tools and Applications Panel -->
   <!-- Plugins to other software Start -->
   <button class="accordion">Plugins to other software</button>
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
         </ul>
   </div>
   <!-- End of Plugins Panel -->
   <!-- Devices Start -->
   <button class="accordion">Devices aka MQTT-enabled products that are "Things"</button>
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
            <li><a href="http://www.remakeelectric.com/">ReMake</a> - ReMake Electric electricity metering systems publish all readings to the on-device MQTT broker.</li>
            <li><a href="http://www.owasys.com">Owasys</a> - The owa11 model is an IP67 asset tracking and telemetry unit reporting location, events and IO information using MQTT</li>
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

