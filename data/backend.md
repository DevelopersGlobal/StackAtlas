# Backend Stacks

## API Forge

**Use case:** REST API with auth, storage, and background jobs
**Tools:** FastAPI, PostgreSQL, Redis, Docker
**Difficulty:** Intermediate

**Why this combo works**
- Clear and durable backend foundation
- Good support for async work and structured APIs
- Portable setup for local and hosted environments

**Caveats**
- Background jobs need operational care
- Infra complexity is higher than serverless stacks

## Serverless Relay

**Use case:** Event-driven backend for lightweight apps
**Tools:** TypeScript, Cloudflare Workers, KV, Queues
**Difficulty:** Intermediate

**Why this combo works**
- Fast global deployment model
- Nice fit for webhook handlers and edge-friendly APIs
- Lower ops burden for smaller products

**Caveats**
- Vendor-specific patterns can reduce portability
- Long-running tasks may need a separate service
