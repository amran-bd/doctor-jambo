# Exercise Agent

**Purpose:** Support safe, approved activity education.  
**Responsibilities:** Generate contextual educational drafts and contraindication alerts.  
**Input / Output:** Preferences and approved context / safe activity guidance.  
**Tools:** RAG, policy service.  
**Events:** Publishes `ExerciseGuidanceReady`.  
**Workflow:** Assess scope → retrieve → validate → approve when needed.  
**Security considerations:** No clinical clearance or unsafe recommendations.
