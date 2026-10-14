# Amy V

### Technical writing · API reliability · Developer education

I build software and write the documentation that makes it usable. My work connects API contracts, SDK behavior, failure recovery, application security, and the decisions developers need to make along the way.

My approach starts with a working example: reproduce the behavior, test the difficult paths, explain the tradeoffs, and give the reader a clear next step. The result is a body of independent projects with source code, tests, technical reports, and walkthroughs you can inspect together.

**[Portfolio](https://amy-villa-signal-gallery.vercel.app/) · [Engineering evidence](https://amy-villa-signal-gallery.vercel.app/recruiter-proof) · [LinkedIn](https://www.linkedin.com/in/amy-villa-5830aa433/) · [Medium](https://medium.com/@amyv.dev) · [Contact](mailto:amyv.dev@gmail.com)**

## Start with the evidence

| Explore | The question it answers | Review the work |
| --- | --- | --- |
| **API documentation — HookForge SDK** | Can a developer install, run, and evaluate an SDK from the documentation? | [Quickstart and examples](https://github.com/Amyvdev1/hookforge-sdk#readme) · [Developer-experience report](https://github.com/Amyvdev1/hookforge-sdk/blob/main/report.md) |
| **Security explanation — Webhook Trust Lab** | Why does a valid signature still need freshness, event identity, and a transaction boundary? | [Implementation and tests](https://github.com/Amyvdev1/webhook-trust-lab) · [Case study and video](https://amy-villa-signal-gallery.vercel.app/projects/webhook-trust-lab) |
| **Integration education — Olostep Reliability Lab** | What should an integration do when a batch is partial, interrupted, or uncertain? | [Recovery model](https://github.com/Amyvdev1/olostep-integration-reliability-lab/blob/main/docs/reliability-model.md) · [Case study and video](https://amy-villa-signal-gallery.vercel.app/projects/olostep-integration-reliability-lab) |

For a five-minute review, choose one question, open its walkthrough, then compare the explanation with the implementation and tests. For the broader product architecture, explore SignalOS below.

## Selected writing

- **[Technical Work Is a Form of Translation](https://medium.com/@amyv.dev/technical-work-is-a-form-of-translation-8a54c98bf673)** — moving between code, product, operations, and human judgment.
- **[The Hidden Economics of AI Automation](https://medium.com/@amyv.dev/the-hidden-economics-of-ai-automation-d6b04f46d816)** — examining why faster is not necessarily better.
- **[The Most Important AI Product Feature May Be the Next Action](https://medium.com/@amyv.dev/the-most-important-ai-product-feature-may-be-the-next-action-9705fed201f0)** — making explanations useful at the moment a reader needs to act.

[Read more on Medium →](https://medium.com/@amyv.dev)

## Flagship — SignalOS

**[SignalOS — The Developer Experience Reliability Platform](https://github.com/Amyvdev1/signalos-developer-experience-platform)**

One payment-launch investigation connects contract findings, an outdated quickstart, timeout recovery, duplicate protection, agent approval, policy replay, and an exportable evidence trail.

- Analyze OpenAPI contract gaps and supported breaking changes.
- Reproduce local HTTP failures; retry a committed operation without duplicating it.
- Inspect HMAC verification, replay windows, and synthetic event ordering.
- Require an expiring, argument-and-policy-bound approval before a simulated financial action.
- Preserve investigation history in SQLite and export Markdown, JSON, HTML, or CSV.
- Inspect estimated economics with explicit inputs; unknown costs remain unknown.

**Working local MVP:** React, TypeScript, Node 24, SQLite, 44 behavioral tests, desktop/mobile browser checks, and GitHub Actions. The broader platform is a documented roadmap; the current SDK, documentation, and economics features support the payment scenario.

[Case study and console preview](https://amy-villa-signal-gallery.vercel.app/projects/signalos-developer-experience-platform) · [Architecture](https://github.com/Amyvdev1/signalos-developer-experience-platform/blob/main/docs/architecture.md) · [Engineering article](https://github.com/Amyvdev1/signalos-developer-experience-platform/blob/main/docs/engineering-note.md) · [Verification](https://github.com/Amyvdev1/signalos-developer-experience-platform/actions/workflows/verify.yml)

## Security and integration reliability

**[Webhook Trust Lab](https://github.com/Amyvdev1/webhook-trust-lab)** follows an event from HMAC verification and signed timestamps to persistent event identity and an atomic SQLite-local effect. Inspect 39 deterministic tests, concurrent delivery, rollback, a threat model, and nine recorded scenarios. [Case study and walkthrough](https://amy-villa-signal-gallery.vercel.app/projects/webhook-trust-lab).

**[Olostep Integration Reliability Lab](https://github.com/Amyvdev1/olostep-integration-reliability-lab)** makes asynchronous batches, polling, pagination, partial results, and recovery explainable. Nine offline scenarios accompany a sanitized two-URL live compatibility check. [Case study and walkthrough](https://amy-villa-signal-gallery.vercel.app/projects/olostep-integration-reliability-lab).

Both are independent reference projects. Local security behavior and a bounded live compatibility check do not establish production adoption or exactly-once remote effects.

## AI economics, controls & decision systems

<details>
<summary>Explore five projects on cost, permissions, evidence, and onboarding</summary>

| Project | Purpose | Implementation to inspect |
| --- | --- | --- |
| [AgentLedger](https://github.com/Amyvdev1/agentledger-economics) | AI Agent Economics and Decision Ledger | Model/tool/retry/review cost estimates, persistent events, unknown-cost propagation, human baseline and risk-adjusted value |
| [TrustBoundary](https://github.com/Amyvdev1/trustboundary-agent-controls) | AI Agent Permissions, Policy and Human Approval | Strict tool schemas, role/scope gates, expiring approvals, idempotent execution and policy-aware replay |
| [EvidenceGraph](https://github.com/Amyvdev1/evidencegraph-decision-workspace) | Research Provenance and Decision Support | Source-to-claim links, contradictory evidence, freshness, human decisions and preserved evidence snapshots |
| [WorkflowROI](https://github.com/Amyvdev1/workflowroi-automation-economics) | Automation Economics and Human-in-the-Loop Simulation | Manual/partial/AI-assisted comparison, review and error costs, adoption, break-even and sensitivity analysis |
| [DeveloperJourney Observatory](https://github.com/Amyvdev1/developerjourney-observatory) | Developer Onboarding, Friction and Recovery Analytics | Synthetic journeys, first-success and recovery metrics, privacy validation and documentation comparisons |

These five applications use React, Node 24 and SQLite, with local setup, tests, browser verification, reports, architecture notes and engineering articles. [Explore the collection](https://amy-villa-signal-gallery.vercel.app/recruiter-proof#decision-systems).

</details>

## API & developer tools

<details>
<summary>Explore six API, SDK, and developer-experience projects</summary>

| Project | Purpose | Implementation to inspect |
| --- | --- | --- |
| [DX Orbit](https://github.com/Amyvdev1/dx-orbit) | Developer Experience Intelligence for OpenAPI | Explainable contract findings, integration friction, revision comparison and report export |
| [DevStart](https://github.com/Amyvdev1/devstart) | API Developer Onboarding & Recovery Environment | Authentication, validation, rate limits, failure states and actionable recovery scenarios |
| [HookForge](https://github.com/Amyvdev1/hookforge) | Webhook Reliability & Debugging Workbench | Signatures, retries, duplicate delivery, event ordering, malformed payloads and recovery |
| [ToolTrust](https://github.com/Amyvdev1/tooltrust) | AI Agent Tool Reliability Infrastructure | Tool schemas, permissions, side effects, confirmation, idempotency and replayable simulated execution |
| [SignalDesk](https://github.com/Amyvdev1/signaldesk) | Developer Feedback Intelligence | Structured friction and documentation feedback, prioritization, resolution and issue-draft export |
| [HookForge SDK](https://github.com/Amyvdev1/hookforge-sdk) | TypeScript SDK & Generator Evaluation | MIT SDK generated with Voxgig, setup/examples, generated checks, local HTTP verification and a developer-experience report |

</details>

## Full-stack systems & interface engineering

<details>
<summary>Explore workflow engineering, webhook debugging, and accessible interfaces</summary>

| Project | Focus |
| --- | --- |
| [ForgeFlow AI Automation](https://github.com/Amyvdev1/forgeflow-ai-automation) | React/TypeScript and FastAPI workflows, validated inputs, SQLite run history, visible fallback behavior and human review |
| [MailTrace DX Lab](https://github.com/Amyvdev1/Amyvdev1-mailtrace-dx-lab) | Signed webhooks, retries, idempotency, event ordering and developer-facing failure investigation |
| [ClearRoute API](https://github.com/Amyvdev1/clearrout-api) | Typed validation, legal workflow transitions, predictable errors, audit events, tests and CI |
| [AccessPath Console](https://github.com/Amyvdev1/accessible-workflow-console) | Keyboard-first workflows, semantic interfaces, visible focus, accessible recovery and accessibility checks |

</details>

## Portfolio & supporting assets

- **[Technical Portfolio / Signal Engine](https://github.com/Amyvdev1/amy-technical-portfolio):** a React/TypeScript review experience connecting project narratives, actual application previews, public source, tests and implementation boundaries. [Visit the website](https://amy-villa-signal-gallery.vercel.app/).
- **[Portfolio Assets](https://github.com/Amyvdev1/amy-villa-portfolio-assets):** the supporting visual asset repository for the portfolio.

## Engineering principles

- Make inputs, state transitions and failure paths explicit.
- Validate before acting; keep permission and approval decisions inspectable.
- Test recovery, malformed requests and duplicates alongside the happy path.
- Keep measured behavior, estimates, assumptions and synthetic fixtures distinguishable.
- Document what runs today and what production operation would still require.

**Working stack:** TypeScript · React · Node.js · Python · FastAPI · Pydantic · Zod · REST/OpenAPI · JSON Schema · SQLite · pytest · Vitest · Playwright · Docker · GitHub Actions

**Evidence boundary:** These are independent engineering projects. Simulated payments, agent execution, feedback and onboarding sessions are labelled. Forecasts are not measured savings; tests and local verification do not imply production adoption, scale, authenticated security or customer outcomes. Each repository documents its own implemented scope and limitations.
