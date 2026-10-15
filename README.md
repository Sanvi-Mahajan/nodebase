# Nodebase

**An Asynchronous Workflow Execution Engine for Multi-Step AI Pipelines**

Nodebase is a workflow orchestration platform built with Next.js, TypeScript, tRPC, Inngest, Prisma, and PostgreSQL. It supports DAG-based workflow execution, asynchronous processing, dynamic template resolution, and secure credential management.

---

## Features

- **DAG-Based Workflow Execution:** Organize interconnected workflow steps using directed acyclic graphs.
- **Asynchronous Processing:** Orchestrate background execution using Inngest.
- **LLM Pipeline Orchestration:** Coordinate multi-step AI workflows and external LLM integrations.
- **Dynamic Template Resolution:** Resolve variables and pass data between workflow steps.
- **Secure Credential Management:** Encrypt third-party API credentials using AES-256 encryption.
- **Type-Safe Backend:** Use tRPC, TypeScript, and Prisma for type-safe backend operations.
- **Execution History:** Persist workflow execution metadata in PostgreSQL.
- **Error Monitoring:** Integrate Sentry for error tracking and debugging.

---

## Tech Stack

- **Framework:** Next.js 15
- **Language:** TypeScript
- **API Layer:** tRPC
- **Workflow Orchestration:** Inngest
- **ORM:** Prisma
- **Database:** Neon PostgreSQL
- **Encryption:** AES-256
- **Monitoring:** Sentry

---

## Architecture

1. **Workflow Configuration:** Define workflows and their execution steps.
2. **API Layer:** Handle application operations through tRPC.
3. **Execution Engine:** Coordinate asynchronous processing using Inngest.
4. **Template Resolution:** Resolve variables and propagate intermediate results.
5. **Credential Management:** Securely store and access third-party API credentials.
6. **Persistence:** Store workflow data and execution history in PostgreSQL.
7. **Monitoring:** Track application errors using Sentry.

---

## Getting Started

### Prerequisites

- Node.js
- PostgreSQL database
- Inngest configuration
- Required environment variables

### Installation

```bash
git clone <YOUR_REPOSITORY_URL>
cd <YOUR_REPOSITORY_DIRECTORY>
npm install

**Author**
Sanvi Mahajan ヽ(✿ﾟ▽ﾟ)ノ
