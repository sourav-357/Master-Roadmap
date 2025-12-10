
<br>

# TOPLINE (1-sentence)

Do **Priority A** perfectly. Build **2 flagship projects** (front + back + deployed). Solve **DSA daily** (timed mocks weekly). Apply for internships / job openings aggressively once you have one deployed full-stack project + 150–200 DSA problems. Do Priority B after Priority A is stable.

<br>

---

<br>

# PRIORITY A — MUST (do in this order)

I number them 1 → 12: finish #1 before moving to #2 etc. You may overlap DSA with everything below (DSA is daily, not sequential).

### 1) HTML ✅ / CSS (Responsive) ✅ — **2 weeks**

* **What / Why:** Basic building blocks of every web UI. Recruiters notice polish. You must make a pixel-correct portfolio and components.
* **Deliverable:** Live portfolio + 2 small UI pages (one responsive blog/project page, one contact form).
* **Resources:** MDN HTML & CSS docs; freeCodeCamp "Responsive Web Design".

<hr>

### 2) JavaScript (ES6+ fundamentals) ✅ — **3 weeks**

* **What / Why:** Language used everywhere (frontend + Node). Must understand closures, async/await, event loop, modules.
* **Deliverable:** 5 micro-tasks: debounce, promise→async refactor, DOM widget, fetch + caching demo, module bundling demo.
* **Resources:** MDN JS, YouTube JS deep-dive playlists, complete JS sections of your Udemy JS courses.

<hr>

### 3) Git & GitHub (PR workflow + basic CI) — **1 week**

* **What / Why:** Collaboration, version history, PRs are interview basics.
* **Deliverable:** Repo with branch→PR→merge + GitHub Actions: run tests on push.
* **Resources:** GitHub Learning Lab; Git documentation.

<hr>

### 4) Node.js + Express (backend fundamentals in JS) — **5–6 weeks**

* **What / Why:** Backend for your full-stack projects. Learn request lifecycle, middleware, async handling, REST.
* **Deliverable:** Production-like REST API (auth, users, products) with validation and tests.
* **Resources:** ZTM Node course, Jonas Schmedtmann Node course.

<hr>

### 5) React (hooks + functional components) — **6 weeks**

* **What / Why:** Industry-standard for frontend roles. Most product roles expect React.
* **Deliverable:** React SPA (project #1 front-end) that consumes your API.
* **Resources:** React docs + your Udemy React courses (Maximilian / ZTM).

<hr>

### 6) Relational DB (Postgres) + ORM (Prisma) — **3–4 weeks**

* **What / Why:** ACID transactions, joins, analytics — needed for serious backend roles.
* **Deliverable:** Order/payments microservice (migrations + sample transactions).
* **Resources:** Postgres docs; Prisma docs.

<hr>

### 7) Docker + Deploy (AWS/Vercel) — **3–4 weeks**

* **What / Why:** Containerize and deploy. You must be able to deploy a real app on AWS or Vercel. Interviewers ask deployment questions.
* **Deliverable:** Multi-stage Dockerfile + docker-compose for local dev + one app deployed (API on EC2 or container registry → ECS/ECR OR simple EC2 + Nginx).
* **Resources:** Docker docs; AWS Free Tier tutorials.

<hr>

### 8) Next.js (production React) — **3 weeks**

* **What / Why:** Server side rendering, routing, production features. Strong preference for Next in product companies.
* **Deliverable:** Portfolio or project deployed on Vercel with at least one SSR/SSG page.
* **Resources:** Next.js docs + course you own.

<hr>

### 9) TypeScript (strict) — **4–6 weeks** — *after Node in JS*

* **What / Why:** Many hires require TS. Convert an existing project to strict TS — THIS proves scale readiness.
* **Deliverable:** Convert the backend API to strict TypeScript (no `any`), type-safe controllers/services.
* **Resources:** TypeScript handbook; hands-on TS projects.

<hr>

### 10) Testing (unit + integration + basic e2e) — **3–4 weeks**

* **What / Why:** Tests = production-ready mindset; interviews ask about testability.
* **Deliverable:** Jest unit tests, Supertest integration tests for APIs, CI runs tests and fails on <80% coverage.
* **Resources:** Jest docs; Supertest docs; Playwright/Cypress for e2e (optional minimal).

<hr>

### 11) WebSockets / Real-time / Socket.io (namespaces, rooms, real-time multiplayer) — **2 weeks**

* **What / Why:** Many apps need live updates / chat / notifications — knowing sockets is a strong differentiator.
* **Deliverable:** Design docs for URL shortener, chat, and e-commerce (HLD + LLD). Hardened API: rate-limits, helmet, input validation.
* **Resources:** Traversy Media Socket.io Crash Course (1 hr) + Node.js + Socket.io + React Chat App by freeCodeCamp (3 hrs)

<hr>

### 12) NoSQL (MongoDB + Mongoose) — **2–3 weeks**

* **What / Why:** Fast prototyping, common with Node. You must know both SQL and NoSQL use-cases.
* **Deliverable:** Product catalog API using Mongo + aggregation queries.
* **Resources:** MongoDB docs; Maximilian MongoDB course.

<hr>

### 13) Core CSE Subjects - **(4th Sem)**

<hr>

<hr>

### 14) Computer Networks (CN) — **2 weeks**

* **What:** OSI Model, TCP/IP, DNS, HTTP/HTTPS, REST, caching, load balancers.
* **Why:** Foundation for backend scalability & interviews. You can’t talk about servers or APIs without knowing how data moves across the internet.
* **Deliverable:** Notes + 1-page summary on “How a request travels from browser to server.”
* **Resources:**

  * Gate Smashers (YouTube playlist on CN — concise + clear)
  * “Computer Networking: A Top-Down Approach” (Ch.1–5)
  * ByteByteGo blog/videos for visuals (YouTube).

<hr>

### 15) Operating System (OS) — **2 weeks**

* **What:** Processes, Threads, CPU Scheduling, Deadlocks, Memory management, Paging, Virtual Memory, Semaphores.
* **Why:** Interviewers use OS to check system-level thinking — critical for LLD & backend interviews.
* **Deliverable:** Mindmap or Notion page summarizing how OS handles multiple processes + example of producer–consumer problem using semaphores.
* **Resources:**

  * Gate Smashers (OS playlist)
  * Notes from *Arora Sir / Kunal Kushwaha OS Notes*
  * Book (if needed): Galvin — *Operating System Concepts.*

<hr>

### 16) Database Management System (DBMS) — **2 weeks**

* **What:** Normalization, Joins, Indexing, Transactions, Isolation levels, ACID, Query Optimization.
* **Why:** Core for backend + system design + interviews. Explains why Prisma/Mongoose behave the way they do.
* **Deliverable:** Create a sample normalized schema + write SQL queries for joins, nested queries, and transaction examples.
* **Resources:**

  * Gate Smashers (DBMS playlist)
  * *DBMS by Navkar Sir (Apna College YouTube)*
  * Book: Korth — *Database System Concepts.*

<hr>

### 17) Object-Oriented Design (OOD) / Low-Level Design (LLD) — **3 weeks**

* **What:** Classes, objects, design patterns (Singleton, Factory, Strategy, Observer, etc.), SOLID principles.
* **Why:** FAANG & product companies test LLD to check code architecture and class design ability.
* **Deliverable:** Build 2 mini LLD projects — e.g., *Parking Lot System* and *Tic-Tac-Toe with OOP patterns.*
* **Resources:**

  * *SDE Skills by Arpit Bhayani* (YouTube)
  * *System Design Primer GitHub (LLD section)*
  * *Refactoring.Guru* (Design Patterns visual guide)
  * *Gaurav Sen’s LLD playlist.*

<hr>

### 18) System Design Basics (HLD - Part 1) — **3 weeks**

* **What:** Scalability fundamentals — client-server architecture, load balancers, caching (Redis), CDN, databases (SQL vs NoSQL), replication, sharding.
* **Why:** Foundation of every FAANG-level interview — proves you can build scalable systems.
* **Deliverable:** Create architecture diagrams (Excalidraw or Whimsical) for:

  * URL Shortener
  * Instagram feed system
* **Resources:**

  * **System Design Primer (GitHub)** → Main base resource.
  * *Gaurav Sen* YouTube playlist (concept-level clarity)
  * *ByteByteGo* visual series on YouTube.

<hr>

### 19) Advanced System Design (HLD - Part 2) — **4 weeks**

* **What:** Queues (Kafka, RabbitMQ), Rate Limiting, Consistent Hashing, CAP theorem, Event-driven design, Microservices architecture, API Gateway, CQRS.
* **Why:** This is what FAANG expects for 20+ LPA interviews.
* **Deliverable:** Design diagrams + pseudo-architectures for:

  * WhatsApp or Slack chat architecture
  * Netflix / YouTube streaming architecture
* **Resources:**

  * **System Design Primer (GitHub)** (continue)
  * *Gaurav Sen deep dives* (Message queues, Consistent hashing)
  * *Alex Xu – System Design Interview Vol 1 & 2 (Books)* → 100 % recommended.

<hr>

### 20) Mock + Case Study Projects (System Design Capstone) — **2 weeks**

* **What:** Combine all concepts — CN + OS + DB + LLD + HLD — into 1 realistic capstone.
* **Why:** Proof that you can apply design thinking like a senior engineer.
* **Deliverable:** Choose one:

  * *Design Scalable E-Commerce System*
  * *Design YouTube / Instagram backend*
  * *Write a full Notion doc or 10-slide PPT explaining trade-offs, scalability, DB choices.*
* **Resources:**

  * *Excalidraw / Whimsical* for diagramming
  * *System Design Primer (reference architecture section)*

<hr>

### 21) Revision + Mock Interviews (Final Phase) — **2 weeks**

* **What:** Revise CS core (CN, OS, DBMS), LLD patterns, and HLD architectures.
* **Why:** System Design + CS Core questions form 30–40% of FAANG interviews after DSA.
* **Deliverable:** 3 mock interviews (record or simulate) — one each for LLD, HLD, and mixed CS core.
* **Resources:**

<br>

---

<br>

# PRIORITY B — EDGE (do after A)

Numbered sequence after Priority A:

1. **Redis + Background Jobs (BullMQ)** — caching & async processing.

   * Why: Improves latency, scalable emails/jobs.
   * Deliverable: Cache product list; background job to send emails.

2. **CI/CD (GitHub Actions)** — full pipeline tests→build→deploy.

   * Why: Real engineering expects automated pipelines.
   * Deliverable: Pipeline to deploy to staging on PR merge.

3. **Advanced TypeScript patterns** — generics, utility types.

   * Why: Many product codebases require strong TS skill.

4. **Cloud deeper (S3, RDS, Lambda, API Gateway)** — serverless basics.

   * Why: Helps design cost-effective systems and interviews.

5. **Observability (Sentry/Prometheus/Grafana)** — monitoring and tracing.

   * Why: Production debugging, p95 latency analysis.

<br>

---

