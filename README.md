[中文版本](https://github.com/jiangenjing/jiangenjing/blob/main/README.zh-CN.md)

# Hi, I'm Enjing Jiang 👋

🎓 **Tsinghua SIGS · Master's student, 2025 intake** | 🤖 **AI Agent application development** | 📍 **Shenzhen**

I build and study AI applications for customer support, supply-chain decisions, and energy operations — turning user needs into explainable workflows, prototypes, and evaluation plans.

My research focuses on **time-series foundation models and forecasting**. With a background in **Industrial Engineering, Logistics Engineering and Management, and overseas GTM**, I care about both how a system works and why someone would use it.

[📕 Xiaohongshu / 小红书](https://xhslink.cn/o/Aym0oPhPO59) · [💬 WeChat / 微信](#connect)

## 🏆 Featured project · OntoCare — Anker Customer Service Track Champion

**[Source and full documentation](https://github.com/jiangenjing/anker-OntoCare)** · **[Live demo](https://web-production-195cd.up.railway.app/)** · **[Visual project tour](https://jiangenjing.github.io/anker-OntoCare/docs/%E5%8F%82%E8%B5%9B%E6%8F%90%E4%BA%A4%E8%AF%B4%E6%98%8E-%E6%96%B0%E5%A2%9E%E8%A1%A5%E5%85%85%E7%89%88%E6%9C%AC.html)** · **[Watch the demo videos](https://jiangenjing.github.io/anker-OntoCare/docs/%E8%A7%86%E9%A2%91%E6%BC%94%E7%A4%BA.html)**

**Champion, Customer Service Track · Anker inaugural hackathon.**

I built OntoCare for the Anker hackathon to connect customer support with evidence-based business analysis. The customer view handles ambiguous product names, image/video clues, candidate orders, and cited troubleshooting answers. The merchant view turns individual emails and groups of support tickets into reviewable actions. The central questions are **where the evidence came from, which business rules constrain an action, and how failures are found and corrected**.

| Core design | What it does |
| --- | --- |
| **Service + Decision Ontology** | Links products, orders, knowledge, and evidence, then applies explicit decision rules to scope retrieval and permitted actions. The current demo uses JSON relationships and Python rules; policy changes still need code review and regression testing. |
| **Bad-case improvement loop** | Uses multi-turn persona challenges, deterministic assertions, and LLM-as-Judge to identify failures. A human reviews knowledge or rule changes before regression testing; user feedback is a signal, not an automatic truth label. |
| **Business attribution agent** | Analyzes **63 de-identified ticket snapshots** and produces candidate investigation actions linked to source spreadsheet rows, ticket text, and rule IDs. |

**Recorded evaluation:** single-run core-task hard-assertion passes went from **62/74** to **73/74** after fixes. A separate historical latency run recorded **P50 2.63 s / P95 9.00 s**. These demo measurements do not establish an eight-turn resolution rate or production cost. [Read the measurement scope and raw results](https://github.com/jiangenjing/anker-OntoCare#评测结果与口径).

[![OntoCare architecture](https://raw.githubusercontent.com/jiangenjing/anker-OntoCare/main/OntoCare/docs/assets/ontocare-technical-architecture.png)](https://github.com/jiangenjing/anker-OntoCare/blob/main/OntoCare/docs/assets/ontocare-technical-architecture.png)

*Click to enlarge. The diagram includes the pitch design; the repository README and source code define the implemented scope.*

## Featured projects

[Agent applications](#1-agent-applications) · [Forecasting & optimization](#2-forecasting--optimization) · [Product & business](#3-product--business) · [Research](#4-applied-ml--energy-research)

### 1. Agent applications

🤖 **[OntoCare](https://github.com/jiangenjing/anker-OntoCare)** — Featured above: ontology-scoped support, traceable business attribution, and an evaluation-driven improvement loop. [Live demo](https://web-production-195cd.up.railway.app/) · [Architecture](https://github.com/jiangenjing/anker-OntoCare#技术架构).

🤖 **[ServiceMind](https://github.com/jiangenjing/servicemind-agent-demo)** — Multi-Agent customer support with intent routing, RAG, controlled tool calling, layered memory, and request traces. Python / FastAPI, Redis, ChromaDB, and Vue; a Java implementation is also available. [Architecture](https://github.com/jiangenjing/servicemind-agent-demo) · [Source & setup](https://github.com/jiangenjing/servicemind-source-private).

### 2. Forecasting & optimization

🥬 **[Vegetable Replenishment & Pricing](https://github.com/jiangenjing/cumcm-2023-c-vegetable-replenishment)** — Connect sales analysis and ARIMA / GM(1,1) forecasting to replenishment–pricing decisions. **CUMCM 2023 · First Prize, Zhejiang Division**; team paper and original Python experiments.

📦 **[Fresh-Produce 3D Bin Packing](https://github.com/jiangenjing/fresh-produce-3d-bin-packing)** — Undergraduate thesis exploring composite blocks, layer placement, and search heuristics for constrained loading. [Historical-results demo](https://jiangenjing.github.io/fresh-produce-3d-bin-packing/) · [Thesis & code](https://github.com/jiangenjing/fresh-produce-3d-bin-packing).

### 3. Product & business

⚡ **[Shell × Hangzhou · AI Energy Brain](https://github.com/jiangenjing/shell-hangzhou-ai-energy-brain)** — A charging-service prototype linking station discovery, charging, and membership benefits with an AI operations proposal, pilot design, and ROI scenarios. [Mobile demo](http://hawk-knko.upma.site/) · [Presentation & technical proposal](https://github.com/jiangenjing/shell-hangzhou-ai-energy-brain).

### 4. Applied ML & energy research

- **[DRN-RF fatigue detection](https://github.com/jiangenjing/drn-rf-fatigue-research)** · PLOS ONE, 2025 — Visual features and stacked classification. Co-author; data curation, project administration, visualization, and writing. [Paper](https://doi.org/10.1371/journal.pone.0320780).
- **[Storage subsidy design](https://github.com/jiangenjing/energy-storage-subsidy-game)** · Energy Policy, 2026 — Evolutionary-game analysis of high-quality storage adoption. Co-author; investigation and validation. [Paper](https://doi.org/10.1016/j.enpol.2025.114922).
- **[Complementary photovoltaic policy](https://github.com/jiangenjing/photovoltaic-complementary-policy)** · Energy Strategy Reviews, 2026 — Regional classification and policy interpretation under resource constraints. Co-corresponding author; data curation and writing. [Paper](https://doi.org/10.1016/j.esr.2026.102128).

*Project status: ServiceMind provides source and reproduction documentation, not a hosted production service. The charging demo is a student prototype with example data, not an official Shell product. Research pages distinguish historical results, method illustrations, and experiments still to reproduce.*

## Internship · Dreame Technology

**AI Smart Ring BU · Overseas GTM Data Analysis Intern · Jun–Aug 2026**  
[View the interactive portfolio](https://jiangenjing.github.io/dreame-gtm-portfolio/) · [Source & documentation](https://github.com/jiangenjing/dreame-gtm-portfolio)

- **Market and user research:** structured brand websites, retail listings, public reviews and industry materials into competitor matrices, user segments, and positioning hypotheses; presented findings in an interactive HTML research board.
- **Regional GTM planning:** compared market, channel and entry requirements, translating research into regional proposals, partner materials and questions to validate before launch.
- **Commercial modeling:** built interactive value-chain and pricing scenarios to examine product costs, channel allocation, taxes, fees and margin sensitivity.
- **Reporting and AI workflows:** organized business updates into management reports and explored AI-assisted daily summaries and a GTM Agent prototype, with human verification of facts and decisions.

The public portfolio presents work methods and deliverable types; the original research snapshot includes assumptions and information that needs rechecking.

## What I'm working on

- **Agent engineering:** developing OntoCare and ServiceMind around evidence retrieval, rule-constrained actions, tool traces, and evaluation.
- **Forecasting → decisions:** researching time-series foundation models for cross-border e-commerce demand and warehouse allocation, including agents that explain optimization decisions.

## How I think about products

**User need → workflow → technical design → measurable outcome.**

- **ServiceMind:** a useful response should resolve the request or make the next step clear — not merely sound fluent.
- **Charging services:** recommendations should consider the driver's time and reliability, while proposed growth also accounts for incentives and delivery costs.
- **Supply-chain research:** forecast quality matters through its effect on inventory, fulfillment, and operational decisions.

## Experience & highlights

- 🌉 **UC Berkeley · Spring 2024** — Full-scholarship semester exchange, Berkeley Global Access.
- 🌏 **Dreame Technology · Jun–Aug 2026** — Overseas GTM Data Analysis Intern, AI Smart Ring BU. [Interactive portfolio & internship review](https://jiangenjing.github.io/dreame-gtm-portfolio/).
- 🎓 **Zhejiang University of Technology · 2025** — Industrial Engineering, Jianxing Honors College; Zhejiang Outstanding Graduate.
- 🏆 **CUMCM 2023** — Team leader and modeler; First Prize, Zhejiang Division.

**Research tools:** Python · Pandas · NumPy · scikit-learn · Gurobi  
**Agent engineering focus:** FastAPI · RAG · Tool Calling · Redis · ChromaDB · LangGraph

## Connect

📕 **[Xiaohongshu / 小红书](https://xhslink.cn/o/Aym0oPhPO59)** — 4,715 followers · September 2026.  
💬 **WeChat / 微信:** `asphalt2024` — please mention **GitHub** when adding me / 添加时请备注 GitHub。

Happy to connect about AI Agent applications, forecasting and optimization, product ideas, and research collaboration.
