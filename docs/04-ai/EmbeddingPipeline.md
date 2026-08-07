# Embedding Pipeline

Ingestion validates source approval, extracts content, removes unsupported sensitive material, normalises and chunks text, generates embeddings, stores index metadata, and emits `KnowledgeIndexed`. Quality checks measure duplicate content, chunk coverage, language, extraction error, and retrieval relevance. Failed jobs are recoverable and auditable.
