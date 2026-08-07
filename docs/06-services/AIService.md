# AI Service

**Purpose:** Governed LLM interaction, prompts, safety, and response orchestration.  
**Responsibilities:** Context, model routing, grounding, safety, audit.  
**Owned Data:** Prompt/version and AI interaction metadata.  
**REST APIs:** AI assistance APIs.  
**Events Published / Consumed:** `AIResponseGenerated` / consultation requests.  
**Dependencies:** RAG, Agent, model gateway, Audit.  
**Security:** Consent-aware context, policy gates, human approval.  
**Scaling strategy:** Separate asynchronous/streaming pools with quotas.
