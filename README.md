# Hey, I'm Sebastian 👋

**AI Product Manager** | Retrieval, Agents & Evaluation | Finance & Data Background

Certified AI Project Manager (neuefische x SPICED, 2025/26), after eight and a half years at A.P. Moller – Maersk and Safmarine — three and a half owning enterprise key accounts, five as a Finance Analyst in business partnering.

I care about one question more than any other: **how do you know the thing actually got better?**
Most of what's here is an attempt to answer that with a number instead of a feeling.

---

## 🧠 What I'm working on

- **PropLaw** — Knowledge-Graph-augmented RAG API for **German building law** (Baurecht). Musterbauordnung as the framework layer, Brandenburg's building code (BbgBO) implemented as the production-ready reference, architecture modular for the remaining Länder.
- **AI Agents** — multi-step reasoning and orchestration with LangGraph & smolagents
- **RAG Systems** — retrieval pipelines over real, regulated document corpora
- **Evaluation** — scoring rubrics that turn "feels better" into something you can defend

---

## 🚀 Start here

### 🏛 [PropLaw](https://github.com/SebastiansJourney/PropLaw) — Knowledge-Graph-augmented RAG API
`Python · Knowledge Graph · RAG · GCP`

Retrieval over German building regulations. A knowledge-graph layer sits on top of semantic retrieval so every answer stays traceable to the clause that governs it, in the correct jurisdiction.

**The part worth reading is the scoring model.** Retrieval quality was the bottleneck, not model choice. We defined a six-point rubric, ran it against a fixed question set, and used the results to decide what to change next. Precision moved from **2.55 → 3.60 out of 6** across several iterations.

Built with a four-person team. I was the Product Manager, from problem discovery to production-ready prototype.

### 🤖 [PM Assistant](https://github.com/SebastiansJourney/aipm-pm-assistant) — autonomous multi-node planning agent
`LangGraph · Groq · Streamlit`

Takes a project description and a team roster, returns a conflict-free plan: scoping, dependency mapping, scheduling with circular-dependency detection, skill-based allocation, risk audit and an interactive Gantt chart.

Extended over two iterations — optimizer feedback loop, reworked prompts across all six nodes, Pydantic-validated structured outputs, deployed front end. A third branch runs the same pipeline locally on Ollama with no external API.

### 📚 [RAG Pipeline](https://github.com/SebastiansJourney/ds-rag-pipeline) — retrieval over a real document corpus
`FAISS · LangChain · Groq`

Ingestion, chunking, sentence-transformer embeddings, a persisted vector store, similarity search and conversational memory. Runs as a working chat interface over regulated pharmaceutical documentation.

---

## 📦 More projects

| Project | What it does | Stack |
|---|---|---|
| [🌦️ Weather Advisor Agent](https://github.com/SebastiansJourney/weather-advisor-agent) | Tool-using agent giving context-aware recommendations, not just forecasts | smolagents · Claude API · Streamlit |
| [🏎️ ML Project — Mercedes-Benz](https://github.com/SebastiansJourney/AIPM_ML-Project_Mercedes-Benz) | End-to-end ML project with PM framing and business context | scikit-learn · Jupyter |
| [🏠 EDA — Real Estate Analysis](https://github.com/SebastiansJourney/ds-eda-project-template) | Collaborative data analysis: finding the right house for a client | Pandas · Matplotlib · Jupyter |
| [🔌 ds-mcp](https://github.com/SebastiansJourney/ds-mcp) | MCP servers connecting agents to tools and live data sources | MCP · Python |

---

## 🛠️ Stack

**AI & ML**
`Python` `LangGraph` `smolagents` `Claude API` `Groq` `Ollama` `FAISS` `scikit-learn`

**Data**
`Pandas` `NumPy` `SQL` `Matplotlib` `Seaborn`

**Deployment & Tooling**
`Streamlit` `FastAPI` `Docker` `GitHub Actions` `MCP` `VS Code`

**PM Methods**
`OKRs & KPIs` `Scrum / Kanban / Lean` `Roadmapping` `Stakeholder Management` `A/B Testing`

---

## 📍 Background

Eight and a half years at A.P. Moller – Maersk and Safmarine. First owning global key accounts — full commercial ownership, tender negotiations, escalations up to customer C-level. Then five years as a Finance Analyst in business partnering, building Power BI dashboards and decision papers for functional and operational leadership across product lines above €45M combined revenue.

That background means I bring commercial judgement and stakeholder communication to AI product work, not just the technical side.

**B.A. Social Economics**, Universität Hamburg · **Speditionskaufmann (IHK)**, EIMSKIP Hamburg

---

## 📫 Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin)](https://www.linkedin.com/in/sebastian-plum-aipm)

*Open to AI product and solutions roles.*
