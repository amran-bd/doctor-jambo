# Data Architecture

PostgreSQL databases are owned per service and use migrations and backup/recovery controls. Medical content uses encrypted object storage with metadata in the Medical Record context. Redis holds ephemeral cache only. The RAG context owns knowledge metadata and uses a vector database behind an access-aware retrieval API. Data sharing uses APIs, events, or read models—not shared writes.
