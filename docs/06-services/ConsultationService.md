# Consultation Service

**Purpose:** Patient-doctor interaction lifecycle and medical notes.  
**Responsibilities:** Create, manage, and complete consultations.  
**Owned Data:** Consultation aggregate, participant state, notes.  
**REST APIs:** Consultation and note APIs.  
**Events Published / Consumed:** `ConsultationCreated`, `ConsultationCompleted` / patient and doctor updates.  
**Dependencies:** Patient, Doctor, Medical Record, AI.  
**Security:** Participant authorisation, clinician approval, audit.  
**Scaling strategy:** Stateless workload; partition by consultation ID.
