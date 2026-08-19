[English](#english) | [繁體中文](#繁體中文)

---

## 繁體中文

# 哈囉，我是 Rita 👋

**資深後端工程師 / 平台架構師** — 10 年以上軟體開發資歷，專注於高可用分散式系統、雲原生平台建置與開發架構治理。

從後端工程師一直到平台架構師，專精於大型 Java 系統的架構現代化——將老舊的單體式系統，逐步演進為可觀測、易維護、可持續演化的平台。我喜歡透過周全的設計、可重用的抽象化，以及對維運卓越性的堅持，將複雜系統轉化為易於維護的架構。

`Java` · `Spring Boot / Spring Cloud` · `Kubernetes · Istio` · `Kafka · Redis` · `Oracle · MongoDB` · `OpenTelemetry · Grafana Stack` · `GitLab CI · ArgoCD · Terraform`

---

### 我的工作範疇

- **平台架構與技術選型** — 微服務拆分與跨團隊的技術決策，涵蓋服務邊界劃分、技術選型、部署安全性與資料一致性等面向。我將架構視為一連串長期的權衡取捨，並透過 ADR（Architecture Decision Record）記錄重要決策，讓決策背後的推理邏輯不會隨會議結束而消失。

- **雲原生平台與維運建置** — 從零建立 Kubernetes 叢集維運架構、CI/CD 與 GitOps 佈署流程、Vault 機敏治理、服務網格與 IaC 災難復原機制，並將各環境的部署與自測流程文件化。我習慣把「哪個團隊負責哪一層」一併寫清楚，讓責任邊界跟系統邊界一樣明確。

- **系統現代化與大規模重構** — 在 AI 輔助開發工具問世之前，僅憑對框架內部機制的理解，逐段人工完成老舊 Java 系統的重構遷移。我曾將 Servlet-based 應用程式遷移為符合 Spring Boot 慣例的架構，同時保留原有的商業邏輯行為；也曾將原本散落在多層的商業邏輯重新整理為清晰的分層架構。在這個過程中，我運用 Factory、Aggregator 等設計模式，將重複的工作流程抽象化，大幅降低重複程度，並提升系統的長期可維護性與可擴展性。遷移期間原分支仍持續迭代，沒有任何自動轉換工具可以依靠，整個過程是比對原分支 commit log 人工分批移植、逐項驗證商業邏輯無落差完成的。

- **可觀測性與可維運性** — 建立涵蓋自動化埋點無法觸及邊界（WebSocket、執行緒池、排程器）的端到端 OpenTelemetry 追蹤機制，並透過 Grafana stack 呈現。我相信一個系統唯有具備可觀測、可診斷、可維運的能力，才算真正完成。

- **工程標準與開發者體驗** — 跨 Backend、SRE、QA、PM 團隊協作，建立 DDD 分層規範、ArchUnit 架構檢查、schema-as-code、contract testing 與品質關卡（quality gates）。我喜歡將重複發生的工程任務轉化為可重用的標準，並盡可能讓規範從人工 review 併入 CI——寫在文件裡的規範會被遺忘，寫進 CI 的不會。

- **AI Engineering 與知識傳承** — 自建跨專案共用的 Spec-Driven SDLC 開發工作坊：串接多個自製 Skill 與角色 subagent 分工，內建 AI 自測自審機制確保產出對齊驗收條件與工程規範，同時自動產出 spec、program flow、ADR、review 與 QA 等專案知識文件。另落地 MCP、Local LLM 與 n8n 工作流做日常報告整理，讓 AI 不只加速實作，也負責讓專案知識持續累積。

---

### 精選作品

| Repository                                                                                          | 展示內容                                                                                                                                                                                                                 |
| --------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🧠 [**engineering-hub-showcase**](https://github.com/JHying/engineering-hub-showcase)               | 把 AI 輔助開發當成一套需要被工程化的系統來設計：涵蓋需求、規格、實作、審查到測試的 Spec-Driven SDLC pipeline，階段之間交接的是檔案而非對話，知識庫同時是每個階段的輸入與輸出。收錄設計決策與被否決的方案、一張票走完五階段的完整產物鏈，以及真實的踩雷紀錄。<br>*源自：日常開發流程的自動化需求。經多次 harness 優化後，同一訂閱方案的每日額度從 3~5 小時用完變成整個工作日沒用完過。* |
| 🧭 [**architecture-decisions-showcase**](https://github.com/JHying/architecture-decisions-showcase) | 八則 ADR 架構決策紀錄。重點不在最後選了什麼，而在當時的約束、評估過哪些選項、為什麼否決它們、付出的代價，以及大多數決策紀錄會漏掉的一項：這個決策靠什麼確認真的被遵守。挑選標準不是「最重要的架構」，而是每一則各展示一種不同的推理方式，並且都是通用技術標準。<br>*這只是選樣展示，不是全集：原始紀錄皆生成自上述 AI 工作坊，經過去識別化後展示，閱讀起來可能比較抽象。*                         |
| 🔭  [**distributed-tracing-reference**](https://github.com/JHying/distributed-tracing-reference)    | 涵蓋 HTTP、WebSocket、執行緒池與自啟動排程的端到端 OpenTelemetry context 傳遞機制，其中版本標籤同時作為 W3C baggage 與 Istio 路由標頭使用。<br>*源自：OTel Java Agent 不支援 WebSocket instrumentation 造成的鏈路斷鏈，最終以自訂 annotation + AOP 收斂為共用套件。*                     |
| 🧩 [**db-as-code**](https://github.com/JHying/db-as-code)                                           | 展示 schema-as-code 搭配 CI 品質檢測、squash-mode 整合成單一事實來源（source of truth）、Expand–Contract 零停機遷移，以及兩層式 Entity↔schema contract test。<br>*參考實作：驗證於本地與 CI 環境，尚未在線上系統實戰。源自多服務環境下 DB 變更缺乏統一事實來源與零停機遷移策略的問題。*                     |

---

### 我的系統設計理念

- **跨層評估決策影響：** 架構決策會影響應用程式碼、資料模型、部署流程與維運端，我會在這些影響演變成事故之前，先理解它們之間的關聯性。

- **為人設計，也為系統設計：** 快速卻沒有人能安全理解、修改、除錯的軟體，稱不上「完成」。可維護性、可觀測性與維運安全性，是我設計時的首要考量。

- **透過介面抽象化減少重複：** 我會主動尋找重複的商業流程、部署邏輯與基礎設施模式，將它們轉化為可重用的元件。減少重複意味著更低的維護成本，以及更一致的系統行為。

- **重構是架構的演進，不只是程式碼的整理：** 老舊系統往往蘊含多年累積的商業知識，相較於直接請 AI 進行程式碼轉譯，我更傾向在保留既有行為與業務運作的前提下，逐步演進出更乾淨的架構。

- **讓推理決策過程得以留存：** 重要的技術決策值得被記錄下來，包括 ADR、架構圖與工程標準，讓知識留在團隊裡，而不是只存在於個人腦中。

- **架構是長期投資：** 交付功能只是成功的一部分，我從一開始就將可維護性、可擴展性、系統可靠性與維運卓越性，視為系統的核心與一切基礎——保障系統能安全穩定地被快速迭代。

---

> "The goal of software architecture is to minimize the human resources required to build and maintain the required system." — Robert C. Martin

✉️ Email: ritahying@gmail.com

---

## English

# Hi, I'm Rita 👋

**Senior Backend Engineer / Platform Architect** — 10+ years in software, focused on high-availability distributed systems, cloud-native platform build-out, and engineering governance.

From backend engineer to platform architect, specializing in architectural modernization of large Java systems—from legacy monoliths to observable, maintainable, and evolvable platforms. I enjoy transforming complex systems into maintainable architectures through thoughtful design, reusable abstractions, and operational excellence.

`Java` · `Spring Boot / Spring Cloud` · `Kubernetes · Istio` · `Kafka · Redis` · `Oracle · MongoDB` · `OpenTelemetry · Grafana Stack` · `GitLab CI · ArgoCD · Terraform`

---

### What I work on

- **Platform architecture & technology selection** — microservice decomposition and cross-team technical decisions: service boundaries, technology selection, deployment safety, data consistency. I approach architecture as a series of long-term trade-offs and record the important ones as ADRs, so the reasoning doesn't disappear when the meeting ends.

- **Cloud-native platform & operations build-out** — building Kubernetes cluster operations, CI/CD and GitOps delivery, Vault-based secrets governance, service mesh, and IaC disaster recovery from zero, with every environment's deployment and self-test documented. I make a point of writing down which team owns which layer, so ownership boundaries are as explicit as system boundaries.

- **System modernization & large-scale refactoring** — before AI-assisted development tooling existed, I modernized legacy Java systems section by section on nothing but an understanding of framework internals. I migrated Servlet-based applications into idiomatic Spring Boot architectures while preserving existing business behavior, and reorganized logic that had been scattered across layers into a clear layered architecture, extracting repeated workflows into reusable abstractions with patterns such as Factory and Aggregator. The source branch kept shipping throughout and no automated conversion tool was available, so the port ran in batches against that branch's commit log, verifying business-logic parity item by item.

- **Observability & operability** — building end-to-end tracing with OpenTelemetry across the boundaries automatic instrumentation doesn't cover (WebSocket, thread pools, schedulers), surfaced through the Grafana stack. I believe a system isn't finished until it's observable, diagnosable, and operable in production.

- **Engineering standards & developer experience** — collaborating across Backend, SRE, QA, and PM to establish DDD layering rules, ArchUnit architecture checks, schema-as-code, contract testing, and quality gates. I enjoy turning recurring engineering work into reusable standards, and moving standards from manual review into CI wherever possible — a rule written in a document gets forgotten; a rule written into CI doesn't.

- **AI Engineering & knowledge transfer** — a self-built cross-project Spec-Driven SDLC workshop: custom skills chained with role-specific subagents, with built-in AI self-testing and self-review keeping output aligned with acceptance criteria and engineering standards, while automatically emitting spec, program flow, ADR, review, and QA documents as project knowledge. Also shipped MCP, local LLMs, and n8n workflows for daily reporting — so AI not only speeds up implementation but keeps project knowledge compounding.

---

### Selected work

| Repository                                                                                          | What it shows                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| --------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🧠 [**engineering-hub-showcase**](https://github.com/JHying/engineering-hub-showcase)               | Treating AI-assisted development as a system to be engineered: a Spec-Driven SDLC pipeline spanning requirements, spec, implementation, review, and testing, where stages hand off files rather than conversation and the knowledge base is both the input and the output of every stage. Includes the design decisions with their rejected alternatives, one ticket's full artifact chain through all five stages, and the recorded failures.<br>*Origin: the need to automate my own development workflow. After successive harness optimizations, the daily quota on the same subscription went from being exhausted in 3-5 hours to never being reached across a full working day.*                                    |
| 🧭 [**architecture-decisions-showcase**](https://github.com/JHying/architecture-decisions-showcase) | Eight architecture decision records from a high-concurrency platform. What was picked is the least interesting part: what matters is the constraints in force at the time, which options were evaluated, why the others were rejected, what the choice cost, and the one thing most decision records omit — how compliance is actually confirmed. The selection criterion was not "the most important architecture" but that each record demonstrates a different mode of reasoning, and all of them are general engineering practice.<br>*A selection, not the full set: the original records were all produced by  my engineering hub, and are shown here de-identified — which can make some of them read as abstract.* |
| 🔭  [**distributed-tracing-reference**](https://github.com/JHying/distributed-tracing-reference)    | End-to-end OpenTelemetry context propagation across HTTP, WebSocket, thread pools, and self-triggered schedulers, including a version tag that doubles as W3C baggage and an Istio routing header.<br>*Origin: broken traces caused by the OTel Java agent not instrumenting WebSocket, resolved by collapsing the fix into a shared library built on a custom annotation plus AOP.*                                                                                                                                                                                                                                                                                                                                       |
| 🧩 [**db-as-code**](https://github.com/JHying/db-as-code)                                           | Demonstrates schema-as-code with CI quality checks, squash-mode consolidation into a single source of truth, Expand–Contract zero-downtime migrations, and a two-layer Entity↔schema contract test.<br>*Reference implementation — validated locally and in CI, not yet proven on a production system. Origin: DB changes across multiple services having no single source of truth and no zero-downtime migration strategy.*                                                                                                                                                                                                                                                                                              |


---

### How I approach systems

- **Evaluate decisions across layers.** Architecture decisions ripple across application code, data models, deployment pipelines, and production operations. I try to understand those cross-cutting impacts before they become incidents.

- **Design for people as much as systems.** Fast software that nobody can safely understand, modify, or debug isn't finished. Maintainability, observability, and operational safety are first-class design goals.

- **Reduce duplication through interface abstraction.** I actively look for repeated business workflows, deployment logic, and infrastructure patterns that can be turned into reusable building blocks. Less duplication means lower maintenance cost and more consistent systems.

- **Refactoring is architectural evolution, not code cleanup.** Legacy systems often carry years of accumulated business knowledge. Rather than having AI translate code directly, I prefer to evolve a cleaner architecture while preserving proven behavior — making a system easier to understand, extend, and operate without changing what the business logic does.

- **Make the reasoning survivable.** Important technical decisions deserve documentation. ADRs, architecture diagrams, and engineering standards ensure knowledge stays with the team rather than the individual.

- **Architecture is a long-term investment.** Shipping features is only part of success. From the start I treat maintainability, extensibility, reliability, and operational excellence as the core of a system and the basis for everything else — what keeps it safe to iterate on quickly.

---

> "The goal of software architecture is to minimize the human resources required to build and maintain the required system." — Robert C. Martin

✉️ Email: ritahying@gmail.com
