# Sreenath Tella

**Applied AI Engineer — agentic systems that run in production, inside large enterprises.**

I build multi-agent workflows, RAG pipelines, and LLM evaluation harnesses that real business teams use every day — not demos. Twelve years of enterprise engineering across telecom, healthcare, insurance, and federal, where reliability, security review, and data governance aren't optional. The last two years, all-in on agentic AI.

📍 Open to relocation · 🔗 [LinkedIn](https://www.linkedin.com/in/sreenathtella) · 🌐 [thinkingx.org](https://thinkingx.org) · ✉️ sreenath.aieng@gmail.com

---

## What I'm doing now

**Agentic AI Engineer @ AT&T** — Own end-to-end design, build, and production deployment of an Azure-based multi-agent platform automating legacy copper-circuit validation and reclaim across **7 OSS/BSS systems**. A genuinely ambiguous 0-to-1 problem: no clean schema, no single source of truth, real regulatory consequences for getting it wrong.

- LangGraph multi-agent orchestration with parallel retrieval, confidence-based routing, and human-in-the-loop review checkpoints — cut validation cycle time from hours to minutes
- Production-safe NL2SQL over large-scale operational data: dynamic schema injection, static SQL validation, code-enforced safety gates
- Entity-resolution agents reconciling inconsistent identifiers across legacy systems
- Per-agent KPIs and full observability — traces, prompt behavior, retrieval quality, cost per task — via Arize + Azure App Insights

---

## Things I've shipped

| | What it is | Stack |
|---|---|---|
| **Multi-agent OSS/BSS validation platform** | Autonomous circuit validation across 7 legacy systems, with guardrails and HITL escalation. In production at AT&T. | LangGraph · Azure OpenAI · FastAPI · Arize |
| **Order-to-cash agent platform** | Multilingual PO extraction → SKU matching → compliance validation → automated order creation, Salesforce as system of record. In production at Abbott. | Agentforce · LangGraph · OpenAI · Service Cloud |
| **Hybrid RAG + eval harness** | Dense + BM25 retrieval with cross-encoder re-ranking; golden datasets, LLM-as-judge, Langfuse tracing catching regressions pre-release. | Python · Langfuse · Qdrant |
| **MCP tool servers** | Model Context Protocol servers exposing external tools and data to LLM agents — schema design, auth, safe action boundaries. | Python · MCP |
| **Self-hosted AI knowledge base + meeting assistant** | Private AnythingLLM deployment I use daily: document ingestion, embeddings, retrieval, plus transcription → summarization → action items. Runs entirely on infrastructure I control. | AnythingLLM · embeddings · self-hosted |

---

## How I think about agentic systems

A few opinions, since you'll find out anyway:

- **Evals before autonomy.** If you can't measure it, you can't safely let it act. Golden datasets and LLM-as-judge go in on day one, not after the first incident.
- **Deterministic where it matters.** Not every step needs a model. The best agentic systems are mostly boring code with judgment applied narrowly.
- **Human-in-the-loop is a design decision, not a fallback.** Put the checkpoint where the cost of being wrong is highest, and nowhere else.
- **Most enterprise AI projects die in security review, not in the notebook.** Design for data classification and audit from the first sketch and you skip that death.
- **Adoption is the deliverable.** A workflow nobody uses automated nothing.

---

## Stack

**Agentic & LLM** — LangGraph · LangChain · Model Context Protocol (MCP) · multi-agent orchestration · tool use / function calling · structured outputs · prompt & context engineering · Anthropic Claude (API, Claude Code) · Azure OpenAI · OpenAI · Agentforce

**Evals & guardrails** — Golden datasets · LLM-as-judge · regression evals · faithfulness scoring · prompt-drift monitoring · PII detection & masking · Langfuse · LangSmith · Arize

**Retrieval** — Hybrid search (dense + BM25) · cross-encoder re-ranking · semantic chunking · citation-grounded generation · Qdrant · FAISS · ChromaDB · Azure AI Search

**Engineering** — Python · FastAPI · SQL · PySpark · Databricks · Docker · Redis · GitHub Actions · Azure Container Apps · APIM · Key Vault

**Enterprise integration** — Salesforce (Sales/Service Cloud, CPQ, Data Cloud, Agentforce, Apex, LWC) · Apttus/Conga CLM · MuleSoft · OSS/BSS platforms · REST APIs

---

## Track record

Twelve years, mostly inside organizations where a bad deploy has consequences.

**AT&T** · Agentic AI Engineer · 2025–present
**Abbott** · Applied AI Engineer, GTM Order Automation · 2024–2025
**USDA** · Sr. Solutions Architect, Salesforce & Data · 2022–2024 — cut manual case-intake time 60%
**Guidewire** · Sr. Salesforce Engineer, Sales Ops / CPQ · 2022 — improved quote turnaround 30%
**Verizon** · Salesforce Solution Engineer, Contract Lifecycle · 2019–2021 — cut contract generation time 45%
**Farmers Insurance** · Sr. Salesforce Lightning Developer · 2017–2019 — lifted user adoption 40%+
**Sunrun** (via Arc Solutions) · Salesforce Application Developer · 2017
**DXC Technology** · Salesforce Consultant · 2013–2015

**Certifications** — NVIDIA Certified Professional: Agentic AI · NVIDIA Building AI Agents with Multimodal Models · AWS Certified Developer – Associate · AWS Certified AI Practitioner *(in progress)* · Salesforce Certified Data 360 Consultant

---

## What I'm looking for

Hard problems in agentic systems, forward-deployed AI, and the infrastructure the next wave of software runs on — at companies where AI has to survive contact with a real organization.

If you're hiring for that, or you're a founder trying to get an agentic system past the prototype wall, I'd like to talk.

**[LinkedIn](https://www.linkedin.com/in/sreenathtella)** · **sreenath.aieng@gmail.com** · **[thinkingx.org](https://thinkingx.org)**
