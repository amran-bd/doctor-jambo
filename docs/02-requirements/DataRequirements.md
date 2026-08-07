# Data Requirements

## Purpose

Define data expectations without designing a physical data model.

## Scope

Identity, consent, provider, appointment, consultation, AI, voice, agent, and audit data.

## Actors

Patients, doctors, administrators, services, and authorised auditors.

## Requirements

- The system shall maintain unique identities, roles, and consent records.
- The system shall separate clinical content, operational metadata, and audit events according to approved access policies.
- The system shall record AI prompts, retrieved-source references, outputs, safety decisions, and approval events at an approved level of detail.
- The system shall record voice transcripts, language/confidence metadata, and user corrections subject to consent and retention policy.
- The system shall support data minimisation, correction, export, retention, and deletion processes as legally applicable.

## Assumptions

Data classification and retention schedules will be approved before production use.

## Constraints

Sensitive health information requires strict access control and jurisdiction-aware handling.

## Future considerations

Adopt approved clinical interoperability standards and de-identification workflows.
