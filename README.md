# Hi, I'm Rita 👋

**Backend / Platform Architect** — distributed systems, high availability, and DevOps.

8+ years designing and operating high-throughput, microservices platforms. I work on the parts that decide whether a system stays fast, debuggable and changeable as it grows: service boundaries, the data layer, deployment safety, and end-to-end observability.

📍 Taiwan · open to **Backend Architect / Platform Architect / Tech Lead** roles.

---

### What I work on

- **Architecture** — designing and evolving microservices on cloud native technical; knowing when *not* to split, and when *not* to merge back.
- **DB as code** — schema, migrations and infrastructure under version control; zero-downtime deployment and Expand–Contract migrations.
- **Observability** — building tracing into systems with OpenTelemetry across the awkward boundaries (WebSocket, thread pools, schedulers), surfaced through the Grafana stack.
- **AI engineering** — LLM-assisted developer tooling and workflow automation.

### Selected work

Reference projects, each documents *how I reason*, not just what was built — decisions, data, and operability:

| Repository | What it shows |
|------------|---------------|
| 📐 [**architecture-decision-records**](https://github.com/JHying/architecture-decision-records) | A curated set of MADR-format ADRs from real platform decisions — service discovery, container choice (with benchmarks), repository strategy, and when to revert microservices to a monolith. |
| 🔭 [**distributed-tracing-reference**](https://github.com/JHying/distributed-tracing-reference) | End-to-end OpenTelemetry context propagation across HTTP, WebSocket, thread pools and schedulers — including a version tag that doubles as W3C baggage and an Istio routing header. |
| 🧩 [**db-as-code**](https://github.com/JHying/db-as-code) | Flagship reference: a schema-as-code workflow with CI gates, squash-mode source of truth, Expand–Contract zero-downtime migrations, and a two-layer Entity↔schema contract test. |

> Decisions over opinions, data over assertions, honest scope over inflated claims.

### How I approach systems

- **Record the decision.** Architecturally significant choices get an ADR, so "why not X?" is answered once, not relitigated.
- **Make the database consistency.** No manual `ALTER` on a live system — schema changes are reviewed, tested and reproducible like any other code.
- **Trace the whole path.** A request should be followable end-to-end, even through the boundaries automatic instrumentation misses.
- **Be precise about scope.** I describe what I actually owned at each stage, and design for the failure modes rather than the happy path.

---

<!-- Optional: fill these in -->
<!-- 💼 LinkedIn: https://www.linkedin.com/in/your-handle -->
<!-- ✉️  Email: your-email@example.com -->
