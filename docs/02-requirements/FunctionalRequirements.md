# Functional Requirements

## Purpose

Specify observable system behaviours.

## Scope

Patient, doctor, AI, voice, agent, and administrative functions.

## Actors

Patients, doctors, administrators, AI services, and workflow agents.

## Detailed description

This document defines the enterprise healthcare platform baseline for its stated scope. It is read with the SRS and the business foundation, and remains subject to clinical, privacy, security, and operational governance.

## Requirements

| ID | Requirement |
| --- | --- |
| FR-PATIENT-001 | The system shall register patients and verify supported contact methods. |
| FR-PATIENT-002 | The system shall authenticate patients using approved identity and session controls. |
| FR-PATIENT-003 | The system shall let patients manage profile, contact, language, and consent preferences. |
| FR-PATIENT-004 | The system shall let patients create, view, correct, and share permitted health information. |
| FR-PATIENT-005 | The system shall let patients submit health questions and receive clearly labelled AI-assisted guidance. |
| FR-PATIENT-006 | The system shall retain patient conversation history subject to consent, access, and retention policies. |
| FR-PATIENT-007 | The system shall let patients upload supported medical documents and report processing status. |
| FR-PATIENT-008 | The system shall let patients request, confirm, reschedule, and cancel appointments under provider rules. |
| FR-DOCTOR-001 | The system shall let approved doctors manage professional profiles, services, and availability. |
| FR-DOCTOR-002 | The system shall present doctors with authorised patient consultation and history context. |
| FR-DOCTOR-003 | The system shall provide a doctor AI copilot that drafts summaries, explanations, and follow-up suggestions for review. |
| FR-DOCTOR-004 | The system shall let doctors create, edit, approve, and retain consultation summaries and medical notes. |
| FR-AI-001 | The system shall route LLM interactions through approved model, policy, and audit controls. |
| FR-AI-002 | The system shall version prompt templates and associate responses with their effective prompt configuration. |
| FR-AI-003 | The system shall select the minimum authorised patient and session context needed for an AI task. |
| FR-AI-004 | The system shall retrieve approved knowledge before generating responses when a grounded answer is required. |
| FR-AI-005 | The system shall apply access-aware vector search, source ranking, and relevance thresholds. |
| FR-AI-006 | The system shall label generated responses with source, limitation, and safety context where appropriate. |
| FR-AI-007 | The system shall route high-risk or uncertain requests to human review or escalation guidance. |
| FR-VOICE-001 | The system shall accept supported voice input only with appropriate notice and consent. |
| FR-VOICE-002 | The system shall produce speech-to-text transcripts with confidence and correction controls. |
| FR-VOICE-003 | The system shall detect supported languages and provide approved translation where required. |
| FR-VOICE-004 | The system shall render supported text-to-speech output and indicate processing or connection failures. |
| FR-VOICE-005 | The system shall support real-time conversation sessions with observable state and safe fallback. |
| FR-AGENT-001 | The system shall execute a Coordinator Agent that routes approved tasks to specialised agents. |
| FR-AGENT-002 | The system shall execute a Planner Agent that creates reviewable task plans within policy. |
| FR-AGENT-003 | The system shall execute an Executor Agent that performs authorised, scoped workflow actions. |
| FR-AGENT-004 | The system shall execute a Health Journey Agent for auditable follow-up and care-plan support. |
| FR-AGENT-005 | The system shall constrain Symptom, Medication, and Doctor Copilot agents to approved decision-support roles. |
| FR-AGENT-006 | The system shall require human approval for configured clinical or consequential actions. |
| FR-ADMIN-001 | The system shall let authorised administrators manage users, provider verification, policies, and service configuration. |
| FR-ADMIN-002 | The system shall record sensitive administrative actions for audit. |
| FR-ADMIN-003 | The system shall let administrators manage approved knowledge sources, prompt versions, and agent policies. |

## Assumptions

Detailed UX flows and clinical policy define the content of each interaction.

## Constraints

AI output is decision support, not autonomous clinical care.

## Dependencies

This document depends on approved clinical governance, privacy and security policies, and the related requirements in this directory.

## Future enhancements

Additional functions will be versioned with stable IDs and acceptance criteria.
