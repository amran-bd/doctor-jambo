# Patient Service

**Purpose:** Patient profile, preferences, and health-information metadata ownership.  
**Responsibilities:** Profile, consent preferences, authorised patient context.  
**Owned Data:** Patient aggregate and preferences.  
**REST APIs:** Patient profile and consent APIs.  
**Events Published / Consumed:** `PatientUpdated` / `UserAccessChanged`.  
**Dependencies:** Auth, audit.  
**Security:** Patient-scoped RBAC, consent and minimisation.  
**Scaling strategy:** Stateless API replicas; indexed PostgreSQL reads.
