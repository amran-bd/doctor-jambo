# Security Requirements

## Purpose

Set security requirements for protecting users, health information, and platform operations.

## Scope

Applications, APIs, data, AI tools, agents, integrations, and operations.

## Actors

Users, administrators, security teams, services, and auditors.

## Requirements

- Strong authentication and role-based, least-privilege authorisation shall protect sensitive actions.
- Sensitive data shall be encrypted in transit and at rest using approved controls.
- The system shall audit access to health information, consent changes, AI approvals, and privileged administration.
- Secrets shall not be embedded in application code or prompts and shall use approved lifecycle management.
- AI and agent tool access shall be constrained by allowlists, scopes, validation, and monitoring.
- The system shall support security incident detection, response, and evidence retention.

## Assumptions

Threat modelling and security review are part of delivery.

## Constraints

Security controls must meet applicable healthcare and privacy obligations.

## Future considerations

Introduce continuous control monitoring and advanced anomaly detection.
