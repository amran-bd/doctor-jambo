# Agent Lifecycle

An agent is registered with an owner, goal, permitted data, tools, event contracts, budget, and termination conditions. It receives a validated trigger, builds or receives a plan, executes scoped steps, awaits approval where required, records outcome, and terminates or compensates safely.

```mermaid
flowchart LR
  R[Registered] --> T[Triggered]
  T --> P[Planned]
  P --> X[Executing]
  X --> H{Approval?}
  H --> O[Completed or compensated]
  O --> A[Audited and terminated]
```
