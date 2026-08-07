# AI Evaluation

Evaluation is continuous and release-gated. Curated, de-identified test sets cover grounding, medical safety, language, bias, refusal, tool use, retrieval, and adversarial prompts. Offline evaluation precedes controlled production monitoring; human clinical reviewers adjudicate high-risk cases and regression failures.

```mermaid
flowchart LR
  D[Curated evaluation data] --> R[Run prompts, RAG, tools]
  R --> M[Quality and safety metrics]
  M --> H[Clinical and engineering review]
  H --> G{Release gate}
  G -- Pass --> P[Controlled production]
  G -- Fail --> F[Fix prompt, model, or policy]
```
