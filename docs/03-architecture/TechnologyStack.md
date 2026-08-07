# Technology Stack

| Layer | Target technology | Role |
| --- | --- | --- |
| Backend | Java 25, Spring Boot 4+, Spring Cloud | Domain services, configuration, resilience, gateway patterns |
| AI | Spring AI, LangChain4j, Embabel, MCP | Model integration, orchestration, tools, agent workflows |
| Messaging | Kafka | Durable domain and integration events |
| Data | PostgreSQL, Redis | Transactional service data and cache |
| Runtime | Docker, Kubernetes | Containers, orchestration, scaling |
| Observability | OpenTelemetry-compatible tooling | Traces, metrics, logs, alerting |

All selections are target architecture decisions and require implementation ADR review.
