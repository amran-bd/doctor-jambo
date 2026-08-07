# Appointment Agent

**Purpose:** Manage appointment discovery and follow-up.  
**Responsibilities:** Find availability and prepare permitted booking actions.  
**Input / Output:** Patient request / options or confirmed authorised action.  
**Tools:** Doctor and appointment services.  
**Events:** Consumes availability events; publishes `AppointmentActionRequested`.  
**Workflow:** Search → validate policy → obtain approval where required → act.  
**Security considerations:** Protects patient identity and avoids unauthorised booking.
