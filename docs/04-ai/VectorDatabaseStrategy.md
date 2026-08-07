# Vector Database Strategy

The vector store is accessed only through the RAG context. It stores embeddings and approved metadata, not an uncontrolled replacement for medical records. Indexes support tenant, language, content class, authority, validity period, and access-policy filtering. Re-embedding is versioned; deletion and retention propagate from source governance.
