# Symptom Analysis Agent

**Purpose:** Structure patient-reported symptoms for clinician review.  
**Responsibilities:** Clarify input and detect escalation criteria.  
**Input / Output:** Patient narrative / structured, non-diagnostic summary.  
**Tools:** RAG, safety policy.  
**Events:** Publishes `SymptomSummaryReady`.  
**Workflow:** Gather → safety screen → summarise → escalate where required.  
**Security considerations:** Never diagnoses; urgent cases receive emergency guidance.
