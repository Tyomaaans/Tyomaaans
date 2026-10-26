<div align="center">
  <h1>Hi, I'm Tyomaaans 👋</h1>
  <p><strong>Backend development · Go · APIs · Business workflows</strong></p>
  <p>
    <img src="https://komarev.com/ghpvc/?username=tyomaaans&style=flat-square&color=00ADD8&label=PROFILE+VIEWS" alt="Profile Views" />
  </p>
  <p>
    <a href="https://tyomaaans.cloud"><img src="https://img.shields.io/badge/Portfolio-00ADD8?style=for-the-badge" alt="Portfolio" /></a>
    <a href="mailto:contact@tyomaaans.cloud"><img src="https://img.shields.io/badge/Email-334155?style=for-the-badge" alt="Email" /></a>
  </p>
</div>

---

## About

I build backend services with **Go, PostgreSQL, and Redis**, focusing on authentication, business workflows, and API integrations. I also use **React and TypeScript** to build interfaces that connect to those services.

My projects range from session management and URL shortening to purchasing, inventory, sandbox payment integrations, and WebSocket chat.

## Tech stack

<p align="center">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&amp;logo=go&amp;logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&amp;logo=postgresql&amp;logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&amp;logo=redis&amp;logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&amp;logo=react&amp;logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&amp;logo=typescript&amp;logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker" />
</p>

| Area | Technologies |
| --- | --- |
| Languages | Go, TypeScript, JavaScript, SQL |
| Backend | Gin, GORM, REST APIs, JWT, Gorilla WebSocket |
| Data & messaging | PostgreSQL, Redis, RabbitMQ |
| Frontend | React, React Router, Tailwind CSS |
| Deployment | Docker, Docker Compose, Nginx, GitHub Actions |
| Tools & documentation | Git, OpenAPI/Swagger |
| Testing | Go testing, integration tests, Vitest, Playwright |

## What I build

- **Authentication & access:** JWT, refresh-token rotation, device sessions, role permissions, and warehouse access controls.
- **Business workflows:** purchasing approvals, stock reservations, invoices, partial payments, and audit trails, with database transactions and idempotency.
- **Background & real-time services:** Redis caching and rate limiting, RabbitMQ workers, transactional outbox workflows, and WebSocket connections.

## Featured projects

### [Mini-ERP](https://github.com/Tyomaaans/Mini-ERP)

**Go · Gin · GORM · PostgreSQL · Redis · Docker**

A REST API for purchasing, inventory across multiple warehouses, sales, and finance. Includes approval flows, partial receipts and shipments, invoicing, partial payments, and department permissions. Business actions use idempotency keys and transactional audit records, with integration tests covering authorization, rollback, and concurrent operations.

| More projects | Highlights |
| --- | --- |
| [Auth Session](https://tyomaaans.cloud/projects/auth-session) | JWT authentication, refresh-token rotation, device sessions, and session revocation. |
| [URL Shortener](https://tyomaaans.cloud/projects/url-shortener) | Link management, Redis caching, expiration handling, and rate limiting. |
| [Payment Gateway](https://github.com/Tyomaaans/payment-gateway) | DOKU and Xendit sandbox integrations, idempotent checkout, stock reservations, and payment reconciliation. |
| [Realtime Chat](https://github.com/Tyomaaans/REALTIME-CHAT) | Anonymous one-to-one WebSocket chat with matchmaking and a React interface, running on a single server process. |
