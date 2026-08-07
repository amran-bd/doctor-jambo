# Use Case Model

## Purpose

Identify primary actor interactions with the system.

## Scope

The ten core use cases for the first product roadmap.

## Actors

Patient, doctor, administrator, AI service, voice service, and health journey agent.

## Detailed description

This document defines the enterprise healthcare platform baseline for its stated scope. It is read with the SRS and the business foundation, and remains subject to clinical, privacy, security, and operational governance.

## Requirements

```mermaid
flowchart LR
  P[Patient] --> R[Register]
  P --> A[AI consultation]
  P --> V[Voice consultation]
  P --> M[Report explanation]
  P --> B[Appointment management]
  D[Doctor] --> C[Doctor consultation]
  D --> O[Doctor AI Copilot]
  H[Health Journey Agent] --> J[Health journey workflow]
  N[Notification service] --> W[Notification workflow]
  X[Administrator] --> G[Admin management]
  A --> K[RAG knowledge retrieval]
  O --> K
```

## Assumptions

Each use case has an authorised actor and a defined outcome.

## Constraints

Emergency cases require guidance to appropriate emergency channels.

## Dependencies

This document depends on approved clinical governance, privacy and security policies, and the related requirements in this directory.

## Future enhancements

Extend the model for caregiver delegation and partner systems.
