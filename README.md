# Hi there 👋 I'm Enjing Jiang

I'm a **master's student at Tsinghua Shenzhen International Graduate School (2025 intake)**, studying Logistics Engineering and Management. I focus on **AI Agent application development, time-series foundation models, and forecasting** — connecting models, software, and business decisions with a product-minded approach.

![Tsinghua SIGS](https://img.shields.io/badge/Tsinghua-SIGS-6B2C91?style=flat-square)
![Research](https://img.shields.io/badge/Research-Time--Series%20Foundation%20Models-3155A4?style=flat-square)
![Forecasting and Optimization](https://img.shields.io/badge/Focus-Forecasting%20%26%20Optimization-187568?style=flat-square)
![AI Agent Engineering](https://img.shields.io/badge/Building-AI%20Agent%20Applications-202938?style=flat-square)

[Agents](#1-ai-agents--application-engineering) · [Forecasting & optimization](#2-forecasting--decision-optimization) · [Product prototypes](#3-product-prototyping--business-design) · [Research](#4-applied-ml--energy-policy-research)

- 🔬 **Currently exploring** forecasting-driven inventory and warehouse allocation for cross-border e-commerce, alongside AI agents for explaining optimization decisions.
- 🤖 **Building my Agent engineering practice through [ServiceMind](https://github.com/jiangenjing/servicemind-agent-demo)** — multi-agent orchestration, RAG, controlled tool calling, layered memory, and evaluation.
- 🧭 **Product-minded:** I start with user workflows and connect technical choices to task completion, reliability, operating cost, and business value.

## Experience & highlights

- 🌉 **UC Berkeley · Spring 2024:** a full-scholarship semester exchange student in the Berkeley Global Access program.
- 🌏 **Dreame Technology · Summer 2026:** overseas GTM intern in the AI Smart Ring business unit, working on market and competitor analysis, value-chain modeling, and pricing scenarios.
- 🎓 **Zhejiang University of Technology · 2025:** earned my bachelor's degree in Industrial Engineering at Jianxing Honors College, and received the **Zhejiang Outstanding Graduate** honor.
- 🏆 **CUMCM 2023 · First Prize, Zhejiang Division:** team leader and modeler for Problem C, connecting fresh-produce sales analysis, forecasting, replenishment, and pricing optimization.

## Projects by focus

### 1. AI Agents & Application Engineering

**[🤖 ServiceMind · Multi-Agent Customer Support](https://github.com/jiangenjing/servicemind-agent-demo)**

Turn a compound support request into intent routing, specialist collaboration, knowledge retrieval, controlled tool execution, and a traceable response.

- **Architecture:** Python / FastAPI, a custom Agent orchestrator, Redis, ChromaDB, and a Vue debugging interface; a Java implementation is included for comparison.
- **Product focus:** preserve conversation context, cover multiple user needs, and make tool outcomes and human-handoff boundaries visible.
- **Explore:** [Architecture & request walkthrough](https://github.com/jiangenjing/servicemind-agent-demo) · [Source & reproduction guide](https://github.com/jiangenjing/servicemind-source-private). Current focus: reproducibility, evaluation, and safe integration; not a hosted production service.

### 2. Forecasting & Decision Optimization

| Project | Problem → approach → available work |
| --- | --- |
| [🥬 CUMCM 2023 · Vegetable Replenishment & Pricing](https://github.com/jiangenjing/cumcm-2023-c-vegetable-replenishment) | Perishable inventory and changing demand → sales analysis, ARIMA / GM(1,1), and replenishment–pricing optimization → team paper, original Python experiments, and detailed method notes. |
| [📦 Fresh-Produce 3D Bin Packing](https://github.com/jiangenjing/fresh-produce-3d-bin-packing) | Constrained loading space → composite blocks, layer placement, and search heuristics → undergraduate thesis, source archive, and [interactive replay of historical results](https://jiangenjing.github.io/fresh-produce-3d-bin-packing/). |

My ongoing master's research asks not only **“Is the forecast accurate?”**, but also **“Does it improve inventory and fulfillment decisions?”**

### 3. Product Prototyping & Business Design

**[⚡ Shell × Hangzhou · AI Energy Brain](https://github.com/jiangenjing/shell-hangzhou-ai-energy-brain)**

A student energy-competition project connecting the driver journey with charging-station operations.

- **User journey:** station discovery → charging match → reservation and charging → membership benefits → preferences and carbon statements.
- **Solution design:** recommendations, power allocation, predictive maintenance, and incremental-benefit targeting, linked to operational metrics and a staged pilot proposal.
- **Business thinking:** distinguish users from buyers; account for integration, operations, and acquisition costs; evaluate incremental contribution rather than clicks alone.
- **Explore:** [Mobile web prototype](http://hawk-knko.upma.site/) · [Technical / business proposal and presentation](https://github.com/jiangenjing/shell-hangzhou-ai-energy-brain). The interface uses demonstration data; proposed AI and financial improvements are not deployed operating results.

### 4. Applied ML & Energy Policy Research

| Publication | Research focus & my role | Explore |
| --- | --- | --- |
| **PLOS ONE · 2025** | **DRN-RF for operator fatigue detection.** Visual features, feature selection, and stacked classification. Co-author; data curation, project administration, visualization, and manuscript preparation. | [Paper](https://doi.org/10.1371/journal.pone.0320780) · [Methods & metric explorer](https://github.com/jiangenjing/drn-rf-fatigue-research) |
| **Energy Policy · 2026** | **On-capacity vs. On-grid.** Evolutionary-game analysis of high-quality storage adoption and subsidy design. Co-author; investigation and validation. | [Paper](https://doi.org/10.1016/j.enpol.2025.114922) · [Code & policy-model explorer](https://github.com/jiangenjing/energy-storage-subsidy-game) |
| **Energy Strategy Reviews · 2026** | **Complementary photovoltaic policy under resource constraints.** Regional classification, statistical comparisons, and policy interpretation. Co-corresponding author; data curation and manuscript preparation. | [Paper](https://doi.org/10.1016/j.esr.2026.102128) · [Research showcase](https://github.com/jiangenjing/photovoltaic-complementary-policy) |

Each repository explains its architecture or method, available materials, reproduction steps, and validation status. Research showcases illustrate methods and findings rather than claiming complete experimental reproduction. The charging prototype is a student project, not an official Shell product.

## How I approach problems

- **Start with the user:** turn a support request or charging pain point into a workflow, including exceptions and human handoff.
- **Connect models to decisions:** consider how forecasts and optimization affect replenishment, allocation, or service delivery — not just model scores.
- **Bring the business context:** apply my overseas GTM experience to market needs, pricing, delivery costs, and adoption; distinguish promising hypotheses from validated outcomes.

---

**Interests:** AI Agent Applications · Time-Series Foundation Models · Forecasting · Optimization · Product Thinking  
**Research tools:** Python · Pandas · NumPy · scikit-learn · Gurobi  
**Agent engineering focus:** FastAPI · RAG · Tool Calling · Redis · ChromaDB · LangGraph
