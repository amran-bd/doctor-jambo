# Event-Driven Architecture

Kafka carries immutable, versioned business events such as `ConsultationCompleted`, `RecordUpdated`, `KnowledgeIndexed`, and `NotificationDelivered`. Producers use an outbox pattern; consumers are idempotent, observable, and able to retry or dead-letter failures. Events communicate facts, not remote commands disguised as events.
