# RAG Service

**Purpose:** Knowledge ingestion, embedding, vector search, and grounded retrieval.  
**Responsibilities:** Approved-source lifecycle and access-aware retrieval.  
**Owned Data:** Knowledge metadata and vector-index contracts.  
**REST APIs:** Retrieval and ingestion APIs.  
**Events Published / Consumed:** `KnowledgeIndexed` / `RecordUpdated`.  
**Dependencies:** Vector database, embedding provider.  
**Security:** Source approval and retrieval access filtering.  
**Scaling strategy:** Asynchronous ingestion workers; scalable read index.
