### Eneas Faleiros

Adult Intensive Care physician by training and clinical systems architect based in London.

Over the past 25+ years I have worked across almost every chair where clinical decisions meet institutional rules and software: tertiary ICU practice, public health commissioning and regional critical-care bed regulation, health technology assessment (HTA / pharmacoeconomics) and CMIO audit software, hospital medical operations and buyer-side paperless EHR go-live, and 14+ years of multi-hospital EPR architecture, interoperability (`FHIR`), deterministic clinical decision support (`EKM`), and clinical AI safety governance across the UK, Europe, and Brazil.

#### How I Build Here

I approach personal software the same way high-stakes clinical systems have to be built: explicit domain and functional specifications, deterministic replayable state, Architecture Decision Records (`ADRs`), hard safety boundaries around probabilistic AI outputs, and automated pass/fail acceptance gates (`VDONE.md`) — directing AI coding agents as a systems architect and clinical specifier rather than claiming to be a production software developer.

#### Selected Open-Source Projects

| Project | Architecture & Safety Focus | Links |
| :--- | :--- | :--- |
| **[Health OS](https://github.com/Eneasf/health-os)** | Self-hosted personal health data platform aggregating longitudinal measurements (`Samsung Health SDK` Kotlin companion app, smart-scale telemetry, lab reports, and Gemini Vision OCR) over an event-sourced, deterministically replayable read model (`39 ADRs`). Enforces clinical null-honesty (`ADR-016` — missing data is never interpolated) and routes anomalous AI-extracted values to a human review queue. | [Repo](https://github.com/Eneasf/health-os) · [Live Synthetic Demo](https://eneasf.github.io/health-os/) · `MIT` |
| **[Antigravity Token Dashboard](https://github.com/Eneasf/antigravity-token-dashboard)** | Offline, zero-dependency (`Python 3.9+` stdlib) read-only SQLite and custom protobuf telemetry engine with a web observability dashboard tracking LLM token burn, context-cache efficiency, reasoning-token share, and subagent lineage (`40+ ADRs`, `200` automated tests, PII release gates). | [Repo](https://github.com/Eneasf/antigravity-token-dashboard) · [Live Synthetic Demo](https://eneasf.github.io/antigravity-token-dashboard/) · `MIT` |

---

*Independent personal projects, unaffiliated with my employer. All public repositories and live demos run strictly on generated synthetic data.*
