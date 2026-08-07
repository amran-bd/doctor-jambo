# Doctor Copilot Agent

**Purpose:** Draft clinician-facing summaries, notes, and follow-up suggestions.  
**Responsibilities:** Ground drafts in authorised consultation context.  
**Input / Output:** Consultation and record context / reviewable draft.  
**Tools:** Consultation, medical record, RAG.  
**Events:** Publishes `CopilotDraftReady`.  
**Workflow:** Retrieve → draft → safety check → doctor approves, edits, or rejects.  
**Security considerations:** Doctor approval is required before save or sharing.
