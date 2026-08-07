# Traceability Matrix

## Purpose

Link business outcomes to system requirements and verification evidence.

## Scope

Initial Milestone 1 business objectives and Milestone 2 requirements.

## Actors

Product, engineering, QA, clinical governance, security, and operations.

## Detailed description

This document defines the enterprise healthcare platform baseline for its stated scope. It is read with the SRS and the business foundation, and remains subject to clinical, privacy, security, and operational governance.

## Requirements

| BRD requirement | SRS requirement | Future service / module | Verification artefact |
| --- | --- | --- | --- |
| Improve access | FR-PATIENT-001 through FR-PATIENT-008 | Identity, Patient Profile, Appointment modules | Registration and consultation acceptance tests |
| Build trust | FR-DOCTOR-001, FR-ADMIN-001, Security Requirements | Provider, IAM, Audit modules | Provider verification and audit tests |
| Support continuity | FR-DOCTOR-002 through FR-DOCTOR-004, FR-AGENT-004 | Consultation, Copilot, Health Journey modules | Copilot review and journey-workflow tests |
| Reduce administration | FR-ADMIN-002, appointment and notification use cases | Administration, Scheduling, Notification modules | Workflow and delivery tests |
| Operate responsibly | FR-AI-001 through FR-AI-007, FR-AGENT-006, NFRs | AI Gateway, RAG, Policy, Agent Orchestrator modules | Safety, privacy, and approval evidence |

## Assumptions

Backlog items, tests, and releases will retain requirement IDs.

## Constraints

Traceability does not replace clinical, legal, or security approval.

## Dependencies

This document depends on approved clinical governance, privacy and security policies, and the related requirements in this directory.

## Future enhancements

Maintain this matrix automatically from requirement, test, and delivery tools.
