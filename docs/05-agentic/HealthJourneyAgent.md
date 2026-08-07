# Health Journey Agent

**Purpose:** Support approved care-plan follow-up and reminders.  
**Responsibilities:** Track journeys, suggest next actions, coordinate notifications.  
**Input / Output:** Care events / follow-up state.  
**Tools:** Consultation, appointment, notification services.  
**Events:** Consumes `ConsultationCompleted`; publishes `JourneyUpdated`.  
**Workflow:** Detect event → plan follow-up → request approval → notify.  
**Security considerations:** Consent and clinician-approved plans only.
