# Amy Villa

### AI Automation & Technical Solutions Engineer

I build API integrations, inspectable automation, and developer tools that explain what happened, why it failed, and how to recover.

My portfolio focuses on practical engineering questions: validating a tool call before execution, preserving webhook state under retries, making API errors actionable, and keeping human review visible.

**[Explore my portfolio](https://amy-villa-signal-gallery.vercel.app/) · [Recruiter review guide](https://amy-villa-signal-gallery.vercel.app/recruiter-proof) · [LinkedIn](https://www.linkedin.com/in/amy-villa-5830aa433/)**

### A useful five-minute review

1. **API and developer experience:** inspect [DX Orbit](https://github.com/Amyvdev1/dx-orbit), an OpenAPI scorecard with traceable findings, revision comparison, and report export.
2. **Agent tool boundaries:** inspect [ToolTrust](https://github.com/Amyvdev1/tooltrust), a deterministic lab for JSON Schema validation, permissions, human confirmation, and simulated execution traces.
3. **Full-stack workflow engineering:** inspect [ForgeFlow](https://github.com/Amyvdev1/forgeflow-ai-automation), including validated inputs, persisted run history, visible fallback behavior, and human review.

Open the tests and CI alongside the source. They show the behavior each project is designed to preserve.

### Developer tools collection

| Project | Engineering question | Evidence to inspect |
| --- | --- | --- |
| [DX Orbit](https://github.com/Amyvdev1/dx-orbit) | Where does an API contract create integration friction? | Explainable scoring, JSON/YAML input, malformed-input checks, comparison reports |
| [ToolTrust](https://github.com/Amyvdev1/tooltrust) | Should this tool call proceed? | Schema validation, permission and confirmation gates, readable replay traces |
| [DevStart](https://github.com/Amyvdev1/devstart) | Can a developer recover from an API failure? | Six deterministic onboarding scenarios, recovery guidance, session benchmarks |
| [HookForge](https://github.com/Amyvdev1/hookforge) | Does state survive duplicate and out-of-order delivery? | HMAC checks, duplicate protection, stale-event rejection, bounded simulations |
| [SignalDesk](https://github.com/Amyvdev1/signaldesk) | Which documentation problem should a maintainer investigate next? | Feedback taxonomy, weighted priorities, resolution workflow, issue drafts |

These are runnable engineering labs with explicit limits. Simulated delivery and tool execution are labelled; fictional feedback is not customer research. They do not claim production adoption or measured business impact.

### More implementation evidence

- **[MailTrace DX Lab](https://github.com/Amyvdev1/Amyvdev1-mailtrace-dx-lab):** signed webhooks, retries, idempotency, event ordering, and developer-facing debugging.
- **[ForgeFlow AI Automation](https://github.com/Amyvdev1/forgeflow-ai-automation):** React/TypeScript, FastAPI, SQLite persistence, testing, Docker, and CI.
- **[ClearRoute API](https://github.com/Amyvdev1/clearrout-api):** typed validation, explicit state transitions, predictable error contracts, and audit events.
- **[AccessPath Console](https://github.com/Amyvdev1/accessible-workflow-console):** keyboard-first interaction, visible focus, recovery states, and accessibility checks.
- **[Technical Portfolio / Signal Engine](https://github.com/Amyvdev1/amy-technical-portfolio):** an interactive review path connecting the product experience to source, tests, and implementation boundaries.

### How I approach engineering

- Make inputs, state transitions, and failure paths explicit.
- Validate before acting; keep permissions and human decisions inspectable.
- Test the behavior that matters, including recovery and malformed requests.
- Document what runs today and what production deployment would still require.

**Working stack:** Python · FastAPI · Pydantic · JSON Schema · REST/OpenAPI · TypeScript · React · SQLite · pytest · Vitest · Docker · GitHub Actions

**Role focus:** AI automation, technical solutions, API integration, developer experience, and implementation engineering.
