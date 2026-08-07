# Hexagonal Architecture

Each service separates domain and application logic from adapters. Inbound adapters expose HTTP, events, and scheduled commands; outbound adapters implement PostgreSQL, Kafka, Redis, model, vector, notification, and partner ports. This keeps business rules testable and limits vendor coupling.
