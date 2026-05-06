# Hi, I'm Sanju Yelisala 👋

**Software Engineer** | Distributed Systems · Event-Driven Architecture · Backend Engineering

📍 Tallahassee, FL &nbsp;|&nbsp; 📧 ysanju10@gmail.com &nbsp;|&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/sanju-yelisala-2b7b24138)

---

## About Me

I'm a Software Engineer with **6 years of experience** building high-throughput, fault-tolerant distributed systems at scale. I specialize in event-driven architectures, async I/O, concurrency models, and production reliability engineering.

I've delivered mission-critical platforms for enterprise clients (AstraZeneca, Ahold) and government agencies — from systems sustaining **10,000+ concurrent TCP connections at sub-10ms p99 latency** to AI-assisted pipelines that cut manual effort by **40%**. I care deeply about systems that are observable, resilient, and built to last.

---

## 🛠️ Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Backend & Architecture**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-FF6F00?style=flat)
![REST APIs](https://img.shields.io/badge/REST_APIs-02569B?style=flat)

**Messaging & Streaming**
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![AWS SQS](https://img.shields.io/badge/SQS-FF9900?style=flat&logo=amazonaws&logoColor=white)
![SNS](https://img.shields.io/badge/SNS-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)

**Cloud & Infrastructure**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)

**Data & Storage**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat&logo=amazonaws&logoColor=white)

---

## 🚀 Featured Projects

### 🔵 [Raft Consensus Engine & Distributed KV Store](https://github.com/ysanju10)
> **Python · FastAPI · React · Docker · Kubernetes**

Built a fault-tolerant distributed key-value store from scratch implementing the full **Raft consensus algorithm** across a 3-node cluster.

- Full leader election, log replication, log compaction, and `InstallSnapshot` RPC for lagging nodes
- Non-blocking TCP server using Python `selectors` with connection pooling and custom message framing
- Crash recovery via write-ahead log, voted-for state, and periodic KV snapshots to disk
- REST API with API key auth + React dashboard for live cluster state visualization
- Deployed on Kubernetes with StatefulSets for stable DNS-based node identity

---

### 🟠 Internal Load Testing & Observability Framework
> **Python · epoll · TCP · Distributed Systems**

Built a high-concurrency TCP server sustaining **10,000+ concurrent connections at sub-10ms p99 latency**.

- Epoll-based event loop using Python `selectors`
- Connection lifecycle management with backpressure detection and graceful degradation
- Resolved event loop bottlenecks causing 15% throughput degradation via `/proc` and `ss` instrumentation
- Cut load test setup time by **70%**, replacing all ad-hoc manual testing

---

### 🟢 Serverless E-Commerce Platform
> **AWS Lambda · API Gateway · DynamoDB · SQS/SNS · CloudFormation**

Fully serverless order processing platform with event-driven workflows, Cognito-based RBAC, and full infrastructure-as-code.

---

### 🟣 Sentiment-Driven Menu Recommendation System
> **Flask · TensorFlow · scikit-learn · NLP**

End-to-end NLP pipeline with tokenization, vectorization, and sentiment classification — improved F1-score by **15%**.

---

## 💼 Experience Highlights

| Role | Company | Period |
|---|---|---|
| Software Engineer | State of Florida – Dept. of Revenue | Jul 2024 – Present |
| Graduate Assistant | Middle Tennessee State University | Jun 2022 – Dec 2023 |
| Software Development Engineer | Cognizant Technology Solutions | Dec 2017 – Dec 2021 |

**Key wins:**
- 🤖 Built an AI-assisted ticket triage platform (spaCy + NLTK + RabbitMQ) cutting manual effort by **40%**
- ☁️ Deployed serverless AWS infrastructure saving **$1,000/year** in third-party tooling
- ⚡ Delivered 40+ REST/SOAP APIs for AstraZeneca & Ahold as reusable MuleSoft microservices
- 🔒 Enforced enterprise security via OAuth 2.0, LDAP, and client ID validation with Splunk observability

---

## 🎓 Education

- **M.S. Computer Science** — Middle Tennessee State University *(Dec 2023)*
- **B.Tech Electronics & Communication** — Lovely Professional University, India *(Jun 2017)*

---

## 📊 Core Strengths

```
✔ Distributed Systems & Consensus Algorithms
✔ High-Concurrency Networking (TCP, Async IO, epoll)
✔ Event-Driven Architecture (RabbitMQ, SQS, Kafka)
✔ System Design, Fault Tolerance & Observability
✔ Cloud-Native Development (AWS, Docker, Kubernetes)
✔ NLP / ML Integration in Production Systems
```

---

*Feel free to explore my repos or reach out — always happy to connect with fellow engineers building things that matter.*
