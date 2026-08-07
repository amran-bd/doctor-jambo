# Doctor Service

**Purpose:** Doctor profile, credential status, and availability.  
**Responsibilities:** Provider management and schedules.  
**Owned Data:** Doctor aggregate, services, availability slots.  
**REST APIs:** Doctor discovery and availability APIs.  
**Events Published / Consumed:** `DoctorAvailabilityChanged` / `UserAccessChanged`.  
**Dependencies:** Auth, audit.  
**Security:** Verified-provider access and administrator approval.  
**Scaling strategy:** Read replicas/cache for discovery; partition scheduling workloads.
