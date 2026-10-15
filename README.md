# Hi, I'm Akhil Rajan 👋

**Senior AI Solutions Engineer · Generative AI & Agentic Systems · Sydney, Australia 🇦🇺**

I build production GenAI systems end to end: multi-agent RAG, vision-language models and LLM evaluation, shipped on Azure for real users. 8+ years across insurance, procurement, healthcare and travel. 

🟢 **Open to:** freelance and contract engagements, and full-time roles in Australia.
🪪 Full work rights in Australia, no sponsorship required.

---

## What I can help you with

| Problem | What I deliver |
|---|---|
| **Document and contract intelligence** | Extraction, classification and grounded Q&A over PDFs with page- and line-level citations |
| **RAG that holds up in production** | Chunking, hybrid retrieval, reranking, evaluation pipelines, guardrails |
| **Agentic workflows** | Planner/worker multi-agent systems, tool use, MCP, LLM-as-judge evaluation |
| **AI for regulated industries** | Risk assessment, threat modelling and security review so AI products pass enterprise sign-off |
| **Full-stack product development** | End-to-end web apps: FastAPI / Django / Flask backends, React / Next.js / TypeScript frontends, PostgreSQL, REST APIs, streaming UIs |
| **Idea → working product, fast** | Solution architecture, rapid prototypes and MVPs, Docker, Azure Container Apps, CI/CD with GitHub Actions |
| **Data science problems** | Framing messy business questions, analysis and modelling in pandas and scikit-learn, clear results stakeholders can act on |
| **Machine learning** | Classification, recommendation systems and predictive models, from experiment to deployed service |
| **NLP and text analytics** | Named entity recognition, text and intent classification, summarisation, question answering with Hugging Face transformers |
| **Computer vision and OCR** | Document digitisation, OCR, form and layout extraction, VLM-based screen and image understanding |
| **LLMOps and evaluation** | Prompt versioning, automated evals, A/B testing across prompts and models, tracing and cost tracking (Langfuse) |
| **Enterprise automation** | Power Apps, Power Automate and Power BI dashboards, plus AI-driven test generation and automation |

## Featured work

### 🎧 [SupportPilot AI](https://github.com/akhil4rajan/supportpilot-ai)
A multi-tenant, drop-in customer-support assistant: one `<script>` tag gives any website a chat widget that answers from the company's own docs with source citations, looks up **only the signed-in user's** orders, files Jira tickets and hands off to a live human agent. Order access is enforced in layers (customer-signed JWT identity, tool schemas that can't take a user id, tenant-scoped lookups, no existence oracle). Model-agnostic across Anthropic, OpenAI, Gemini, Llama and self-hosted models, with a release-gate eval suite (security, resilience, retrieval) that issues a READY / NOT READY verdict, plus a scaling and capacity model for ~30,000 conversations/day.
`FastAPI` · `Claude API + OpenAI-compatible providers` · `BM25 retrieval` · `React + TypeScript (Shadow DOM widget)` · `WebSockets` · `PostgreSQL` · `Redis` · `Jira` · `Prometheus` · `Docker` · `GitHub Actions`

### 📄 [Contract Intelligence RAG App](https://github.com/akhil4rajan/contract-intelligence-rag-app)
Upload PDF contracts, ask questions across one or several, and get answers grounded in the source. Each answer cites the contract, page and line numbers, and clicking a citation highlights the lines in the original PDF.
`FastAPI` · `LangChain` · `Claude API` · `BM25 + dense retrieval with RRF` · `OCR for scanned PDFs` · `React + TypeScript` · `pytest`

### 🧘 [AI4Human](https://github.com/akhil4rajan/ai4human-fitness)
A multi-agent wellness companion: nutrition, fitness, sleep and mental-wellbeing specialists coordinated by an orchestrator, with a **code-level safety layer** (crisis and medical messages bypass the model; calorie floors and output checks are enforced in code, not just prompts). Includes offline evals, Langfuse observability, CI with a browser smoke test, and bring-your-own-key privacy.
`Claude Agent SDK` · `FastAPI` · `Next.js` · `SSE streaming` · `SQLite` · `Langfuse` · `Playwright` · `GitHub Actions`

### Production highlights (professional work)
- **Contract-processing platform** at Allianz: 15,000+ contracts processed, used by 500–600 colleagues across 30+ departments, 94%+ extraction accuracy against a human-labelled test set.
- **Hierarchical multi-agent RAG**: a planner agent splits questions into sub-queries, domain agents run them in parallel, and a single cited answer comes back.
- **AI test generation**: computer vision plus vision-language models turn screen recordings into executable tests, run by a Playwright agent with LLM-as-judge scoring.
- **Healthcare automation** at Aveta.ai: LLM + RAG medical coding, 92%+ document-extraction accuracy, 85%+ reduction in manual billing intervention.

## What drives me

I love building **solid AI software products**, not demos: software that is tested, evaluated, secure and still working months after launch. I also love **hackathons**. Fast, high-pressure building is where I do some of my best work, and it's where I've won: MachineHack at MLDS 2025, the All India Defence Innovation Hackathon (IIT Madras) and the AWS Community Hackathon. If you're running one in Australia, or want a teammate, get in touch.

## Tech stack

**GenAI & agents:** Claude API · Azure OpenAI · LangGraph · LlamaIndex · MCP · Pydantic · Langfuse
**ML & NLP:** Hugging Face Transformers · scikit-learn · pandas · OCR · Document Intelligence
**Engineering:** Python · TypeScript · SQL · FastAPI · React · Docker · PostgreSQL · GitHub Actions
**Cloud & automation:** Microsoft Azure (Container Apps, Document Intelligence, Foundry) · Power Platform

## Recognition

🏆 Leading Star Award, Allianz (2026) · Best Innovation Award, Allianz (2025) · Winner, MachineHack at MLDS 2025 · First Prize, All India Defence Innovation Hackathon (IIT Madras)

🎓 M.Tech Data Science & Engineering (BITS Pilani) · IBM RAG & Agentic AI Specialisation · Anthropic Academy (Claude API, Claude Code)

## Let's talk

📫 [LinkedIn](https://www.linkedin.com/in/akhilpeterrajan/) is the best way to reach me. Say what you're building and your timeline.
