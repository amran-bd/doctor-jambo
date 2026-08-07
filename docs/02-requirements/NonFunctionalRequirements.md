# Non-Functional Requirements

## Purpose

Set quality attributes and operational expectations.

## Scope

All user-facing services, AI services, integrations, and operations.

## Actors

Patients, doctors, administrators, operations, security, and engineering teams.

## Requirements

| Area | Requirement |
| --- | --- |
| Performance | Core interactive requests shall meet approved latency targets; AI and voice workflows shall disclose processing state. |
| Scalability | Services shall scale independently for demand peaks and asynchronous workloads. |
| Availability | Critical patient, appointment, and safety functions shall meet an approved service-availability objective. |
| Security | Sensitive data shall use strong authentication, least privilege, encryption, and audited access. |
| Privacy | Data collection and use shall be purpose-limited, consent-aware, and support approved retention controls. |
| Reliability | Workflows shall be idempotent where retries are possible and expose recoverable failure states. |
| Maintainability | Components shall have documented interfaces, automated tests, and versioned configuration. |
| Observability | Logs, metrics, traces, alerts, and AI/agent audit events shall support safe operations. |

## Assumptions

Quantified SLOs, RPOs, and RTOs will be approved with operations and governance teams.

## Constraints

Health-data handling and vendor limits may affect latency and regional availability.

## Future considerations

Quality targets will be refined per service and market.
