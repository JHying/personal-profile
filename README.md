# Hi, I'm Rita 👋

**Senior Backend / Platform Architect** — distributed systems, high availability, and DevOps.

From backend engineer to platform architect, specializing in architectural modernization of large Java systems—from legacy monoliths to observable, maintainable, and evolvable platforms. I enjoy transforming complex systems into maintainable architectures through thoughtful design, reusable abstractions, and operational excellence.

📍 Taiwan · open to **Senior Backend / Platform Architect / Tech Lead** roles.

---

### What I work on

- **Platform architecture & technical leadership** — leading microservice decomposition and cross-cutting technical decisions, from service boundaries and technology selection to deployment safety and data consistency. I approach architecture as a series of long-term trade-offs, documenting important decisions with ADRs so the reasoning survives beyond the meeting.

- **System modernization & large-scale refactoring** — modernizing legacy Java systems by understanding framework internals rather than relying on automated migration tools. I've migrated Servlet-based applications into idiomatic Spring Boot architectures while preserving existing business behavior, and reorganized systems into clear layered architectures where business logic had previously been scattered across multiple layers. During the process, I extracted repeated workflows into reusable abstractions using patterns such as Factory and Aggregator, significantly reducing duplication and improving long-term maintainability and extensibility.

- **Observability & operability** — building end-to-end tracing with OpenTelemetry across the boundaries automatic instrumentation doesn't cover (WebSocket, thread pools, schedulers), surfaced through the Grafana stack. I believe a system isn't finished until it's observable, diagnosable, and operable in production.

- **Engineering standards & developer experience** — collaborating across Backend, SRE, QA, and PM to establish engineering practices such as schema-as-code, contract testing, quality gates, and LLM-assisted development workflows. I enjoy turning repeated engineering tasks into reusable standards that improve consistency across teams.

---

### Selected work

Reference projects — each one documents *how I reason*, not just what was built: the decisions, the trade-offs, and the operational considerations.

| Repository | What it shows |
|------------|---------------|
| 📐 **architecture-decision-records** | A curated collection of MADR-format ADRs covering real platform decisions, including service discovery, container selection (with benchmark data), and repository strategy. Each ADR explains not only the chosen solution, but also the alternatives that were rejected and why. |
| 🔭 **distributed-tracing-reference** | End-to-end OpenTelemetry context propagation across HTTP, WebSocket, thread pools, and schedulers, including a version tag that doubles as W3C baggage and an Istio routing header. |
| 🧩 **db-as-code** | Flagship reference demonstrating schema-as-code with CI quality gates, squash-mode source of truth, Expand–Contract zero-downtime migrations, and a two-layer Entity↔schema contract test. |
| 🧠 **knowledge-hub** | Multi-role AI engineering workflow where Backend, QA, SRE, PM, and Reviewer agents collaborate on the same story using role-specific knowledge bases. Includes automatic KB propagation so project knowledge compounds rather than decays. |

---

### How I approach systems

- **Evaluate decisions across layers.** Architecture decisions ripple across application code, data models, deployment pipelines, and production operations. I try to understand those cross-cutting impacts before they become incidents.

- **Design for people as much as systems.** Fast software that nobody can safely understand, modify, or debug isn't finished. Maintainability, observability, and operational safety are first-class design goals.

- **Reduce duplication through abstraction.** I actively look for repeated business workflows, deployment logic, and infrastructure patterns that can be turned into reusable building blocks. Less duplication means lower maintenance cost and more consistent systems.

- **Modernize instead of mechanically rewriting.** Legacy systems often contain years of accumulated business knowledge. I prefer preserving proven behavior while evolving architecture into cleaner designs rather than performing direct code translation.

- **Make the reasoning survivable.** Important technical decisions deserve documentation. ADRs, architecture diagrams, and engineering standards ensure knowledge stays with the team rather than the individual.

- **Architecture is a long-term investment.** Shipping features is only part of success. I treat maintainability, extensibility, reliability, and operational excellence as core system qualities from the beginning—not after problems appear.

---

# 哈囉，我是 Rita 👋

**資深後端工程師 / 平台架構師** — 專注於分散式系統、高可用性架構與 DevOps。

從後端工程師一直到平台架構師，專精於大型 Java 系統的架構現代化——將老舊的單體式系統，逐步演進為可觀測、易維護、可持續演化的平台。我喜歡透過周全的設計、可重用的抽象化，以及對維運卓越性的堅持，將複雜系統轉化為易於維護的架構。

---

### 我的工作範疇

- **平台架構與技術領導** — 主導微服務拆分與跨團隊的技術決策，涵蓋服務邊界劃分、技術選型、部署安全性與資料一致性等面向。我將架構視為一連串長期的權衡取捨，並透過 ADR（Architecture Decision Record）記錄重要決策，讓決策背後的推理邏輯不會隨會議結束而消失。

- **系統現代化與大規模重構** — 曾透過自身對框架內部機制的深入理解（尚未有自動化 AI 遷移工具）來現代化老舊的 Java 系統。我曾將 Servlet-based 應用程式遷移為符合 Spring Boot 慣例的架構，同時保留原有的商業邏輯行為；也曾將原本散落在多層的商業邏輯重新整理為清晰的分層架構。在這個過程中，我運用 Factory、Aggregator 等設計模式，將重複的工作流程抽象化，大幅降低重複程度，並提升系統的長期可維護性與可擴展性。

- **可觀測性與可維運性** — 建立涵蓋自動化埋點無法觸及邊界（WebSocket、執行緒池、排程器）的端到端 OpenTelemetry 追蹤機制，並透過 Grafana stack 呈現。我相信一個系統唯有具備可觀測、可診斷、可維運的能力，才算真正完成。

- **工程標準與開發者體驗** — 跨 Backend、SRE、QA、PM 團隊協作，建立 schema-as-code、contract testing、品質關卡（quality gates）與 LLM 輔助開發流程等工程實踐。我喜歡將重複發生的工程任務，轉化為可重用的標準，藉此提升團隊間的一致性。

---

### 精選作品

以下為參考專案——每一個都記錄了「我如何思考」，而不只是「做了什麼」：包含決策過程、權衡取捨，以及維運面的考量。

| Repository | 展示內容 |
|------------|---------------|
| 📐 **architecture-decision-records** | 精選的 MADR 格式 ADR 集合，涵蓋真實的平台決策，包括服務發現機制、底層 web 容器選型（附上 benchmark 數據）與 repository 策略。每篇 ADR 不僅說明最終方案，也詳述被否決的替代方案及其原因。 |
| 🔭 **distributed-tracing-reference** | 涵蓋 HTTP、WebSocket、執行緒池與自啟動排程的端到端 OpenTelemetry context 傳遞機制，其中版本標籤同時作為 W3C baggage 與 Istio 路由標頭使用。 |
| 🧩 **db-as-code** | 展示 schema-as-code 搭配 CI 品質檢測、squash-mode 整合成單一事實來源（source of truth）、Expand–Contract 零停機遷移，以及兩層式 Entity↔schema contract test。 |
| 🧠 **knowledge-hub** | 個人的多角色 AI 工程協作庫，基於 SA、Backend、QA、SRE、PM 與 Reviewer agent 等各自角色的工作流，針對同一個 story 協同工作，除了將軟體從開發、review 到測試的流程自動化，也內建自動 KB 建立機制，讓專案知識得以持續累積，而非隨時間流失。 |

---

### 我的系統設計理念

- **跨層評估決策影響。** 架構決策會影響應用程式碼、資料模型、部署流程與維運端，我會在這些影響演變成事故之前，先理解它們之間的關聯性。

- **為人設計，也為系統設計。** 快速卻沒有人能安全理解、修改、除錯的軟體，稱不上「完成」。可維護性、可觀測性與維運安全性，是我設計時的首要考量。

- **透過介面抽象化減少重複。** 我會主動尋找重複的商業流程、部署邏輯與基礎設施模式，將它們轉化為可重用的元件。減少重複意味著更低的維護成本，以及更一致的系統行為。

- **演進而非機械式重寫。** 老舊系統往往蘊含多年累積的商業知識。相較於直接請 AI 進行程式碼轉譯，我更傾向在保留既有行為與業務運作的前提下，逐步演進出更乾淨的架構。

- **讓推理過程得以留存。** 重要的技術決策值得被記錄下來。ADR、架構圖與工程標準，讓知識留在團隊裡，而不是只存在於個人腦中。

- **架構是長期投資。** 交付功能只是成功的一部分。我從一開始就將可維護性、可擴展性、可靠性與維運卓越性，視為系統的核心特質——而不是等問題出現後才補救。

---

> "The goal of software architecture is to minimize the human resources required to build and maintain the required system." — Robert C. Martin

I view refactoring as architectural evolution rather than code cleanup—making systems easier to understand, extend, and operate without changing what the business depends on.

重構是架構的演進，而不只是程式碼的整理：在讓系統更容易被理解、擴展與維運的同時，又不改變原本商業邏輯的行為與底層設計。

✉️ Email: ritahying@gmail.com