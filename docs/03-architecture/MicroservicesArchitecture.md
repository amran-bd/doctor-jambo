# Microservices Architecture

| Service | Responsibility | Owned data | APIs | Publishes | Consumes | Dependencies |
| --- | --- | --- | --- | --- | --- |
| doctor-jambo-api-gateway | Edge routing, rate controls, token propagation | Route policy | Public APIs | Access telemetry | Config events | Identity, all services |
| doctor-jambo-auth-service | Authentication, authorisation, user management | Identities, roles | OAuth/OIDC, user APIs | UserAccessChanged | Admin events | Identity provider |
| doctor-jambo-patient-service | Profiles, preferences, health-information metadata | Patient profile | Patient APIs | PatientUpdated | UserAccessChanged | Auth |
| doctor-jambo-doctor-service | Doctor profiles and availability | Doctor profile, slots | Doctor APIs | DoctorAvailabilityChanged | UserAccessChanged | Auth |
| doctor-jambo-consultation-service | Consultation lifecycle and notes | Consultations, notes | Consultation APIs | ConsultationCreated, Completed | PatientUpdated | Patient, Doctor |
| doctor-jambo-medical-record-service | History, documents, reports | Record metadata, documents | Record APIs | RecordUpdated | ConsultationCompleted | Object storage |
| doctor-jambo-ai-service | LLM, prompts, safety, response orchestration | Prompt and audit metadata | AI APIs | AIResponseGenerated | ConsultationCreated | RAG, model gateway |
| doctor-jambo-rag-service | Ingestion, embeddings, retrieval | Knowledge metadata | Retrieval APIs | KnowledgeIndexed | RecordUpdated | Vector database |
| doctor-jambo-agent-service | Agent orchestration and workflow execution | Workflow state | Agent APIs | WorkflowCompleted | Consultation, notification events | MCP tools, business services |
| doctor-jambo-notification-service | Email, SMS, push delivery | Preferences, delivery state | Notification APIs | NotificationDelivered | Appointment, workflow events | External channels |
