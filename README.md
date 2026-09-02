### Hi, I'm Prabin 👋

Backend & Machine Learning Engineer — search, ranking, and NLP systems for high-traffic
marketplaces. I train the models, build the services that serve them, and own both in production.

- 🔭 9+ years in software engineering — the last 5 in search platforms, the last 2 also building
  and operating production ML on top of them
- 🧠 Recent work: BERT-based query understanding, XGBoost/PyTorch ranking models, Elasticsearch
  relevance, and a search orchestration layer serving three production consumers
- 🧪 Currently exploring [agentic search](https://github.com/judasprabin/project-writeups/blob/main/agentic-car-search.md) — LangGraph, MCP tool-calling, and what it actually takes
  to get an LLM system from demo to production-grade
- 💬 Ask me about target leakage, evaluation discipline, or why "offline accuracy" and "production
  accuracy" are two different numbers
- 📫 [LinkedIn](https://www.linkedin.com/in/prabin-karki-7573abb4/) · judasprabin@gmail.com
- ⚡ Available immediately

---

#### What I've shipped

Full write-ups — architecture, decisions, trade-offs — in [project-writeups](https://github.com/judasprabin/project-writeups):

- **[Query understanding](https://github.com/judasprabin/project-writeups/blob/main/bert-query-understanding.md)** — fine-tuned BERT for natural-language search, lifting query conversion
  63.1% → 80.7% in production, at ~19ms inference
- **[Ranking](https://github.com/judasprabin/project-writeups/blob/main/ranking-models.md)** — rebuilt a marketplace's listing-ranking system with XGBoost and PyTorch models,
  moving scoring from a nightly batch job to an intra-day service — including a self-audit that
  caught target leakage in a shipped model before it caused harm
- **[Search platform](https://github.com/judasprabin/project-writeups/blob/main/unisearch-orchestration.md)** — principal author of a unified search service now serving three
  production consumers, and core contributor to the underlying Elasticsearch engine
- **[Agentic search](https://github.com/judasprabin/project-writeups/blob/main/agentic-car-search.md)** — a conversational search agent, redesigned from a deterministic pipeline to an
  MCP tool-calling loop on the back of a structured 42-point brittleness audit

#### What I bring

**Machine Learning & NLP** — PyTorch, XGBoost, Hugging Face Transformers. BERT fine-tuning,
feature engineering, target-leakage auditing, offline-vs-production evaluation discipline.

**Search & Backend** — Elasticsearch, FastAPI, Laravel, Redis. Relevance ranking, query
understanding, sort-cascade design, concurrent request orchestration, resilience patterns
(circuit breakers, graceful degradation).

**Data & Cloud** — SQL/Redshift pipelines, GCP (Kubernetes, Cloud Run, Pub/Sub), Terraform,
Docker, keyless CI/CD.

**AI & Agentic Systems** — LangGraph, MCP (Model Context Protocol), hybrid retrieval (RAG),
tool-calling architectures.

**Languages** — Python, SQL, PHP, TypeScript/JavaScript.

<!--
![Prabin's GitHub stats](https://github-readme-stats.vercel.app/api?username=judasprabin&show_icons=true&theme=default)
Uncomment the line above for a live stats card once the repo is public — it's a hosted image
service (github-readme-stats.vercel.app), nothing to install.
-->
