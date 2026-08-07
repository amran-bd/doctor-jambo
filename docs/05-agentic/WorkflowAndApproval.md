# Workflow and Human Approval

Health workflows begin with an explicit trigger and policy. Human approval is mandatory before patient-facing clinical interpretation, medication guidance or changes, external side effects, clinician-record updates, and any configured high-risk action.

```mermaid
flowchart LR
  T[Workflow trigger] --> P[Plan and policy check]
  P --> E[Execute safe steps]
  E --> H{Approval required?}
  H -- Yes --> R[Clinician or authorised reviewer]
  H -- No --> O[Outcome]
  R --> O
```
