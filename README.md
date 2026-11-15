## Naveenkumar K

Software Engineer at Cognizant. I build backend services in Go, Java and Python, and applied AI features (retrieval, evaluation and tool use through MCP) on top of them.

I care about the parts that make software trustworthy: data isolation, transactions, concurrency, tests that run against a real database, and documentation that states its limits.

[Portfolio](https://naveenkumar75.github.io) · [LinkedIn](https://www.linkedin.com/in/naveenkumar-k-986559239)

---

### [OmniDesk](https://github.com/Naveenkumar75/omnidesk)
**Multi-tenant customer-support backend** · Go · PostgreSQL · pgvector · FastAPI · MCP

- Tenant isolation enforced in two layers: every query is scoped by the tenant in the JWT, and composite foreign keys make the database reject cross-tenant references.
- Ticket state machine with row locks and an audit trail; admin and agent roles; rate-limited login that doesn't leak which accounts exist.
- SLA worker built on `FOR UPDATE SKIP LOCKED`, safe to run on several replicas, with a concurrency test proving each breach is recorded exactly once.
- A RAG service that suggests replies from a tenant's knowledge base, a retrieval evaluation that gates CI, and an MCP server that acts with the caller's own permissions.
- Versioned migrations, structured logging, an OpenAPI spec kept in sync with the router by a test, and CI running the Go and Python suites against PostgreSQL.

---

**Work with:** Go · Java / Spring Boot · Python / FastAPI / Django · TypeScript / Angular · PostgreSQL · Docker · GitHub Actions · LLM APIs, RAG, pgvector, MCP

Open to Software Engineer and AI Engineer roles at product companies.
