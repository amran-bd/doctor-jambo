# Service Architecture

```mermaid
flowchart LR
  G[API Gateway] --> A[Auth]
  G --> P[Patient]
  G --> D[Doctor]
  G --> C[Consultation]
  G --> AP[Appointment]
  C --> MR[Medical Record]
  C --> AI[AI]
  AI --> R[RAG]
  AI --> AG[Agent]
  AP --> N[Notification]
  A --> AU[Audit]
  P & D & C & AP & MR & AI & R & AG & N --> K[(Kafka)]
```

All services own a PostgreSQL datastore or explicitly owned operational store. Kafka events propagate completed domain facts. Hexagonal ports isolate REST, Kafka, persistence, and external adapters.
