# Agent Platform Architecture

Spring AI integrates model and tool capabilities; LangChain4j supports agent abstractions and Embabel supports structured orchestration where approved. A policy-controlled agent service owns lifecycle and workflow state. MCP provides typed, scoped tools behind a gateway; business services remain authoritative.

```mermaid
flowchart LR
  U[Patient or Doctor] --> C[Coordinator Agent]
  C --> P[Planner Agent]
  P --> E[Executor and specialist agents]
  E --> M[MCP policy gateway]
  M --> T[Approved tools and services]
  E --> H{Human approval}
  H --> A[Audited outcome]
```
