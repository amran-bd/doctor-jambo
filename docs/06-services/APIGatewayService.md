# API Gateway Service

**Purpose:** Secure public entry point and API composition boundary.  
**Responsibilities:** Routing, rate limits, token propagation, request correlation.  
**Owned Data:** Route and policy configuration.  
**REST APIs:** Public versioned routes to domain services.  
**Events Published / Consumed:** Access telemetry / configuration changes.  
**Dependencies:** Auth and domain service APIs.  
**Security:** OAuth2/OIDC validation, JWT scopes, WAF/rate policy.  
**Scaling strategy:** Stateless horizontal replicas and edge caching.
