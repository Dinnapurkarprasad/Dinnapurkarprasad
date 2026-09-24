# Prasad Dinnapurkar

Full-Stack Developer

 · [LinkedIn](https://linkedin.com/in/prasad-dinnapurkar) · [GitHub](https://github.com/Dinnapurkarprasad) · [Portfolio](https://prasad-portfolio-psi.vercel.app) · [Email](mailto:prasaddinnapurkar@gmail.com)

---

## Stack

|  | Technologies |
|---|---|
| **Languages** | `TypeScript` · `JavaScript` · `Python` · `SQL` |
| **Frontend** | `React` · `Next.js` · `Tailwind CSS` · `shadcn/ui` · `React Query` · `GSAP` |
| **Backend** | `Django` · `Django REST Framework` · `FastAPI` · `Node.js` · `Express` · `Celery` · `WebRTC` |
| **AI** | `LangChain` · `LangGraph` · `RAG` · `LLM APIs` · `Claude` · `Gemini` · `Groq` |
| **Data & Infra** | `PostgreSQL` · `MongoDB` · `Redis` · `RabbitMQ` · `Docker` · `AWS` · `Vercel` |

---

## Working On

- **AI agents** — Tool use, middleware, context engineering, and multi-agent orchestration with LangChain and LangGraph.
- **Retrieval** — Hybrid search, reranking, and grounded generation with citations.
- **Evals & observability** — Tracing, datasets, and regression testing for LLM pipelines.
- **Production web** — Next.js rendering strategies, Django REST data flows, and async job pipelines on Celery and Redis.

---

## Projects

### [Verity](https://multi-agent-system-mb5h.vercel.app/)

Multi-agent research system that turns a single topic query into an 8-section cited report.

LangChain agents — Tavily search and a BeautifulSoup reader — orchestrated through an LCEL chain with a critic step that strips unsupported claims. Generates section by section across 18 LLM calls to stay under an 8,000 token-per-request ceiling. Next.js frontend with client-side polling against background jobs, incremental section rendering and progress states. FastAPI backend secured with JWT httpOnly cookies and Google OAuth 2.0.

### [context-engineering-agents](https://github.com/Dinnapurkarprasad/messy-vs-tidy-agent)

Side-by-side comparison of a naive agent and a context-engineered one on the same task.

Both agents share the same model and tools; the difference is entirely in how context is assembled, trimmed and passed between steps. Uses LangChain tools and middleware, with no retrieval layer, to isolate context engineering as the only variable.

### [Microservices Social Media Backend](https://github.com/Dinnapurkarprasad/Nodejs-Microservices)

Four independent backend services — Auth, Posts, Media and Search — built in Node.js and Express.

Each service exposes REST APIs with clear boundaries and route-level middleware, containerized with Docker Compose and decoupled via RabbitMQ for async inter-service communication and independent scaling. Redis-backed caching and session management, with JWT authentication and rate limiting enforced as middleware across service boundaries.

### [KrushiMitra](https://github.com/Dinnapurkarprasad)

AI agricultural support platform. Runner-Up, New GenAI Hackathon 2024.
