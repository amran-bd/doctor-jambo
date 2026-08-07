# Notification Service

**Purpose:** Consent-aware email, SMS, and push delivery.  
**Responsibilities:** Template, channel preference, delivery status, retries.  
**Owned Data:** Notification preference and delivery state.  
**REST APIs:** Notification request/status APIs.  
**Events Published / Consumed:** `NotificationDelivered` / appointment and workflow events.  
**Dependencies:** Channel providers, Patient.  
**Security:** Consent, content minimisation, provider secrets.  
**Scaling strategy:** Kafka consumers and independent delivery workers.
