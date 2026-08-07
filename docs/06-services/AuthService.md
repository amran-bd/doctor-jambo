# Auth Service

**Purpose:** Identity, authentication, authorisation, and user lifecycle.  
**Responsibilities:** OAuth2/OIDC, roles, credentials, access policy.  
**Owned Data:** User identity, roles, consent-linked access metadata.  
**REST APIs:** Token, user, role, and access-management APIs.  
**Events Published / Consumed:** `UserAccessChanged` / admin policy changes.  
**Dependencies:** Identity provider, audit.  
**Security:** RBAC, MFA-capable integration, immutable access audit.  
**Scaling strategy:** Stateless replicas; durable identity store.
