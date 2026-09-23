## Hi, I'm Kaue Campos

Backend engineer and **open source developer**. I build backend systems in Node.js/TypeScript and Go, with a focus on distributed systems, observability and AI agents.

- Software developer since 2018, currently a Software Engineer at **Claro Brasil**
- Open source contributor to **[Prometheus](https://github.com/prometheus/prometheus)**
- Interested in clean architecture, performance, and building reliable systems around LLMs

### Open source

| Project | Contribution | Status |
|---|---|---|
| [prometheus/prometheus](https://github.com/prometheus/prometheus) | [promql: fix inconsistent labelset collision error for range vector functions](https://github.com/prometheus/prometheus/pull/18631): range vector functions like `rate()` and `max_over_time()` no longer fail with a spurious *"vector cannot contain metrics with the same labelset"* error when series with different metric names don't overlap in time. Fixes [#14695](https://github.com/prometheus/prometheus/issues/14695). | ✅ Merged, Sep 2026 |

### Featured projects

| Project | What it is |
|---|---|
| [banking-graphql](https://github.com/kasharkzy/banking-graphql) | GraphQL banking API on Bun, Hono, GraphQL Yoga and Prisma, built with ports & adapters: domain logic isolated from HTTP, GraphQL and the database, tested with Vitest and in-memory repositories. |
| [bombardier-http](https://github.com/kasharkzy/bombardier-http) | HTTP load-testing CLI in Go: JSON-defined requests, concurrency, rate limiting and staged load plans, with latency percentiles, throughput and status-code breakdown. |

### Currently working on

- Idempotent transfers, the outbox pattern and OpenTelemetry tracing in `banking-graphql`
- An AI agent that operates the banking API through an **MCP server**, with human approval for money-moving actions and evals in CI

### Stack

**Languages:** TypeScript · JavaScript · Go  
**Backend:** Node.js · Bun · NestJS · Hono · GraphQL · Prisma  
**Infra & tooling:** Docker · GitHub Actions · Prometheus

### Find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kauecampos/)
[![dev.to](https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white)](https://dev.to/sh4rkzy)
