---
title: Why MQTT
index: 0
description: Learn why technical leaders and CTOs choose MQTT as the standard for scalable, reliable IoT and event-driven architectures.
layout: default
---

<style>
  :root {
    --text-primary: #111111;
    --text-secondary: #555555;
    --text-muted: #888888;
    --border-color: #e5e5e5;
    --bg-color: #ffffff;
    --accent-color: #222222;
  }

  .minimal-wrapper {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    color: var(--text-primary);
    background: var(--bg-color);
    line-height: 1.7;
    margin: 0;
    padding: 0;
  }

  .minimal-container {
    max-width: 900px;
    margin: 0 auto;
    padding: 60px 20px;
  }

  .minimal-container h1, .minimal-container h2, .minimal-container h3 {
    color: var(--text-primary);
    margin-top: 0;
  }

  .minimal-container p {
    color: var(--text-secondary);
  }

  .minimal-header {
    margin-bottom: 60px;
    border-bottom: 1px solid var(--border-color);
    padding-bottom: 40px;
  }

  .minimal-header h1 {
    font-size: 3rem;
    font-weight: 600;
    letter-spacing: -0.02em;
    margin-bottom: 1rem;
    line-height: 1.1;
  }

  .minimal-header p {
    font-size: 1.25rem;
    font-weight: 300;
    max-width: 700px;
  }

  .minimal-section {
    margin-bottom: 60px;
  }

  .minimal-section h2 {
    font-size: 1.5rem;
    font-weight: 500;
    border-bottom: 1px solid var(--border-color);
    padding-bottom: 15px;
    margin-bottom: 30px;
  }
  
  .principle-block {
    margin-bottom: 40px;
    padding-left: 20px;
    border-left: 2px solid var(--border-color);
  }

  .principle-block h3 {
    font-size: 1.15rem;
    font-weight: 600;
    margin-bottom: 8px;
  }

  .principle-block p {
    margin-bottom: 0;
    max-width: 800px;
  }

  .minimal-table-wrapper {
    overflow-x: auto;
    border: 1px solid var(--border-color);
  }

  .minimal-table {
    width: 100%;
    border-collapse: collapse;
    text-align: left;
    font-size: 0.95rem;
    min-width: 800px;
  }

  .minimal-table th {
    background: #fafafa;
    padding: 20px;
    font-weight: 500;
    color: var(--text-primary);
    border-bottom: 1px solid var(--border-color);
  }

  .minimal-table td {
    padding: 20px;
    color: var(--text-secondary);
    border-bottom: 1px solid var(--border-color);
    vertical-align: top;
  }

  .minimal-table tr:last-child td {
    border-bottom: none;
  }

  .minimal-table .row-header {
    font-weight: 600;
    color: var(--text-primary);
  }

  .minimal-table .mqtt-highlight {
    background-color: #f7f7f8;
    color: var(--text-primary);
    font-weight: 500;
  }
  
  .minimal-table th.mqtt-highlight {
    background-color: #eeeeea;
    font-weight: 600;
  }

  .business-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 24px;
    margin-top: 30px;
  }

  .business-card {
    border: 1px solid var(--border-color);
    padding: 30px;
    display: flex;
    flex-direction: column;
    background: var(--bg-color);
  }

  .business-card h3 {
    font-size: 1.15rem;
    font-weight: 600;
    margin-bottom: 12px;
    line-height: 1.4;
  }

  .business-card p {
    font-size: 0.95rem;
    color: var(--text-secondary);
    margin-bottom: 24px;
    flex-grow: 1;
    line-height: 1.6;
  }

  .proof-point {
    font-size: 0.85rem;
    font-weight: 600;
    color: var(--text-primary);
    border-top: 1px solid var(--border-color);
    padding-top: 16px;
    margin-top: auto;
    text-transform: uppercase;
    letter-spacing: 0.05em;
  }
  .use-case-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 16px;
  }

  .use-case-link {
    display: inline-block;
    padding: 12px 24px;
    border: 1px solid var(--border-color);
    color: var(--text-primary);
    text-decoration: none;
    font-weight: 500;
    transition: all 0.2s ease;
    background: var(--bg-color);
  }

  .use-case-link:hover {
    border-color: var(--text-primary);
    background: #f9f9f9;
    color: var(--text-primary);
  }
</style>

<div class="content-floating">
  <div class="minimal-wrapper">
    <div class="minimal-container">
      <header class="minimal-header">
        <h1>Architecting for Scale</h1>
        <p>Why modern event-driven architectures rely on MQTT for decoupled system design and guaranteed delivery.</p>
      </header>

      <section class="minimal-section">
        <h2>Why MQTT for your Business</h2>
        
        <div class="business-grid">
          <div class="business-card">
            <h3>Built to survive the real world</h3>
            <p>Engineered for unreliable networks and constrained edge environments. It reliably delivers data or buffers it until connectivity is restored.</p>
            <div class="proof-point">Proven in remote factory floors</div>
          </div>

          <div class="business-card">
            <h3>Scale without rebuilding</h3>
            <p>The exceptionally lightweight architecture natively scales from a ten-device pilot to ten million global production devices without re-engineering.</p>
            <div class="proof-point">Scales linearly to massive fleets</div>
          </div>

          <div class="business-card">
            <h3>Zero vendor lock-in</h3>
            <p>As an open OASIS standard, your core messaging layer remains infrastructure-agnostic, letting you freely migrate workloads between clouds.</p>
            <div class="proof-point">Interoperable across AWS, Azure & GCP</div>
          </div>

          <div class="business-card">
            <h3>Trusted by industry leaders</h3>
            <p>Deployed globally as the mission-critical foundation for the largest, most demanding consumer and enterprise technologies in existence.</p>
            <div class="proof-point">Powers BMW's vehicle fleet & Amazon Alexa</div>
          </div>

          <div class="business-card" style="grid-column: 1 / -1;">
            <h3>Secure enterprise connective tissue</h3>
            <p>Intelligently unifies Operational Technology with IT backend systems, backed by strict end-to-end security models across the full stack.</p>
            <div class="proof-point">The proven bridge for enterprise data lakes</div>
          </div>
        </div>
      </section>

      <section class="minimal-section">
        <h2>Explore Industry Use Cases</h2>
        <p style="margin-bottom: 30px;">Discover how organizations are utilizing MQTT across various sectors to drive operational efficiency and scale.</p>
        
        <div class="use-case-grid">
          <a href="{{ '/use-cases/#automotive' | relative_url }}" class="use-case-link">Automotive &rarr;</a>
          <a href="{{ '/use-cases/#logistics' | relative_url }}" class="use-case-link">Logistics &rarr;</a>
          <a href="{{ '/use-cases/#manufacturing' | relative_url }}" class="use-case-link">Manufacturing &rarr;</a>
          <a href="{{ '/use-cases/#smarthome' | relative_url }}" class="use-case-link">Smart Home &rarr;</a>
          <a href="{{ '/use-cases/#oil-gas' | relative_url }}" class="use-case-link">Energy &rarr;</a>
          <a href="{{ '/use-cases/#consumer-products' | relative_url }}" class="use-case-link">Consumer Products &rarr;</a>
          <a href="{{ '/use-cases/#transportation' | relative_url }}" class="use-case-link">Transportation &rarr;</a>
        </div>
      </section>

      <section class="minimal-section">
        <h2>Why Now?</h2>
        <p style="margin-bottom: 30px;">MQTT is increasingly connecting to enterprise platforms like Apache Kafka and AMQP-based tools like EMQ. It is designed to fit seamlessly into existing enterprise architectures—acting as the edge-to-cloud bridge—rather than replacing your core backend messaging infrastructure.</p>

        <div class="minimal-table-wrapper">
          <table class="minimal-table">
            <thead>
              <tr>
                <th>Characteristic</th>
                <th class="mqtt-highlight">MQTT</th>
                <th>Apache Kafka</th>
                <th>AMQP</th>
                <th>REST / Webhooks</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="row-header">Core Paradigm</td>
                <td class="mqtt-highlight">IoT & Edge Pub/Sub</td>
                <td>Data Streaming / Append Log</td>
                <td>Enterprise Queuing</td>
                <td>Synchronous Request/Response</td>
              </tr>
              <tr>
                <td class="row-header">Target Environment</td>
                <td class="mqtt-highlight">Unreliable networks, constrained edge</td>
                <td>Datacenter to Datacenter, stable networks</td>
                <td>Backend microservices, internal VPCs</td>
                <td>Standard web integrations</td>
              </tr>
              <tr>
                <td class="row-header">Client Footprint</td>
                <td class="mqtt-highlight">Extremely minimal (Microcontroller capable)</td>
                <td>Heavy (JVM or persistent polling required)</td>
                <td>Moderate (Complex channel logic required)</td>
                <td>Heavy (Verbose HTTP payloads)</td>
              </tr>
              <tr>
                <td class="row-header">Connections & Scale</td>
                <td class="mqtt-highlight">Millions of concurrent active clients</td>
                <td>Thousands of partitions/clients</td>
                <td>Tens of thousands of active channels</td>
                <td>Constrained heavily by server thread limits</td>
              </tr>
            </tbody>
          </table>
        </div>
      </section>
    </div>
  </div>
</div>
