# Appointment Service

**Purpose:** Appointment booking, change, and cancellation lifecycle.  
**Responsibilities:** Availability reservation and participant notification triggers.  
**Owned Data:** Appointment aggregate and reservation state.  
**REST APIs:** Appointment management APIs.  
**Events Published / Consumed:** `AppointmentBooked`, `AppointmentChanged` / availability changes.  
**Dependencies:** Patient, Doctor, Notification.  
**Security:** Participant and provider policy checks.  
**Scaling strategy:** Transactional partitioning and idempotent booking commands.
