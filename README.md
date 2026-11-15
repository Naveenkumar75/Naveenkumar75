# Hi, I'm Naveenkumar 👋

**Software Engineer at Cognizant · Backend & Full-Stack · Growing into AI Engineering**

B.Tech in Information Technology (M. Kumarasamy College of Engineering, 2025). I build backend services and full-stack applications in Java, Python, Go and Angular, and I'm specializing in applied AI: LLM applications, RAG, agents and MCP.

[Portfolio](https://naveenkumar75.github.io) · [LinkedIn](https://www.linkedin.com/in/naveenkumar-k-986559239)

---

## Tech stack

| Area | Tools |
|---|---|
| Languages | Java, Python, Go, JavaScript, TypeScript |
| Frontend | Angular 17+, HTML, CSS |
| Backend | Spring Boot, FastAPI, Django, REST APIs |
| Databases | PostgreSQL, MySQL, SQLite |
| Data processing | Pandas, NumPy, OpenPyXL, Apache POI |
| AI / GenAI | LLMs, RAG, Vector Databases, MCP, Prompt Engineering |
| Tools & cloud | Git, GitHub, Docker, Microsoft Graph API, SharePoint, Cloudflare R2 |
| Integrations | Razorpay |

## Featured project

### [OmniDesk](https://github.com/Naveenkumar75/omnidesk) · Go · PostgreSQL · pgvector · FastAPI · MCP
[![CI](https://github.com/Naveenkumar75/omnidesk/actions/workflows/ci.yml/badge.svg)](https://github.com/Naveenkumar75/omnidesk/actions/workflows/ci.yml)

Multi-tenant customer-support backend.

- **Tenant isolation in two layers:** every query is scoped by the tenant in the JWT, and composite foreign keys make the database reject cross-tenant references.
- **Tickets:** state machine with row locks and an audit trail, assignment, replies and internal notes, admin/agent roles.
- **SLA worker** built on `FOR UPDATE SKIP LOCKED`, safe across replicas; each breach is recorded exactly once.
- **AI layer:** RAG reply suggestions over pgvector, a retrieval evaluation that gates CI, and an MCP server that acts with the caller's own token.
- **Production basics:** rate-limited login, versioned migrations, structured logging, OpenAPI spec, integration tests against PostgreSQL in CI.

**Next:** semantic embeddings with hybrid (vector + full-text) search, measured against the current baseline.

## Focus areas

- Backend engineering with Java/Spring Boot, Python (FastAPI, Django) and Go
- Production-minded design: auth, transactions, tenant data isolation, concurrency, CI
- Shipping LLM features: retrieval, evaluation, tool use and MCP servers
- Data structures and algorithms in Java

---

📫 Open to Software Engineer and AI Engineer opportunities at product-based companies.
