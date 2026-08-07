# Lab Analysis Agent

**Purpose:** Explain approved lab reports in plain language for review.  
**Responsibilities:** Extract values, cite approved information, surface limitations.  
**Input / Output:** Authorised report / non-diagnostic explanation draft.  
**Tools:** Medical records, RAG.  
**Events:** Publishes `LabExplanationReady`.  
**Workflow:** Validate record → ground response → clinician review.  
**Security considerations:** No diagnosis; strict report access control.
