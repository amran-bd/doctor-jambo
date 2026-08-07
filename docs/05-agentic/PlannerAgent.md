# Planner Agent

**Purpose:** Produce bounded, policy-aware execution plans.  
**Responsibilities:** Decompose approved goals and identify approvals.  
**Input / Output:** Goal and constraints / structured plan.  
**Tools:** Policy, knowledge retrieval.  
**Events:** Consumes `WorkflowAssigned`; publishes `PlanProposed`.  
**Workflow:** Inspect → plan → validate → await approval.  
**Security considerations:** Cannot grant tools or bypass approval.
