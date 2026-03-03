# Backend-Oriented Full-Stack Developer Roadmap
## 12 Months to Internship & 24 Months to 12–15 LPA Placement

---

## Overview: Two Phases

**Phase 1**: Foundation → Strong Internship  
**Phase 2**: Internship → 12–15 LPA Placement

This document covers BOTH phases in one place.

---

## Global Rules (Very Important)

- **Backend language for projects**: Node.js + Express (later add TypeScript)
- **Databases**: Learn **SQL (PostgreSQL/MySQL) first**, then **MongoDB**. Both required.
- **Frontend**: Only HTML/CSS + React (no need for more frontend frameworks before first job)
- **Advanced infra**: Only **basic** level for messaging/real-time; no deep Kafka/microservices needed before first internship

---

## Technologies: Yes/No/Optional (Complete View)

### **REQUIRED — Phase 1 (Internship)**

Already listed in Phase 1 section. Recap:
- C++/Java (basics), React, Node.js, Express, SQL, MongoDB, Docker, CI/CD, JWT, Redis, Jest/Supertest, basic system design concepts

### **REQUIRED — Phase 2 (Placement)**

Adding to Phase 1:
- **Java OOP + Spring Boot** (strong working knowledge)
- **Spring Data JPA + Hibernate** (solid depth)
- **Spring Security with JWT** (interview-level)
- **TypeScript basics** (apply to Node projects)
- **System Design** (intermediate; design 5–7 real systems)
- **Two flagship projects** (one Node, one Spring Boot)
- **Production features**: caching, queuing, monitoring in both ecosystems

### **NOT REQUIRED — Learn After Full-Time Job**

- Deep Kafka / message brokers
- Full microservices architecture
- Kubernetes
- Advanced DevOps (Terraform, Ansible)
- GraphQL (GraphQL expertise can wait)
- Machine learning / data science
- Advanced concurrent programming (reactive systems)
- Full ELK / Prometheus stack setup
- Advanced database optimization (query tuning at expert level)

---

## Key Metrics & Checkpoints (Complete View)

### Project Progression

- **Early Phase 1**: Barebones CRUD API
- **Mid Phase 1**: Full-stack app deployed
- **Late Phase 1**: Production-ready 2nd project
- **End Phase 1**: Flagship Node project (fully featured)
- **Early Phase 2**: Spring Boot backend API recreated
- **Mid Phase 2**: Flagship Spring Boot project (fully featured)
- **End Phase 2**: 2 polished flagships + 2–3 additional quality projects

### Application Timeline

- **Internship**: Start applying early Phase 1, secure by end of Phase 1
- **Full-time roles**: Start applying post-internship
- **Target**: 50+ applications/month in final phase
- **Response rate target**: 5–10% (5–10 interviews from 100 apps)
- **Offer target**: Secure 12–15 LPA role by end of Phase 2

---

## When to Apply for Full-Time Roles (Phase 2)

- **Start applying**: After internship ends or overlap
- **Heavy pushing**: Final phase
- **Ideal readiness**: Final checkpoints
- **Application sources**:
  - LinkedIn: targeted outreach to recruiters
  - Company career pages: direct applications
  - AngelList: startup opportunities
  - Referrals: through internship mentor/connections
  - Cold emails: curated list of 30–50 companies

---

## Target Companies (Tier 1 & High-Pay)

**Tier 1 Tech**: Google, Meta, Amazon, Microsoft, Apple, Uber  
**Tier 2 India**: Atlassian, Postman, Freshworks, Chargebee, Cred, Razorpay  
**High-Growth Startups**: Groww, Meesho, Zomato, Swiggy, Stripe (if hiring), Databricks, OpenAI (if hiring)  
**Remote-first**: Vercel, Supabase, Figma, WorkOS  

---

## Resources by Topic (Updated for Phase 2)

### New for Phase 2:
- **Java**: Effective Java, Java Concurrency in Practice (advanced parts)
- **Spring Boot**: Official Spring Boot guide, Baeldung (100+ articles), Spring in Action (book)
- **System Design**: Gaurav Sen (YouTube), Alex Xu's book, DesignGurus.io
- **Mock Interviews**: Pramp, Interviewing.io, friends from community

---

## Daily/Weekly Habits (Phase 2)

**During Internship**:
- **Daily**: 1–2 hours dev (learning from internship code)
- **Weekly**: 1 code review, 1 small project improvement

**Post-Internship**:
- **Daily**: 2–3 hours dev (flagship projects) + system design
- **Weekly**:
  - 1 system design practice (design a new system)
  - 1 project milestone (feature, optimization, or test coverage)
  - 1–2 mock interviews (full 90-min session)
- **Bi-weekly**: Polish one project's documentation/demo

---

## Honest Reality Check

### Phase 1:
- Ambitious but achievable at 50 hrs/week
- Success factors: consistency, project focus, aggressive applications

### Phase 2:
- Ranges from moderate to heavy depending on internship load
- During internship: lighter load (learn from real work)
- Post-internship: heavy load (2–3 hrs dev daily)
- Critical: **Don't waste internship**; apply learnings to side projects

### Key Success Factors (Both Phases):
1. **Consistency over perfection** — Show up daily, even if just 1 hour
2. **Real projects beat tutorials** — Build, deploy, get feedback
3. **Portfolio visibility** — GitHub, live demos, and talking about your work matter enormously
4. **Aggressive application strategy** — 50+ apps/month; expect 3–5% response
5. **Learn from feedback** — Each rejection/failure is data; adjust accordingly
6. **Internship is gold** — Real production code > tutorial projects. Absorb everything.
7. **Network and referrals** — After internship, leverage connections for referrals (massively higher conversion)

---

## Summary: Your Path to 12–15 LPA

**Phase 1**:
→ Build strong foundation (Node + React)  
→ Get a solid SDE internship (apply early)  

**Phase 2**:
→ Learn production best practices during internship
→ Build Java/Spring Boot backend expertise
→ Master system design at interview level
→ Build flagship projects showing depth
→ Apply aggressively to full-time roles
→ **Target 12–15 LPA placement by end of Phase 2**  

---

# PHASE 1: INTERNSHIP FOCUS

---

## Absolute Foundations (≈120h total)

### Dev (≈70–80h)

**1. DSA Language Basics (C++ or Java) – 30h**
- Required: YES, deep enough to be fully comfortable writing basic programs
- Topics: data types, loops, functions, arrays, strings, classes/objects, basic OOP
- Implement manually:
  - Dynamic array
  - Singly linked list
  - Stack and queue (array or linked list)
- Resources: GeeksforGeeks, LeetCode discussions

**2. Git + GitHub – 10–15h**
- Required: YES, basic level
- Commands: init, clone, add, commit, push, pull, branch, merge
- GitHub: create repos, push code, write simple README
- Resources: GitHub Guides, Atlassian Git tutorials

**3. Linux/Terminal Basics – 10–15h**
- Required: YES, basic level only
- Commands: ls, cd, mkdir, rm, cp, mv, cat, grep, ps, kill
- Goal: be comfortable working in terminal; able to run Node/DB servers later
- Resources: Linux Command Line Basics course

**4. HTML & CSS (Part 1) – 20–25h**
- Required: YES, moderate depth
- Semantic HTML: headings, div/span, forms, links, images
- CSS: selectors, box model, margins/padding, colors/typography
- Project: simple static landing page (no JS yet)
- Resources: freeCodeCamp, MDN Web Docs

---

## Web Basics + Stronger Foundations (≈120h)

### Dev (≈70–80h)

**5. HTML & CSS (Part 2) – 15–20h**
- Flexbox and Grid, responsive design (media queries)
- Project: responsive personal portfolio page
- Resources: freeCodeCamp Responsive Web Design course

**6. JavaScript Fundamentals – 40–45h**
- Required: YES, deep enough for frontend + Node
- Topics:
  - Variables, scopes, closures
  - Functions, higher-order functions
  - Arrays/objects, destructuring
  - ES6 basics (let/const, arrow functions, template literals)
  - DOM manipulation, events
  - Basic async (promises, async/await)
  - Fetch API
- Resources: javascript.info, freeCodeCamp JavaScript course

**7. Small JS Projects – 15–20h**
- Calculator, todo list (localStorage), form validation
- Goal: be comfortable writing JS without copying code
- Deploy on GitHub Pages

---

## React + HTTP + Foundations (≈120h)

### Dev (≈70–80h)

**8. HTTP & REST Basics – 10–15h**
- Required: YES
- HTTP methods (GET, POST, PUT, DELETE), status codes (200, 201, 400, 401, 404, 500)
- Headers, cookies vs tokens
- REST principles (resources, idempotency, stateless)
- Resources: MDN HTTP, RESTful API Design best practices

**9. React (Part 1) – 40–45h**
- Required: YES, moderate depth
- Topics:
  - JSX, functional components, props, state, events
  - useState/useEffect hooks, basic form handling
  - Component lifecycle, re-rendering
- Project: Todo app with React (no backend yet), localStorage persistence
- Resources: React.dev official tutorial, Scrimba React course

**10. React (Part 2) – 20–25h**
- React Router (multiple pages)
- Basic global state with Context API
- Project: simple "blog frontend" that fetches dummy API data (JSONPlaceholder)
- Resources: React Router docs, Context API tutorial

---

## Node/Express Foundations (≈120h)

### Dev (≈70–80h)

**11. Node.js Basics – 15–20h**
- Required: YES, deep eventually
- Node runtime, npm, modules (require/import)
- Basic scripts, event loop understanding
- Resources: Node.js official docs, freeCodeCamp Node.js course

**12. Express (Part 1) – 30–35h**
- Basic server, routes, middleware, request/response
- Error handling, status codes
- Build: simple REST API for "posts" with in-memory data
- Resources: Express.js official guide, Net Ninja Express tutorial

**13. Express (Part 2) – 20–25h**
- Folder structure (routes, controllers, middleware)
- Environment variables (dotenv)
- Better error handling with middleware
- Simple logging (console/morgan)
- Use Postman to test APIs, export collections
- Resources: Best practices guides on GitHub

---

## SQL + Real APIs (≈120h)

### Dev (≈70–80h)

**14. SQL (Part 1) – 30–35h**
- Required: YES, strong depth
- Install PostgreSQL/MySQL locally
- Topics: create tables, primary/foreign keys, basic joins (INNER, LEFT, RIGHT)
- SELECT, INSERT, UPDATE, DELETE queries
- ORDER BY, GROUP BY, HAVING, LIMIT
- Resources: SQLZoo interactive tutorial, freeCodeCamp SQL course

**15. SQL (Part 2) – 20–25h**
- Normalization (1NF, 2NF, 3NF basics)
- Indexing, why they matter for performance
- Transactions, ACID properties basics
- Query optimization, EXPLAIN plans
- Design DB schema for a small app (users/posts/comments)
- Resources: Database design tutorials, PostgreSQL documentation

**16. Backend Project #1 (Barebones) – 20–25h**
- Required: YES
- Node + Express + SQL (Postgres/MySQL)
- Features:
  - User registration/login (plain for now, no auth yet)
  - CRUD for posts with DB
  - Simple pagination
- Deliverables: GitHub repo, Postman collection

---

## MongoDB + Full Stack Project (≈120h)

### Dev (≈70–80h)

**17. MongoDB – 30–35h**
- Required: YES, moderate depth
- CRUD operations, collections, documents
- Aggregations (basic pipeline)
- Indexing concepts, when to use Mongo vs SQL
- Document design best practices
- Resources: MongoDB University free courses, official docs

**18. ORM/ODM – 15–20h**
- Required: YES, basic level
- Use Prisma (for SQL) or Sequelize; use Mongoose for Mongo
- Model relationships, queries through ORM
- Resources: Prisma docs, Sequelize docs, Mongoose docs

**19. Backend Project #2: Full Stack v1 – 20–30h**
- Choose one:
  - Blog (posts, comments, search)
  - Notes app (notebooks, notes, sharing)
  - Simple Task Manager (tasks, categories, filtering)
- Stack: React frontend + Node + Express + **either SQL or Mongo**
- Features:
  - Auth (basic JWT)
  - CRUD with filters, pagination
  - Responsive React UI
  - Deployed (Render/Railway + Netlify/Vercel)
- Deliverables: Live link, GitHub, README

---

## Auth + Security + Better APIs (≈120h)

### Dev (≈70–80h)

**20. Auth & Security (Deep) – 40–45h**
- Required: YES, solid depth for JWT and basic security
- JWT auth (access token + refresh token pattern)
- Password hashing with bcrypt (salt, rounds)
- Role-based access control (RBAC): admin, user, moderator
- Input validation: JOI or Zod
- Basic security practices:
  - Sanitize input (prevent SQL injection)
  - Prevent XSS (escape HTML entities)
  - CSRF at conceptual level
  - HTTPS/TLS importance
- Resources: OWASP top 10, Auth0 blog, JWT.io explanation

**21. Improve Existing Backend Projects – 30–35h**
- Add auth + validation to previous projects
- Implement proper folder structure:
  - /routes
  - /controllers
  - /services
  - /models
  - /middleware
  - /utils
  - /config
- Add comprehensive error handling
- Clean up code, add comments
- Update Postman collection and README

---

## Production Skills — Redis, Rate Limiting, Logging, Tests (≈120h)

### Dev (≈70–80h)

**22. Redis (Caching) – 20–25h**
- Required: YES, basic–good depth
- Setup Redis locally, basic commands (SET, GET, EXPIRE, DEL)
- Implement caching in Node:
  - Cache results of expensive queries
  - Set TTL (time-to-live)
  - Simple cache invalidation strategies
  - Use Redis for session storage
- Resources: Redis official docs, Redis tutorial on Node.js

**23. Rate Limiting – 10–15h**
- Required: YES, basic level
- Use express-rate-limit middleware or build with Redis
- Implement per-IP and per-user limits
- Apply to login endpoints and public APIs
- Resources: express-rate-limit docs, rate-limiting best practices

**24. Logging & Error Handling – 15–20h**
- Required: YES, basic level
- Use Winston or similar logger (not just console.log)
- Structured logging (JSON format)
- Log levels: error, warn, info, debug
- Correlation IDs for tracing requests
- Central error handler middleware
- Consistent JSON error responses
- Resources: Winston docs, structured logging patterns

**25. Testing (Unit + Integration) – 20–25h**
- Required: YES, at least moderate
- Jest setup and configuration
- Supertest for HTTP endpoint testing
- Unit tests for utility functions
- Integration tests for API routes
- Mock external dependencies
- Target: ≥70–80% coverage on at least one backend project
- Resources: Jest docs, Supertest docs, Testing best practices

---

## Docker + CI/CD + Monitoring + Flagship v1 (≈120h)

### Dev (≈70–80h)

**26. Docker (Complete) – 25–30h**
- Required: YES, moderate depth
- Dockerfile for Node app (multi-stage builds)
- .dockerignore file
- docker-compose for app + database + Redis
- Run full stack locally via docker-compose
- Push image to Docker Hub (optional but useful)
- Resources: Docker official docs, Docker for Node.js guide

**27. CI/CD (GitHub Actions) – 20–25h**
- Required: YES, basic level
- GitHub Actions workflow: lint → test → build → deploy
- Run tests on every push to main
- Build Docker image on successful tests
- Deploy to Railway, Render, or similar
- Environment secrets management
- Resources: GitHub Actions docs, Deploy to Railway tutorial

**28. Monitoring + Error Tracking – 20–25h**
- Required: YES, basic level
- Integrate Sentry into Node backend
- Set up basic performance monitoring
- Log aggregation: at minimum, understand what tools exist (ELK, Datadog, etc.)
- Create simple dashboards for:
  - Request latency
  - Error rates
  - Active users
- Resources: Sentry docs, basic monitoring concepts

**29. API Documentation – 10–15h**
- Required: YES, basic level
- Use Swagger/OpenAPI or maintain very clear Postman collection
- Document all endpoints: method, path, parameters, response formats
- Include authentication requirements
- Share documentation link in README and CV
- Resources: Swagger/OpenAPI docs, Postman documentation

---

## Core CS + Flagship Project (≈120h)

### Dev (≈70–80h)

**30. Core CS: OS + Networks + DBMS – 40–45h**
- Required: YES, interview depth
- **Operating Systems** (15–20h):
  - Processes vs threads, context switching
  - CPU scheduling basics, deadlocks
  - Memory management (virtual memory, paging)
  - I/O handling
- **Computer Networks** (15–20h):
  - TCP vs UDP
  - HTTP/HTTPS, how HTTPS works (certificates)
  - DNS resolution
  - Latency, throughput, bandwidth
  - OSI model overview
- **DBMS** (10–15h):
  - ACID properties, why they matter
  - Isolation levels (Read Uncommitted, Read Committed, etc.)
  - Indexes and query optimization
  - Normalization vs denormalization tradeoffs
- Resources: Gate Smashers YouTube (concise videos), OWASP for security concepts

**31. Flagship Project (Part 1) – 30–35h**
- Required: YES, 1–2 strong flagship apps total (2 by end of phase)
- Choose one:
  - **LMS** (courses, enrollments, progress tracking, quiz system)
  - **E-commerce** (products, cart, orders, payment integration)
  - **URL shortener + analytics** (short URLs, click tracking, analytics)
- Implement:
  - Clean architecture (MVC pattern or similar)
  - Node + Express + SQL (Postgres/MySQL)
  - Auth and RBAC
  - Proper folder structure
  - Input validation
- Start with core features, no fancy UI yet

---

## System Design Basics + Flagship Finishing (≈120h)

### Dev (≈70–80h)

**32. System Design (Basics Only) – 30–40h**
- Required: YES, basic ability to talk about design
- Concepts:
  - Vertical scaling vs horizontal scaling
  - Load balancers (concept)
  - Database replication (read replicas)
  - Caching layers (Redis, CDN)
  - CAP theorem (high-level)
  - Eventual consistency vs strong consistency
  - Sharding and partitioning (concept)
- Design simple systems:
  - URL shortener (generation, retrieval, analytics)
  - Rate-limited API (how to handle traffic spikes)
  - Simple social feed (how to handle millions of posts)
- Goal: be able to discuss scaling your own projects
- Resources: Gaurav Sen YouTube (Design Gurus free), "Grokking the System Design Interview" free version

**33. Flagship Project (Part 2) – 30–40h**
- Add production features to flagship project:
  - Caching (Redis) for expensive queries
  - Rate limiting on public endpoints
  - Logging with correlation IDs
  - Monitoring and error tracking (Sentry)
  - Tests with ≥70–80% coverage
  - Fully dockerized (Docker + docker-compose)
  - CI/CD pipeline working
  - Complete documentation (README with architecture diagram, deployment steps)
  - API documentation (Swagger or Postman collection)
  - Live deployment with working demo

---

## Polish, Apply Hard, and Optional Extras (≈120h)

### Dev (≈70–80h)

**34. Polish Portfolio – 20–25h**
- Required: YES
- GitHub: pin best 3–4 repos (especially flagships)
- Clean, detailed READMEs:
  - Problem statement
  - Tech stack
  - Features
  - Performance/scaling notes
  - How to run locally
  - Screenshots or GIFs
- Live demos:
  - Deploy at least 1–2 projects live
  - Share working links
- Portfolio website:
  - Describe flagship projects
  - Highlight scale/complexity (e.g., "Handles 1000 concurrent users with caching")
  - Link to GitHub
  - Links to deployed projects

**35. Soft Skills & Interview Talking Points – 20–25h**
- Required: YES
- Practice explaining:
  - Projects: problem you solved, tech choices, challenges, performance decisions
  - Failures/debugging: what went wrong, root cause, how you fixed it
  - Behavioral: "Tell me about yourself", "Why this company", "Biggest learning"
  - STAR method for behavioral questions (Situation, Task, Action, Result)
- Do mock interviews with friends or on Pramp
- Record yourself explaining a project; watch and improve
- Prepare 2–3 good questions to ask interviewers

**36. Optional Light Extras (basic only) – 20–30h**
- **WebSockets / real-time** – YES, basic only:
  - Add real-time notifications OR simple chat to one project
  - Use Socket.io for simplicity
  - Example: real-time order updates in e-commerce
  - NOT deep implementation, just enough for demo
- **NOT required before first job:**
  - Deep microservices, deep Kafka/RabbitMQ
  - Full ELK/Prometheus stack setup
  - Complex message queues
  - Just know conceptually what they solve

---

# PHASE 2: PLACEMENT FOCUS

**Goal**: Transition from "strong intern" to "junior SDE competitive for 12–15 LPA + top companies"

### What Changes in Phase 2

1. **Add Java backend** (Spring Boot) alongside Node
2. **Deepen system design** from basic to interview-level
3. **Build flagship projects in both ecosystems** (Node flagship + Spring Boot flagship)
4. **Strong project-based learning during internship**
5. **Target company-specific interview prep** in final months

---

## Java Fundamentals + Spring Boot Intro (≈120h)

### Dev (≈70–80h)

**37. Java OOP & Collections – 40–45h**
- Required: YES, solid working knowledge
- Topics:
  - Classes, objects, inheritance, polymorphism
  - Interfaces, abstract classes
  - Generics and type erasure (basics)
  - Exceptions: checked vs unchecked, custom exceptions
  - Collections: List, Set, Map, Queue
  - Streams API (basic functional programming)
  - Lambdas and functional interfaces
- Implement:
  - Basic OOP problems in Java (mimic simple Node projects)
  - Collection-based problems
- Resources: Java Official Tutorials, Effective Java (selected chapters)

**38. Spring Boot Fundamentals (Part 1) – 30–35h**
- Required: YES, good working knowledge
- Topics:
  - Spring Boot starter projects and conventions
  - @SpringBootApplication, configuration
  - Dependency Injection with @Autowired, constructor injection
  - Spring profiles (dev, prod)
  - Properties and YAML configuration
  - Embedded Tomcat and running apps
- Resources: Spring Boot official docs, Baeldung Spring Boot articles

---

## Spring Boot Backend + REST APIs + System Design Basics (≈120h)

### Dev (≈70–80h)

**39. Spring Boot Fundamentals (Part 2) – 25–30h**
- Spring MVC: Controllers, request mapping, path variables, query params
- REST principles in Spring
- Exception handling with @ExceptionHandler, @ControllerAdvice
- Validation: Bean Validation, custom validators
- Response structures and HTTP status codes
- Request/response serialization with Jackson
- Resources: Spring Boot Web guide, REST best practices

**40. Spring Data JPA + Hibernate – 25–30h**
- Required: YES, good depth
- Entity modeling with annotations (@Entity, @Column, @Id, @GeneratedValue)
- Relationships: @OneToMany, @ManyToOne, @ManyToMany
- CRUD operations with repositories
- Custom queries with @Query
- Lazy loading vs eager loading
- N+1 problem and prevention
- Database migrations with Flyway or Liquibase
- Resources: Spring Data JPA docs, Hibernate docs

**41. Spring Boot Project #1 (Backend API) – 20–25h**
- Recreate one of your Node.js projects in Spring Boot
- Example: LMS backend in Spring Boot + PostgreSQL
- Features:
  - RESTful endpoints for CRUD
  - JPA/Hibernate with relationships
  - Input validation
  - Proper error responses
  - Basic logging
- Deliverables: GitHub repo, Postman collection

---

## Spring Security + Advanced Spring Boot (≈120h)

### Dev (≈70–80h)

**42. Spring Security (JWT + OAuth2 Basics) – 30–35h**
- Required: YES, solid working knowledge
- Authentication and authorization
- JWT tokens: generation, validation, refresh tokens
- Password encoding (BCrypt)
- Roles and authorities: @Secured, @PreAuthorize
- CORS configuration
- API key-based auth (optional)
- OAuth2 concepts (high-level)
- Resources: Spring Security official guide, JWT with Spring

**43. Spring Boot Production Features – 20–25h**
- Spring Boot Actuator: health checks, metrics
- Caching with Spring Cache + Redis
- Logging: SLF4J and Logback configuration
- Async processing: @Async for background tasks
- Task scheduling: @Scheduled
- Error tracking integration (Sentry)
- Metrics exposure (Prometheus format optional)
- Resources: Spring Boot Actuator guide, Baeldung Spring Caching

**44. Testing with Spring Boot – 20–25h**
- Required: YES, good coverage
- JUnit 5 basics
- Spring Boot Test annotations: @SpringBootTest, @WebMvcTest
- MockMvc for testing controllers
- Mockito for mocking
- Integration tests with TestRestTemplate
- Target: 80%+ coverage on Spring Boot project
- Resources: Spring Boot Testing guide, JUnit and Mockito tutorials

---

## Flagship Project (Spring Boot) + TypeScript (≈120h)

### Dev (≈70–80h)

**45. Flagship Project (Spring Boot Part 1) – 40–45h**
- Build a substantial backend system in Spring Boot
- Example: E-commerce platform, Analytics dashboard, Project management app
- Features:
  - Multiple entity relationships (complex domain model)
  - Authentication with JWT + role-based access
  - Search/filtering with complex queries
  - Pagination and sorting
  - Caching strategy for hot queries
  - Rate limiting on public endpoints
- Start with core domain logic

**46. TypeScript + Node Refactor (Optional but Recommended) – 20–25h**
- Add TypeScript to your Node.js projects:
  - Basic types: interfaces, generics, enums
  - Function typing
  - Utility types: Partial, Omit, Pick
  - Apply to controllers, services, models
- Refactor previous project with TypeScript
- Benefits: type safety, better IDE support, more "senior" code

---

## System Design Deep + Final Polish (≈120h)

### Dev (≈70–80h)

**47. System Design (Intermediate) – 40–45h**
- Required: YES, interview-level depth
- Concepts:
  - Load balancing strategies (round-robin, least connections, hash-based)
  - Database scaling: read replicas, sharding, partitioning strategies
  - Caching architectures: cache-aside, write-through, write-behind
  - Message queues concepts (producer-consumer pattern, eventual consistency)
  - Search indexing (Elasticsearch basics)
  - CDN and edge computing
  - Monitoring and alerting patterns
  - Database consistency models (strong vs eventual)
- Design 5–7 full systems:
  - URL shortener (with analytics)
  - News feed / social media
  - E-commerce (inventory + cart + payments)
  - Messaging / chat system
  - Video streaming platform (high-level)
  - Real-time analytics / leaderboard
  - Notification system
- For each: draw architecture, discuss tradeoffs, justify tech choices
- Resources: Gaurav Sen full playlist, Alex Xu System Design Interview book (if purchased), Design Gurus

**48. Flagship Project (Spring Boot Part 2) – 20–25h**
- Add production features:
  - Redis caching for expensive queries
  - Message queue for async tasks (basic: even simple scheduling is fine)
  - Docker + docker-compose
  - CI/CD with GitHub Actions
  - Unit + integration tests (≥80% coverage)
  - Monitoring/logging/error tracking
  - Complete API documentation
  - Live deployment
  - Performance optimizations (indexing, query optimization, caching strategy documented)

**49. Node Flagship Refinement – 10–15h**
- Polish earlier Node flagship:
  - Add more features or optimize bottlenecks
  - Ensure tests and documentation are top-notch
  - Prepare live demo with clear talking points

---

## Interview Prep + Final Applications (≈120h)

### Dev (≈70–80h)

**50. Project Portfolio Polish (Final) – 25–30h**
- Required: YES, final pass
- GitHub pins: 4 best projects
  - Flagship 1 (Node) with live link
  - Flagship 2 (Spring Boot) with live link
  - 2 other strong projects
- READMEs with:
  - Architecture diagrams (ASCII or tools like Excalidraw)
  - Performance optimizations explained
  - How to run (with docker-compose examples)
  - Screenshots/GIFs of working features
  - Challenges faced and solutions
- Portfolio website: updated with latest projects and achievements
- LinkedIn: fully optimized with portfolio link

**51. Company-Specific Interview Prep – 30–35h**
- Target specific companies (Tier 1 or high-paying startups):
  - Research interview patterns
  - Study company tech stacks and products
  - Practice explaining your projects tailored to company needs
  - Prepare targeted behavioral stories
  - Mock interviews with friends targeting that company's style
- Prepare Q&A:
  - "Why this company?"
  - "Tell me about your biggest technical challenge"
  - "How did you optimize that API?"

**52. Final Behavioral + Communication Training – 15–20h**
- Required: YES
- Practice:
  - STAR method for all behavioral questions
  - Technical explanation clarity (whiteboard drawing skills if remote pair coding)
  - Asking good follow-up questions in design discussions
  - Handling "I don't know" gracefully
  - Showing curiosity about company's tech
- Record mock videos and review
- Do 3–5 final full mock interviews (simulated on-site if possible)

---

## Transition: Internship During Phase 2

**Key Insight**: Phase 2 can overlap with your actual internship.

**During Internship**:
- You're working as an intern
  - Learn real production patterns from your internship mentor/code
  - Apply learnings to your own projects
  - Don't overburden yourself; learn FROM your internship
- Post-internship:
  - Full-time mode: intensive learning + interview prep
  - Build flagship projects based on internship learnings
  - Apply aggressively to full-time roles

---

## Final Checklist Before Full-Time Interviews

- [ ] 4–5 GitHub projects with exceptional documentation
- [ ] 2 flagship projects (Node + Spring Boot) with live deployment
- [ ] Can do 5+ full system design discussions completed (on paper/whiteboard)
- [ ] 5–10 mock full interviews completed with 70%+ rating
- [ ] Company-specific interview prep for 5–10 target companies
- [ ] Portfolio website updated with all flagship projects
- [ ] LinkedIn optimized with referrals and recommendations
- [ ] Resume with quantified impact (e.g., "optimized API response time from 500ms to 100ms using Redis")
- [ ] API documentation (Swagger) for all backend projects
- [ ] Docker + CI/CD working in both Node and Spring Boot projects
- [ ] 80%+ test coverage on flagship projects
- [ ] Clear talking points for every project (problem, solution, tech choice, optimization)
- [ ] 3–5 behavioral stories polished and ready (STAR method)

---

**Last updated**: 2026  
**Target Phase 1 outcome**: Paid SDE internship  
**Target Phase 2 outcome**: 12–15 LPA off-campus full-time placement  
**Total investment**: ~4800 hours (50 hrs/week × 96 weeks)  
**Success depends on**: Consistency, real project building, aggressive applications, and learning from internship.
