# Agent Service

**Purpose:** Orchestrate policy-bounded agent workflows.  
**Responsibilities:** Lifecycle, plans, task state, MCP tool policy, approval.  
**Owned Data:** Workflow and agent execution state.  
**REST APIs:** Agent workflow APIs.  
**Events Published / Consumed:** `WorkflowCompleted` / consultation and appointment events.  
**Dependencies:** AI, MCP tools, business services, Audit.  
**Security:** Typed tools, least privilege, human-in-the-loop.  
**Scaling strategy:** Queue-backed workers partitioned by workflow.
