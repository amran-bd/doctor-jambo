# Acceptance Criteria

## Purpose

Define minimum evidence that a requirement is ready for acceptance.

## Scope

Functional, safety, privacy, AI, voice, and agent behaviours.

## Actors

Product owners, QA, clinicians, security reviewers, and operations teams.

## Requirements

- **Patient registration:** Given valid required details, when a patient completes verification, then an account is created and the event is audited.
- **AI consultation:** Given a supported question, when the patient submits it, then the response identifies AI assistance, applies safety checks, and provides escalation guidance when triggered.
- **Voice consultation:** Given supported speech, when the patient speaks, then the system presents a transcript, confidence status, and a way to correct it before consequential use.
- **Report explanation:** Given an approved report input, when explanation is requested, then the system provides plain-language information and advises clinician follow-up rather than diagnosis.
- **Doctor copilot:** Given consultation context, when a draft is generated, then the doctor can review, edit, approve, or reject it before it is shared.
- **Agent workflow:** Given a configured goal, when an agent runs, then its inputs, actions, approvals, outcomes, and failures are auditable.

## Assumptions

Test data and approved safety scenarios are available.

## Constraints

Acceptance cannot waive legal, privacy, or clinical-governance review.

## Future considerations

Automate acceptance evidence in delivery pipelines.
