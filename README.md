# Hi, I'm Ashwini 👋

Software Engineer with 3+ years building high-performance backend systems at IBM Cloud — distributed caching, gRPC services, storage engine design, and cloud-native architectures.

I think about backend systems the way a database engineer thinks about storage: correctness under failure first, clean boundaries second, performance third.

---

## What I'm Building

### [memcore](https://github.com/ashnote23/memcore) — Crash-Safe Spaced Repetition Engine

A production-grade backend storage engine built from first principles in C++, with a Go HTTP API layer connected via gRPC — fully containerised with Docker and running on Kubernetes.

This is not a flashcard app. It is a backend storage engine that happens to schedule flashcards — built with the same reasoning you'd apply to a production system.

```
curl → Kubernetes Pod → Go HTTP → gRPC → C++ engine → WAL + snapshot storage
```

**What it demonstrates:**
- Write-ahead logging with CRC32 crash recovery
- Snapshot + append-only log persistence
- Strict architectural boundaries enforced at the language level
- Schema-first API design with gRPC and protobuf
- Multi-container Kubernetes Pod deployment
- SM-2 scheduling algorithm with mathematical stability proof

---

## Currently

- 🎯 Pursuing **CKAD** (Certified Kubernetes Application Developer) — target April 2026
- 🔧 Deploying memcore on Kubernetes — Namespaces, ConfigMaps, PVCs, Ingress
- 📚 Path: CKAD → CKA → Kubernetes Operator in Go

---

## Tech Stack

**Languages**

![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)

**Systems & Backend**

![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat&logo=google&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Protobuf](https://img.shields.io/badge/Protobuf-4285F4?style=flat&logo=google&logoColor=white)

**Infrastructure**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![IBM Cloud](https://img.shields.io/badge/IBM_Cloud-1261FE?style=flat&logo=ibmcloud&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Databases**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

---

## What I'm Looking For

I'm looking for roles where systems thinking and distributed infrastructure depth matter — not just feature delivery.

**Target roles:**

🔧 **Backend Engineer** — distributed systems, API design, high-performance services in Go or C++

☁️ **Cloud Infrastructure Engineer** — cloud-native backend, IBM Cloud / AWS / GCP, infrastructure at scale

🚀 **Platform Engineer** — internal developer platforms, Kubernetes-based infrastructure, CI/CD pipelines

🤖 **Kubernetes Operator Developer** — extending Kubernetes with custom controllers in Go, CRDs, Operator SDK

**What I bring that's uncommon:**
- Backend systems depth (WAL, crash recovery, storage engine design) + Kubernetes deployment experience
- Go + C++ + gRPC in production — not just tutorials
- 3+ years on distributed systems at IBM Cloud (Redis, Zookeeper, caching, failover)
- Everything built from first principles with documented reasoning

📍 Bangalore, India — open to hybrid and remote
📬 ashwiniyadav2312@gmail.com
🔗 [linkedin.com/in/ashwini-r-496930227](https://linkedin.com/in/ashwini-r-496930227)

---

*Building in public — 16 days of engineering logs at [memcore/docs/daily_logs](https://github.com/ashnote23/memcore/tree/main/docs/daily_logs)*
