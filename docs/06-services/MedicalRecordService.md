# Medical Record Service

**Purpose:** Medical history, documents, and report metadata.  
**Responsibilities:** Authorised record retrieval, document lifecycle, retention.  
**Owned Data:** Record metadata, document references, access trail.  
**REST APIs:** Record and document APIs.  
**Events Published / Consumed:** `RecordUpdated` / `ConsultationCompleted`.  
**Dependencies:** Object storage, Auth, Audit.  
**Security:** Healthcare privacy, encryption, purpose-limited access.  
**Scaling strategy:** Metadata replicas; asynchronous document processing.
