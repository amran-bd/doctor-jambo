# Audit Service

**Purpose:** Immutable evidence for sensitive actions and healthcare compliance.  
**Responsibilities:** Collect, retain, query, and protect audit events.  
**Owned Data:** Append-only audit records.  
**REST APIs:** Authorised audit query APIs.  
**Events Published / Consumed:** `AuditArchived` / security, access, AI, agent, and domain events.  
**Dependencies:** Kafka, secure retention storage.  
**Security:** Tamper-evident records and strict auditor roles.  
**Scaling strategy:** Stream ingestion and partitioned immutable storage.
