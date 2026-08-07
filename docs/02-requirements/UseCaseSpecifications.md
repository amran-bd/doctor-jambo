# Use Case Specifications

## Purpose

Provide concise specifications for the core use cases.

## Scope

Registration, AI and voice consultations, report explanation, doctor workflows, agents, appointments, notifications, and administration.

## Actors

Patient, doctor, administrator, AI/voice services, notification service, and agent.

## Requirements

| Use case | Primary actor | Success outcome |
| --- | --- | --- |
| Patient registration | Patient | Verified account and consent record created. |
| Patient AI consultation | Patient | Safe, labelled guidance with grounded context or escalation. |
| Voice consultation | Patient | Reviewed transcript and supported response generated. |
| Medical report explanation | Patient | Plain-language explanation and clinician-follow-up advice available. |
| Doctor consultation | Doctor | Consultation context and agreed follow-up recorded. |
| Doctor AI Copilot | Doctor | Reviewable draft is accepted, changed, or rejected by doctor. |
| Health Journey Agent | Agent | Authorised follow-up tasks progress with auditable state. |
| Appointment management | Patient/Doctor | Appointment changes are valid and participants notified. |
| Notification workflow | System | Correct, consent-aware message is delivered or recoverably failed. |
| Admin management | Administrator | Authorised configuration or verification change is audited. |

## Assumptions

Alternate flows, data fields, and service contracts will be refined per use case.

## Constraints

No automated workflow may bypass configured human approval.

## Future considerations

Expand each row into fully dressed use-case specifications.
