# Amy Villa

### API systems · Developer experience · Inspectable automation

I build developer-facing systems that make complex workflows easier to integrate, debug, and operate. My work connects API contracts, SDK behavior, failure recovery, agent permissions, and the evidence behind a technical decision.

A system should explain what happened, why an action was allowed or blocked, how to recover, and which assumptions shape its value.

**[Portfolio](https://amy-villa-signal-gallery.vercel.app/) · [Engineering evidence](https://amy-villa-signal-gallery.vercel.app/recruiter-proof) · [LinkedIn](https://www.linkedin.com/in/amy-villa-5830aa433/) · [Contact](mailto:amyv.dev@gmail.com)**

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

## AI economics, controls & decision systems

| Project | Purpose | Implementation to inspect |
| --- | --- | --- |
| [AgentLedger](https://github.com/Amyvdev1/agentledger-economics) | AI Agent Economics and Decision Ledger | Model/tool/retry/review cost estimates, persistent events, unknown-cost propagation, human baseline and risk-adjusted value |
| [TrustBoundary](https://github.com/Amyvdev1/trustboundary-agent-controls) | AI Agent Permissions, Policy and Human Approval | Strict tool schemas, role/scope gates, expiring approvals, idempotent execution and policy-aware replay |
| [EvidenceGraph](https://github.com/Amyvdev1/evidencegraph-decision-workspace) | Research Provenance and Decision Support | Source-to-claim links, contradictory evidence, freshness, human decisions and preserved evidence snapshots |
| [WorkflowROI](https://github.com/Amyvdev1/workflowroi-automation-economics) | Automation Economics and Human-in-the-Loop Simulation | Manual/partial/AI-assisted comparison, review and error costs, adoption, break-even and sensitivity analysis |
| [DeveloperJourney Observatory](https://github.com/Amyvdev1/developerjourney-observatory) | Developer Onboarding, Friction and Recovery Analytics | Synthetic journeys, first-success and recovery metrics, privacy validation and documentation comparisons |

These five applications use React, Node 24 and SQLite, with local setup, tests, browser verification, reports, architecture notes and engineering articles. [Explore the collection](https://amy-villa-signal-gallery.vercel.app/recruiter-proof#decision-systems).

## API & developer tools

| Project | Purpose | Implementation to inspect |
| --- | --- | --- |
| [DX Orbit](https://github.com/Amyvdev1/dx-orbit) | Developer Experience Intelligence for OpenAPI | Explainable contract findings, integration friction, revision comparison and report export |
| [DevStart](https://github.com/Amyvdev1/devstart) | API Developer Onboarding & Recovery Environment | Authentication, validation, rate limits, failure states and actionable recovery scenarios |
| [HookForge](https://github.com/Amyvdev1/hookforge) | Webhook Reliability & Debugging Workbench | Signatures, retries, duplicate delivery, event ordering, malformed payloads and recovery |
| [ToolTrust](https://github.com/Amyvdev1/tooltrust) | AI Agent Tool Reliability Infrastructure | Tool schemas, permissions, side effects, confirmation, idempotency and replayable simulated execution |
| [SignalDesk](https://github.com/Amyvdev1/signaldesk) | Developer Feedback Intelligence | Structured friction and documentation feedback, prioritization, resolution and issue-draft export |
| [HookForge SDK](https://github.com/Amyvdev1/hookforge-sdk) | TypeScript SDK & Generator Evaluation | MIT SDK generated with Voxgig, setup/examples, generated checks, local HTTP verification and a developer-experience report |

## Full-stack systems & interface engineering

| Project | Focus |
| --- | --- |
| [ForgeFlow AI Automation](https://github.com/Amyvdev1/forgeflow-ai-automation) | React/TypeScript and FastAPI workflows, validated inputs, SQLite run history, visible fallback behavior and human review |
| [MailTrace DX Lab](https://github.com/Amyvdev1/Amyvdev1-mailtrace-dx-lab) | Signed webhooks, retries, idempotency, event ordering and developer-facing failure investigation |
| [ClearRoute API](https://github.com/Amyvdev1/clearrout-api) | Typed validation, legal workflow transitions, predictable errors, audit events, tests and CI |
| [AccessPath Console](https://github.com/Amyvdev1/accessible-workflow-console) | Keyboard-first workflows, semantic interfaces, visible focus, accessible recovery and accessibility checks |

## Portfolio & supporting assets

- **[Technical Portfolio / Signal Engine](https://github.com/Amyvdev1/amy-technical-portfolio):** a React/TypeScript review experience connecting project narratives, actual application previews, public source, tests and implementation boundaries. [Visit the website](https://amy-villa-signal-gallery.vercel.app/).
- **[Portfolio Assets](https://github.com/Amyvdev1/amy-villa-portfolio-assets):** the supporting visual asset repository for the portfolio.

## A useful five-minute review

1. **Follow the whole integration:** start with SignalOS's payment investigation and compare its report with the source and tests.
2. **Inspect one boundary deeply:** TrustBoundary for approval/idempotency; HookForge for delivery/recovery; DX Orbit for contract findings.
3. **Challenge a decision:** change an assumption in AgentLedger or WorkflowROI, or inspect conflicting evidence in EvidenceGraph.

## Engineering principles

- Make inputs, state transitions and failure paths explicit.
- Validate before acting; keep permission and approval decisions inspectable.
- Test recovery, malformed requests and duplicates alongside the happy path.
- Keep measured behavior, estimates, assumptions and synthetic fixtures distinguishable.
- Document what runs today and what production operation would still require.

**Working stack:** TypeScript · React · Node.js · Python · FastAPI · Pydantic · Zod · REST/OpenAPI · JSON Schema · SQLite · pytest · Vitest · Playwright · Docker · GitHub Actions

**Evidence boundary:** These are independent engineering projects. Simulated payments, agent execution, feedback and onboarding sessions are labelled. Forecasts are not measured savings; tests and local verification do not imply production adoption, scale, authenticated security or customer outcomes. Each repository documents its own implemented scope and limitations.
