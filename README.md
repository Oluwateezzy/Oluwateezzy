<div align="center">

# Hey, I'm Oluwatobiloba 👋🏿

**Backend Engineer · Systems Builder · Technical Writer**

I build high-performance backend systems, event-driven architectures, and cloud-native infrastructure.
I don't just use tools I build them from scratch to understand how they work.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/oluwatobiloba-oluwafunmilayo-9b9632349)
[![Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@oluwateezzy03)

</div>

---

## ⚡ What I Do

```typescript
const oluwatobiloba = {
    role: "Backend Engineer",
    languages: ["TypeScript", "Python", "JavaScript", "Go"],
    backend: ["NestJS", "Fastify", "FastAPI", "Express"],
    databases: ["PostgreSQL", "MongoDB", "DynamoDB", "Redis", "SQLite"],
    messaging: ["Apache Kafka", "Redis Pub/Sub", "WebSockets"],
    cloud: ["AWS S3", "AWS DynamoDB", "Docker", "CDN"],
    architecture: [
        "Event-Driven Systems",
        "Microservices",
        "Multi-Tenant SaaS",
        "Double-Entry Ledgers",
    ],
    currentlyLearning: ["Go", "Kubernetes", "Terraform"],
};
```

---

## Signature Projects

> These aren't tutorials — they're systems I engineered from the ground up.

### [Telemetry Vault](https://github.com/oluwateezzy/telemetryVault) — High-Throughput Ingestion Engine
A system that ingests **millions of telemetry events** with sub-millisecond latency.
- Double-buffer batching (1000 events/batch), cursor-based **O(1) pagination** across millions of records
- PostgreSQL **time-range partitioning**, Token Bucket rate limiter, LRU-cached API key auth
- `Fastify` · `TypeScript` · `PostgreSQL` · `Kysely` · `Zod` · `Docker`
- 📖 [**Read the Engineering Article →**](https://oluwateezzy03.medium.com/system-design-learning-journey-building-a-high-throughput-telemetry-engine-d4c0f82e3f25)

### [PyStore](https://github.com/oluwateezzy/object_storage_s3) — S3-Compatible Object Storage (Built From Scratch)
A production-grade object storage system **replicating core AWS S3** architecture.
- Streaming I/O (never loads files into memory), **HMAC-SHA256 presigned URLs**, multipart uploads
- Object versioning with delete markers, **event-driven lifecycle management** via Kafka
- `Python 3.12` · `FastAPI` · `SQLAlchemy` · `Apache Kafka` · `aiofiles`

### [Async Process Manager](https://github.com/oluwateezzy/async_process_manager) — Event-Driven Integration Platform
A centralized service that unifies **email, SMS, payments, and webhooks** through Kafka.
- 3-tier priority routing, Dead Letter Queue, pluggable provider modules (SendGrid, Twilio, Stripe)
- API key security (bcrypt + AES-256), **Prometheus + Grafana** observability, Python SDK
- `Python` · `FastAPI` · `Apache Kafka` · `PostgreSQL` · `Redis` · `Docker`

### [Node Kafka](https://github.com/oluwateezzy/node_kafka) — Message Broker Built From Zero Dependencies
Implemented **Apache Kafka's core internals** from scratch using raw TCP.
- Segment-based commit log with **byte-offset indexing**, sparse `.index` files
- Consumer groups, offset tracking, metadata discovery API
- `Node.js` · `TCP` · `Custom Protocol` · `Zero Dependencies`

### [Aegis-CLI](https://github.com/oluwateezzy/server_manager) — Linux Server & Docker Management Dashboard
A web-based control plane for Linux servers with **real-time observability** and AI insights.
- Systemd service orchestration, Docker lifecycle management, **self-healing containers**
- Real-time CPU/RAM/Disk/Network metrics, traffic analytics, automated email alerts
- `Node.js` · `Express` · `React` · `Docker` · `systeminformation`

### [SIGINT](https://github.com/oluwateezzy/online_presence_tracker_system) — Real-Time Presence Tracker
A "spy movie" inspired surveillance system with **instant online detection** via WebSockets.
- Heartbeat-based presence detection, watcher pattern, Redis TTL-based state management
- `NestJS` · `Socket.IO` · `Redis` · `Vite`

---

## Tech Stack

<div align="center">

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)

**Backend Frameworks**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)

**Databases & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## Latest Articles

<!-- BLOG-POST-LIST:START -->
- [Building Telemetry Vault: How I Handle Millions of Events Without Crushing My Database](https://oluwateezzy03.medium.com/system-design-learning-journey-building-a-high-throughput-telemetry-engine-d4c0f82e3f25)
- [Understanding Authentication Methods in API Security](https://medium.com/@oluwateezzy03/understanding-authentication-methods-in-api-security-09bd53814769)
- [Creating a Flexible Prisma Module in NestJS](https://medium.com/@oluwateezzy03/creating-a-flexible-prisma-module-in-nestjs-710e0321ec5d)
- [Understanding Asynchronous Operations in JavaScript](https://medium.com/@oluwateezzy03/understing-asynchronous-operations-in-javascript-acd7bcec12b9)
- [Singleton Pattern in TypeScript](https://medium.com/@oluwateezzy03/singleton-pattern-in-typescript-5a4f6a178988)
- [Updating a Screen in React Native Without Reloading](https://medium.com/@oluwateezzy03/updating-a-screen-in-react-native-without-reloading-45f9c7f25b8b)
<!-- BLOG-POST-LIST:END -->

---

## GitHub Stats

<div align="center">

<a href="https://github.com/oluwateezzy">
  <img height="180px" src="https://github-readme-stats.vercel.app/api?username=oluwateezzy&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
</a>
<a href="https://github.com/oluwateezzy">
  <img height="180px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=oluwateezzy&layout=compact&theme=tokyonight&hide_border=true" />
</a>

<br/>

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=oluwateezzy&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

### Let's Connect

I'm currently open to **Backend Engineer**, **Cloud Engineer**, and **Junior DevOps** roles.

If you're building something interesting and need someone who understands systems at every layer — from the TCP socket to the database partition — let's talk.

[![LinkedIn](https://img.shields.io/badge/Reach_out_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/oluwatobiloba-oluwafunmilayo-9b9632349)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:oluwateezzy03@gmail.com)

</div>
