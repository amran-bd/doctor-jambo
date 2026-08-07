# Tool Calling and MCP Architecture

Tools are typed, allowlisted, scoped, time-bounded capabilities; the model never receives unrestricted network or database access. MCP servers publish declared tools and permissions. A policy gateway validates identity, purpose, arguments, approval state, and result redaction.

```mermaid
sequenceDiagram
  participant L as LLM
  participant P as Policy Gateway
  participant T as Approved Tool
  L->>P: structured tool request
  P->>P: validate scope and approval
  P->>T: authorised call
  T-->>P: minimal result
  P-->>L: redacted result
```

```mermaid
flowchart LR
  A[Agent] --> M[MCP client]
  M --> P[MCP policy gateway]
  P --> S[Scoped MCP server]
  S --> T[Approved business tool]
  T --> X[Audit event]
```
