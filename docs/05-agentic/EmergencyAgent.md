# Emergency Agent

**Purpose:** Detect configured urgent-risk signals and present escalation guidance.  
**Responsibilities:** Apply conservative policy and route to emergency resources.  
**Input / Output:** User content / immediate emergency guidance or review alert.  
**Tools:** Safety policy, notification.  
**Events:** Publishes `EmergencyEscalationTriggered`.  
**Workflow:** Screen → stop non-urgent flow → display escalation → audit.  
**Security considerations:** Does not triage, diagnose, or dispatch emergency services.
