# Communication and Package Structure

Synchronous REST APIs are versioned and used for immediate commands or queries; Kafka transports durable, asynchronous domain events. Consumers are idempotent, correlated, observable, and retry/dead-letter capable.

```mermaid
flowchart LR
  G[API Gateway] -->|REST| C[Consultation Service]
  C -->|REST| MR[Medical Record Service]
  C -->|REST| AI[AI Service]
  C -->|event| K[Kafka]
  K --> N[Notification Service]
```

```mermaid
flowchart LR
  S[Publisher service] --> O[Outbox]
  O --> K[Kafka]
  K --> C[Idempotent consumer]
  C --> D[Local domain model]
```

```mermaid
flowchart TB
  B[service-name]
  B --> D[domain: aggregates, events, ports]
  B --> A[application: commands, queries, use cases]
  B --> I[infrastructure: persistence, Kafka, external adapters]
  B --> X[interfaces: REST, messaging, configuration]
```
