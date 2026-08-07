# Solution Architecture

## Purpose

Define the principal building blocks and interactions.

## Architecture

An API gateway fronts independently deployable domain services. PostgreSQL is owned per service; Redis supports short-lived cache and session-adjacent needs; Kafka transports durable domain events. AI, RAG, voice, and agent services are policy-controlled platform capabilities. Kubernetes provides cloud-native runtime isolation and scaling.

## Requirements

- Services shall expose versioned APIs and publish contract-owned events.
- No service shall directly write another service's transactional data.
- Clinical decisions remain with authorised clinicians; AI outputs are labelled decision support.
- Cross-cutting identity, audit, privacy, and observability controls apply to every service.

## Dependencies and future enhancements

Depends on ADRs, bounded-context ownership, and platform operations. Future detailed designs define SLOs, schemas, and API contracts.
