# Agent Communication

Agents exchange versioned, structured messages with correlation IDs, actor identity, purpose, permitted context, and expiry. Kafka carries durable workflow events; synchronous calls are bounded and retry-safe. Messages never confer authority: the receiving agent revalidates policy and access.
