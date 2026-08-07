# Medication Agent

**Purpose:** Provide approved medication information and reminders.  
**Responsibilities:** Retrieve authorised information and flag conflicts for review.  
**Input / Output:** Approved medication context / labelled draft guidance.  
**Tools:** Medical record, approved knowledge.  
**Events:** Publishes `MedicationReviewRequested`.  
**Workflow:** Retrieve → validate → require clinician approval.  
**Security considerations:** Cannot alter medication or provide unapproved advice.
