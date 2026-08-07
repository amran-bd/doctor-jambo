# Use Case Model

## Purpose

Identify primary actor interactions with the system.

## Scope

The ten core use cases for the first product roadmap.

## Actors

Patient, doctor, administrator, AI service, voice service, and health journey agent.

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

## Future considerations

Extend the model for caregiver delegation and partner systems.
