### Hi, I'm Prabin 👋

Backend & Machine Learning Engineer — search, ranking, and NLP systems for high-traffic
marketplaces. I train the models, build the services that serve them, and own both in production.

- 🔭 9+ years in software engineering — the last 5 in search platforms, the last 2 also building
  and operating production ML on top of them
- 🧠 Recent work: BERT-based query understanding, XGBoost/PyTorch ranking models, Elasticsearch
  relevance, and a search orchestration layer serving three production consumers
- 🧪 Currently exploring [agentic search](https://github.com/judasprabin/project-writeups/blob/main/agentic-car-search.md) — LangGraph, MCP tool-calling, and what it actually takes
  to get an LLM system from demo to production-grade
- 🌱 Building a few things on my own time under [Karki Labs](https://github.com/judasprabin) —
  see pinned repos below
- 💬 Ask me about target leakage, evaluation discipline, or why "offline accuracy" and "production
  accuracy" are two different numbers
- 📫 [LinkedIn](https://www.linkedin.com/in/prabin-karki-7573abb4/) · judasprabin@gmail.com
- ⚡ Available immediately

---

#### What I've shipped

Full write-ups — architecture, decisions, trade-offs — in [project-writeups](https://github.com/judasprabin/project-writeups):

- **[Query understanding](https://github.com/judasprabin/project-writeups/blob/main/bert-query-understanding.md)** — fine-tuned BERT for natural-language search, lifting query conversion
  63.1% → 80.7% in production
- **[Ranking](https://github.com/judasprabin/project-writeups/blob/main/ranking-models.md)** — rebuilt a marketplace's listing-ranking system with XGBoost and PyTorch models,
  moving scoring from a nightly batch job to an intra-day service — including a self-audit that
  caught target leakage in a shipped model
- **[Search platform](https://github.com/judasprabin/project-writeups/blob/main/unisearch-orchestration.md)** — principal author of a unified search service now serving three
  production consumers, and core contributor to the underlying Elasticsearch engine

#### Selected projects

| Project | What it is |
|---|---|
| EV research RAG agent | Hybrid-retrieval (BM25 + FAISS) research assistant with multimodal PDF ingestion and evaluation-first design — local prototype, not yet public |
| [Saathi](https://github.com/judasprabin/saathi) | AI settlement assistant for the South Asian diaspora in Australia — frontend + core flows, paired with Manaslu's scan/fill API on the backend (private repo) |
| [Nepal Earth](https://github.com/judasprabin/nepal-earth) | Geospatial intelligence platform — strategy & feasibility analysis |
| [HouseSmart Scan Service](https://github.com/judasprabin/scan-service) | Receipt and bill OCR scanning with AI extraction |

#### Tech I work in

`Python` · `PyTorch` · `XGBoost` · `Hugging Face Transformers` · `SQL` · `PHP / Laravel` ·
`TypeScript` · `Elasticsearch` · `FastAPI` · `Redis` · `GCP (Kubernetes, Cloud Run, Pub/Sub)` ·
`Terraform` · `LangGraph` · `MCP`

<!--
![Prabin's GitHub stats](https://github-readme-stats.vercel.app/api?username=judasprabin&show_icons=true&theme=default)
Uncomment the line above for a live stats card once the repo is public — it's a hosted image
service (github-readme-stats.vercel.app), nothing to install.
-->
