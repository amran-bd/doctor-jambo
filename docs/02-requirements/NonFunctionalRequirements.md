# Non-Functional Requirements

## Purpose

Set quality attributes and operational expectations.

## Scope

All user-facing services, AI services, integrations, and operations.

## Actors

Patients, doctors, administrators, operations, security, and engineering teams.

## Detailed description

This document defines the enterprise healthcare platform baseline for its stated scope. It is read with the SRS and the business foundation, and remains subject to clinical, privacy, security, and operational governance.

## Requirements

| Area | Requirement |
| --- | --- |
| Performance | 95% of non-AI API requests shall meet the approved API response target; AI streaming shall provide a first visible response or clear processing status within the approved interaction target. |
| Scalability | Stateless workloads shall support horizontal scaling; event consumers and AI workloads shall scale independently for high-concurrency demand. |
| Availability | Critical patient, appointment, authentication, and safety functions shall meet approved availability and recovery targets. |
| Security | OAuth2/OIDC authentication, JWT session controls, RBAC, encryption, secret management, and audit logging shall protect sensitive functions. |
| Privacy | Patient data collection and processing shall be purpose-limited, consent-aware, access-controlled, and governed by approved retention controls. |
| Reliability | Workflows shall be idempotent where retries are possible, use durable events where required, and expose recoverable failure states. |
| Maintainability | Components shall have documented interfaces, automated tests, and versioned configuration. |
| Observability | Logs, metrics, traces, alerts, and AI/agent audit events shall support safe operations. |

## Assumptions

Quantified SLOs, RPOs, and RTOs will be approved with operations and governance teams.

## Constraints

Health-data handling and vendor limits may affect latency and regional availability.

## Dependencies

This document depends on approved clinical governance, privacy and security policies, and the related requirements in this directory.

## Future enhancements

Quality targets will be refined per service and market.
