# Functional Requirements

## Purpose

Specify observable system behaviours.

## Scope

Patient, doctor, AI, voice, agent, and administrative functions.

## Actors

Patients, doctors, administrators, AI services, and workflow agents.

## Requirements

| ID | Requirement |
| --- | --- |
| FR-PATIENT-001 | The system shall register patients and verify supported contact methods. |
| FR-PATIENT-002 | The system shall let patients manage profiles, consent, appointments, and care history available to them. |
| FR-PATIENT-003 | The system shall let patients submit health questions and receive clearly labelled AI-assisted guidance. |
| FR-DOCTOR-001 | The system shall let approved doctors manage availability, appointments, and consultation context. |
| FR-DOCTOR-002 | The system shall provide a doctor AI copilot that drafts summaries, explanations, and follow-up suggestions for review. |
| FR-AI-001 | The system shall retrieve approved knowledge before generating responses when a grounded answer is required. |
| FR-AI-002 | The system shall show source, limitation, and safety context where appropriate. |
| FR-AI-003 | The system shall route high-risk or uncertain requests to human review or escalation guidance. |
| FR-VOICE-001 | The system shall accept supported spoken input and return transcript confidence. |
| FR-VOICE-002 | The system shall support language detection, translation where approved, and spoken output. |
| FR-AGENT-001 | The system shall execute authorised health-journey workflows with explicit goals, state, and audit events. |
| FR-AGENT-002 | The system shall require human approval for configured clinical or consequential actions. |
| FR-ADMIN-001 | The system shall let authorised administrators manage users, provider verification, policies, and service configuration. |
| FR-ADMIN-002 | The system shall record sensitive administrative actions for audit. |

## Assumptions

Detailed UX flows and clinical policy define the content of each interaction.

## Constraints

AI output is decision support, not autonomous clinical care.

## Future considerations

Additional functions will be versioned with stable IDs and acceptance criteria.
