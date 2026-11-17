<h1 align="center">Hi, I'm Deepak 👋</h1>
<h3 align="center">Full-Stack Software Engineer · GenAI, RAG & Agentic Systems</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=deepakdevengineer&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
  <a href="https://www.linkedin.com/in/deepakdevengineer" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" /></a>
  <a href="https://iamdeepak.tech" target="_blank"><img src="https://img.shields.io/badge/Portfolio-iamdeepak.tech-1F2A44?style=flat" /></a>
</p>

I'm a full-stack engineer who usually ends up as the sole engineer on what I build, end to end: architecture, backend, frontend, and what happens after it ships. Lately that's meant production GenAI systems, multi-tenant RAG, agentic workflows, model gateways, and the unglamorous work of making sure AI output is actually correct before it reaches someone, on top of the Laravel/PHP and Python full-stack work I started with.

### What I've actually shipped

- **Multi-tenant RAG platform**, live inside a third-party school ERP: metadata-scoped retrieval so one tenant's data can never surface for another, a multi-provider LLM gateway with automatic failover, and a two-pass review where a second AI pass checks every finding in the first pass's own output before a human sees it.
- **Automated financial-data QA platform**, validating live ETF data across 4 regions, grown from a 38-script suite to 72 scheduled jobs and 629 check agents, with a Playwright browser-automation layer that independently caught a real, previously-undetected bug across multiple live products.
- **Production search & marketplace platforms** (Laravel/Vue.js): migrated search from SQL `LIKE` queries to Elasticsearch, blue-green index rollover for zero-downtime reindexing, and Razorpay payment integration with idempotent webhooks.

### Featured repos

- 🤖 **[rag-knowledge-chatbot](https://github.com/deepakdevengineer/rag-knowledge-chatbot)** — Full-stack RAG chatbot (FastAPI + ChromaDB + Next.js/React): upload a document, chat with it, grounded only in retrieved context, with a relevance threshold so it never guesses.
- 🔒 **[ermis-v2](https://github.com/deepakdevengineer/ermis-v2)** — A validation assistant where no automated detection, even at 99% confidence, becomes final without a human explicitly confirming it, backed by an append-only audit trail enforced at the database level.

### Stack I actually use

**Languages:** Python · PHP · TypeScript/JavaScript · SQL · C++ (fundamentals)
**Backend:** FastAPI · Flask · Laravel · Node.js/Express · Celery · REST APIs
**AI / GenAI:** RAG pipelines (pgvector, ChromaDB) · LangChain · LangGraph · OpenRouter · prompt engineering & evaluation (RAGAS-style)
**Frontend:** React · Next.js · Angular · Vue.js · Tailwind CSS
**Data:** PostgreSQL · MySQL · Redis · Elasticsearch · MongoDB
**Cloud & DevOps:** AWS · Azure (DevOps/Pipelines, Functions, Logic Apps) · Docker · Nginx · Git/CI-CD

<p align="left">
  <a href="https://www.linkedin.com/in/deepakdevengineer" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="linkedin" height="30" width="40" /></a>
</p>

📫 **Reach me:** dk78834@gmail.com · [iamdeepak.tech](https://iamdeepak.tech)

<br/>

<p align="left"><img align="center" src="https://github-readme-stats.vercel.app/api?username=deepakdevengineer&show_icons=true&locale=en&theme=default" alt="deepakdevengineer stats" /></p>
<p align="left"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=deepakdevengineer&show_icons=true&locale=en&layout=compact" alt="top languages" /></p>
<p align="left"><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=deepakdevengineer" alt="streak stats" /></p>
