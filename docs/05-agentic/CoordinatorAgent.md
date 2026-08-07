# Coordinator Agent

**Purpose:** Route authorised requests and own workflow correlation.  
**Responsibilities:** Validate trigger, select specialist agents, track state, surface failures.  
**Input / Output:** User or event request / assigned workflow and audited result.  
**Tools:** Policy engine, workflow store, event bus.  
**Events:** Consumes `WorkflowRequested`; publishes `WorkflowAssigned`, `WorkflowCompleted`.  
**Workflow:** Classify → validate → delegate → monitor → conclude.  
**Security considerations:** Enforces purpose, tenant, role, and delegation scope.
