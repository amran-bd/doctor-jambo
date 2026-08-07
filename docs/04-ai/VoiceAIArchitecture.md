# Voice AI Architecture

Voice interactions require notice and consent. Speech-to-text supplies confidence and correction; language detection selects approved translation; AI processes reviewed text; text-to-speech returns the answer with transparent processing state. Audio and transcript retention follow patient-data policy.

```mermaid
flowchart LR
  A[Voice input] --> S[Speech to text]
  S --> L[Language and translation]
  L --> G[AI safety and generation]
  G --> T[Text to speech]
  T --> P[Patient]
```
