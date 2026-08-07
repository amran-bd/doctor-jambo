# LLM Strategy

## Purpose

Define resilient model selection and portability.

## Strategy

Use OpenAI-compatible APIs behind a model gateway and support approved open-source models for regional, cost, latency, and resilience needs. Route by task risk, capability, data residency, latency, and evaluation score—not only cost. Pin model and configuration versions per interaction; maintain fallback models and explicit degraded behaviour.

## Constraints

No provider receives data beyond approved policy; model changes require evaluation and governance approval.
