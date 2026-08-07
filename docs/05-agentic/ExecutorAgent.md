# Executor Agent

**Purpose:** Execute authorised plan steps.  
**Responsibilities:** Invoke scoped tools, retry safely, compensate failures.  
**Input / Output:** Approved step / result and evidence.  
**Tools:** MCP-gated business tools.  
**Events:** Consumes `PlanApproved`; publishes `StepCompleted` or `StepFailed`.  
**Workflow:** Validate → call tool → verify → record.  
**Security considerations:** Least privilege, timeouts, immutable audit.
