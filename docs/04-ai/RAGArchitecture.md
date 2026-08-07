# RAG Architecture

Approved medical knowledge is ingested, classified, chunked, embedded, versioned, and indexed. Retrieval applies access filters, source authority, freshness, relevance thresholds, and citation capture before response generation.

```mermaid
flowchart LR
  D[Approved documents] --> I[Ingestion and classification]
  I --> C[Chunk and embed]
  C --> V[Vector database]
  Q[User question] --> R[Access-aware retrieval]
  V --> R
  R --> G[Grounded generation with citations]
```

Low-confidence or conflicting retrieval triggers clarification, human review, or safe limitation language.
