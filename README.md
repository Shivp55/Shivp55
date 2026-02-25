<!-- Premium Minimal Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:1f2937&height=200&section=header&text=Shaishav%20Parekh&fontSize=44&fontColor=ffffff&animation=fadeIn" />
</p>

<h3 align="center">Backend & Distributed Systems Engineer</h3>

<p align="center">
  Dublin, Ireland • Open to Backend / Distributed Systems Roles  
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/shaishav-parekh/">LinkedIn</a> •
  <a href="https://shivp55.github.io/shaishav-portfolio/">Portfolio</a> •
  <a href="mailto:shaishavparekh23@gmail.com">Email</a>
</p>

---

## Engineering Approach

I design backend systems that prioritize:

- Horizontal scalability  
- Idempotent API design  
- Fault isolation between services  
- Observability-first architecture  
- Concurrency-safe processing  
- Secure and production-ready SDLC  

My work centers around distributed microservices, event-driven systems, and operational reliability.

---

# 🏦 System Design Case Study  
## Distributed Banking Microservices Platform  

🔗 Repository:  
https://github.com/Shivp55/Microservices  

**Stack:** Java • Spring Boot • Kafka • Kubernetes • Prometheus • Grafana  

### Architecture

- Independent domain services (Accounts, Loans, Cards)
- Asynchronous inter-service communication using Kafka
- Server-side service discovery
- Centralized configuration management
- Dockerized services deployed on Kubernetes
- Horizontal pod scaling
- Prometheus metrics with Grafana dashboards
- CI/CD via Maven pipelines

---

### System Design Decisions

**1️⃣ Consistency vs Availability (CAP Consideration)**  
For transaction workflows, strong consistency was prioritized over availability.  
Services use transactional boundaries to maintain ACID compliance for financial data integrity.

**2️⃣ Idempotency Handling**  
Transaction APIs designed with idempotency keys to prevent duplicate processing during retries.

**3️⃣ Concurrency Control**  
- Optimistic locking using JPA version fields  
- Thread-safe Kafka consumers  
- Transaction isolation levels carefully selected  

**4️⃣ Fault Tolerance**  
- Retry logic for transient failures  
- Dead-letter topic pattern in Kafka  
- Service isolation to prevent cascading failure  

**5️⃣ Caching Strategy**  
- Redis-based caching for read-heavy endpoints  
- Cache invalidation aligned with domain updates  
- Reduced read latency by ~30–35% in optimized endpoints  

---

# 📊 Performance & Impact

- ~35% reduction in API response time via indexing & query tuning  
- Reduced manual deployment overhead via CI/CD automation  
- Improved production visibility through Prometheus + Grafana dashboards  
- Designed services to scale horizontally under load  

---

# 📈 Streaming System Design  
## Real-Time Clickstream Anomaly Detection  

🔗 Repository:  
https://github.com/Shivp55/flink-clickstream-anomaly-detection  

**Stack:** Kafka • Apache Flink • Docker  

### Design Focus

- Stateful stream processing  
- Windowed aggregations  
- Backpressure management  
- Partition-aware Kafka processing  
- Containerized multi-service orchestration  

Trade-off considered between latency and processing accuracy in anomaly thresholds.

---

# 🧾 Full Stack Systems

## Sticker Application  
🔗 https://github.com/Shivp55/React_Java_Learning  

- Spring Boot REST APIs  
- JWT authentication + RBAC  
- Modular React architecture  
- SQL query optimization  
- Layered backend design  

---

## Employee Management Dashboard  
🔗 https://github.com/Shivp55/Employee-Management-App  

- Controller–Service–Repository pattern  
- Clean React component separation  
- RESTful API contracts  
- Structured validation & error handling  
- ~35% latency reduction through query optimization  

---

# 🛡 Reliability & Production Engineering

- L3 production support experience  
- Root Cause Analysis (RCA)  
- CloudWatch, Prometheus & Grafana monitoring  
- Secure SDLC (OWASP awareness)  
- CI/CD automation  
- Blue/Green deployment familiarity  

---

# Core Stack

**Languages:** Java, Python, JavaScript  
**Backend:** Spring Boot, Microservices, REST APIs  
**Frontend:** React  
**Streaming:** Kafka  
**Containers:** Docker, Kubernetes  
**Cloud:** AWS (EC2, Lambda, API Gateway, CloudWatch)  
**Build:** Maven  
**Databases:** PostgreSQL, MySQL, MongoDB, Redis  
**Testing:** JUnit, Mockito  

---

# Experience Snapshot

### Freelance Full Stack Engineer (2023–Present)
- Architected distributed systems end-to-end  
- Improved API performance via database tuning  
- Built CI/CD automation  
- Implemented observability dashboards  

### Full Stack Software Engineer – GreySlate
- Built microservices + React UI  
- Kafka event processing  
- Production support & reliability improvements  

### Java Software Engineer – Tatvasoft
- Enterprise REST APIs  
- Integration testing  
- Migration toward microservices  

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f2937,100:111827&height=120&section=footer&text=Thank%20You%20For%20Visiting&fontSize=14&fontColor=ffffff&animation=fadeIn" />
</p>

---

# GitHub Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Shivp55&theme=github_dark" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Shivp55&theme=github-dark" />
</p>

