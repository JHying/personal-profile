# Hi, I'm Rita 👋

**Senior Backend / Platform Architect** — distributed systems, high availability, and DevOps.

8+ years of industry experience in backend and platform engineering. In recent years I've focused on the architecture side — the decisions that determine whether a system remains fast, maintainable, and operable as it scales and as teams change.

📍 Taiwan · open to **Senior Backend / Platform Architect / Tech Lead** roles.

---

### What I work on

- **Platform architecture & technical leadership** — leading microservice decomposition and cross-cutting technical decisions, from service boundaries and tech selection to deployment safety and data consistency. I've guided teams through system rewrites, abstraction of repeated business flows, and migration trade-offs — and document the reasoning in ADRs so decisions survive beyond the meeting.
- **Observability & operability** — building tracing into systems with OpenTelemetry across the boundaries automatic instrumentation misses (WebSocket, thread pools, schedulers), surfaced through the Grafana stack. A system isn't done until it's debuggable end-to-end.
- **Engineering standards & cross-functional collaboration** — working across Backend, SRE, QA, and PM to formalize practices like schema-as-code, contract testing, and quality gates into repeatable team workflows. Recent focus includes LLM-assisted developer tooling and workflow automation.

### Selected work

Reference projects — each one documents *how I reason*, not just what was built: the decisions, the data, and the operability.

| Repository | What it shows |
|------------|---------------|
| 📐 [**architecture-decision-records**](https://github.com/JHying/architecture-decision-records) | A curated set of MADR-format ADRs from real platform decisions — covering service discovery, container selection (with benchmark data), and repository strategy. Each ADR documents not just the decision, but what was ruled out and why. |
| 🔭 [**distributed-tracing-reference**](https://github.com/JHying/distributed-tracing-reference) | End-to-end OpenTelemetry context propagation across HTTP, WebSocket, thread pools, and schedulers — including a version tag that doubles as W3C baggage and an Istio routing header. |
| 🧩 [**db-as-code**](https://github.com/JHying/db-as-code) | Flagship reference: a schema-as-code workflow with CI gates, squash-mode source of truth, Expand–Contract zero-downtime migrations, and a two-layer Entity↔schema contract test. |
| 🧠 [**knowledge-hub**](https://github.com/JHying/knowledge-hub) | Multi-role AI workshop: Backend, QA, SRE, PM, and Reviewer agents run in parallel on the same story — generating codes, tests, specs, review findings, and deployment notes from their own KB slice via `MASTER_INDEX.md` keyword routing. An `update-kb` skill propagates `pending-file` back into per-project KBs automatically, so accumulated context compounds rather than decays. |

### How I approach systems

- **Evaluate decisions across layers.** Architecture choices ripple — a service boundary decision affects the data layer, the deployment pipeline, and how SRE on-calls at 3 AM. I try to reason through those cross-cutting impacts before they become incidents.
- **Design for the people, not just the traffic.** Fast systems that no one can debug or change safely aren't finished. Traceability, reproducible schema changes, and documented trade-offs are part of the deliverable.
- **Make the reasoning survivable.** Significant choices get an ADR. Practices get written down and turned into team workflows — so the knowledge doesn't leave with the person who made the call.
- **Architecture is a long-term investment.** A system that ships fast but can't be maintained, extended, or trusted under failure isn't a success. I treat maintainability, extensibility, and reliability as first-class concerns — not things to retrofit later.

---

> "The goal of software architecture is to minimize the human resources required to build and maintain the required system." — Robert C. Martin

✉️  Email: ritahying@gmail.com
