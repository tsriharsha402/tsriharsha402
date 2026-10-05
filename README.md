<h1 align="center">Hi, I'm Sriharsha T 👋</h1>

<h3 align="center">Senior Backend Engineer → building production-grade LLM systems</h3>

<p align="center">
  <em>Reliable. Measurable. Worth what they cost.</em>
</p>

<!-- LinkedIn placeholder: replace YOUR-HANDLE with your profile handle, then delete this line and the closing arrow below
<p align="center">
  <a href="https://www.linkedin.com/in/YOUR-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>
-->

---

I've spent my career building backend systems that have to stay up, scale, and stay cheap to run. Now I'm bringing that same discipline to AI: **LLM applications that hold up in production, not just in demos.**

My goal is to lead engineering teams that ship AI to real users, safely and measurably.

## 🎯 What I focus on

| | |
|---|---|
| **Production LLM systems** | RAG services, tool-using agents and APIs designed for latency, reliability and cost from day one |
| **Evaluation-driven delivery** | Every AI feature ships with an eval suite in CI. Quality is measured, not guessed |
| **Decisions with tradeoffs** | Model selection, build vs. buy and risk, written down as decision records |
| **Enabling teams** | Playbooks, templates and practices that help teams deliver AI with confidence |

## 🚧 Building in public

I'm building a portfolio of production-minded AI projects. Each one ships with an executive summary, architecture diagram, eval results, cost analysis and decision records.

| Project | What it demonstrates | Status |
|---|---|---|
| **[production-rag-service](https://github.com/tsriharsha402/production-rag-service)** | RAG API with verifiable citations, caching, rate limiting, a 46-question eval suite gating CI and per-request cost tracking | ✅ v0.1 shipped · Claude eval: 84.8% pass, 0 invented answers, $0.009/question |
| **[llm-model-selection](https://github.com/tsriharsha402/llm-model-selection)** | Benchmarking Claude configurations on quality, latency and cost with confidence intervals and a pre-registered decision rule, ending in a one-page recommendation memo | ✅ Recommends Sonnet 5.5 (low effort): same pass rate as Opus 5.5 on this test set, 56% cheaper, faster · 225 calls, $1.28 |
| **[reliable-agent](https://github.com/tsriharsha402/reliable-agent)** | Tool-using agent with layered guardrails (human approval for writes, rules in code, budgets, loop detection), full tracing and a 14-scenario eval incl. prompt injection | ✅ Live eval: 14/14 scenarios incl. prompt injection, $0.33 total |
| **[ai-delivery-playbook](https://github.com/tsriharsha402/ai-delivery-playbook)** | Lifecycle, risk tiers and 9 templates (feature brief, eval plan, risk assessment, launch readiness, AI incident postmortem…), applied end to end to production-rag-service | ✅ v1 shipped |
| **[ai-team-leadership](https://github.com/tsriharsha402/ai-team-leadership)** | Hiring for AI teams (competency matrix, interview loop, question bank with scoring anchors), onboarding, a 30-60-90 day plan, operating model and roadmap | ✅ v1 shipped |

## 💡 How I work

1. **No eval, no launch.** If we can't measure quality, we can't ship it or improve it.
2. **Cost is a feature.** Track $/request from the first prototype, not after the bill arrives.
3. **Write decisions down.** Future teammates deserve to know *why*, not just *what*.
4. **Boring infrastructure, interesting products.** Reliability first, then novelty.

## 🧰 Toolbox

**Languages & frameworks**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Data & infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL_+_pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)

**AI engineering**

![LLM APIs](https://img.shields.io/badge/LLM_APIs-412991?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-6A1B9A?style=flat-square)
![Embeddings & Vector Search](https://img.shields.io/badge/Embeddings_&_Vector_Search-00897B?style=flat-square)
![Agents](https://img.shields.io/badge/Agents_&_Tool_Use-C2185B?style=flat-square)
![LLM Evals](https://img.shields.io/badge/LLM_Evaluation-F57C00?style=flat-square)
![Guardrails](https://img.shields.io/badge/Guardrails_&_Safety-455A64?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

## 📈 Right now

- 🔭 Running live evaluations across my projects, then adding hybrid retrieval to **production-rag-service**
- 🌱 Going deep on LLM evaluation, agent reliability and AI product delivery
- 💬 Ask me about backend architecture, APIs and scaling systems, and how those lessons apply to LLMs

---

<p align="center"><sub>Building AI that works on Monday morning, not just in the demo.</sub></p>
