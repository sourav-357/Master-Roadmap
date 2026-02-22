# Backend-Oriented Full-Stack Developer Roadmap
## 12 Months to Internship & 24 Months to 12–15 LPA Placement

---

## Overview: Two Phases

**Phase 1 (Months 1–12)**: Foundation → Strong Internship  
**Phase 2 (Months 13–24)**: Internship → 12–15 LPA Placement

This document covers BOTH phases in one place.

---

## Global Rules (Very Important)

- **Backend language for projects**: Node.js + Express (later add TypeScript)
- **DSA language**: C++ or Java — pick one and stick to it for all DSA
- **Databases**: Learn **SQL (PostgreSQL/MySQL) first**, then **MongoDB**. Both required.
- **Frontend**: Only HTML/CSS + React (no need for more frontend frameworks before first job)
- **Advanced infra**: Only **basic** level for messaging/real-time; no deep Kafka/microservices needed before first internship

---

# PHASE 1: MONTHS 1–12 (INTERNSHIP FOCUS)

---

## Month 1: Absolute Foundations (≈120h total)

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

### DSA (≈40–50h)

**5. DSA Foundations – 40–50h**
- Required: YES, deep eventually
- Topics: arrays, strings, basic math problems, time complexity
- Problems: ~40–50 easy questions (LeetCode/HackerRank)
- Goal: get used to writing full solutions and submitting online
- Time target: Start aiming for ≤35 minutes per easy problem
- Resources: NeetCode.io, LeetCode Easy tag

---

## Month 2: Web Basics + Stronger DSA (≈120h)

### Dev (≈70–80h)

**6. HTML & CSS (Part 2) – 15–20h**
- Flexbox and Grid, responsive design (media queries)
- Project: responsive personal portfolio page
- Resources: freeCodeCamp Responsive Web Design course

**7. JavaScript Fundamentals – 40–45h**
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

**8. Small JS Projects – 15–20h**
- Calculator, todo list (localStorage), form validation
- Goal: be comfortable writing JS without copying code
- Deploy on GitHub Pages

### DSA (≈40–50h)

**9. DSA: Arrays & Strings Deep – 40–50h**
- Topics: two pointers, sliding window basics, prefix sums
- Problems: 40–50 easy (and a few easy–medium)
- Time target: easy in ≤35 minutes, moving towards 30 minutes
- Resources: NeetCode Array/String videos

---

## Month 3: React + HTTP + DSA Medium Start (≈120h)

### Dev (≈70–80h)

**10. HTTP & REST Basics – 10–15h**
- Required: YES
- HTTP methods (GET, POST, PUT, DELETE), status codes (200, 201, 400, 401, 404, 500)
- Headers, cookies vs tokens
- REST principles (resources, idempotency, stateless)
- Resources: MDN HTTP, RESTful API Design best practices

**11. React (Part 1) – 40–45h**
- Required: YES, moderate depth
- Topics:
  - JSX, functional components, props, state, events
  - useState/useEffect hooks, basic form handling
  - Component lifecycle, re-rendering
- Project: Todo app with React (no backend yet), localStorage persistence
- Resources: React.dev official tutorial, Scrimba React course

**12. React (Part 2) – 20–25h**
- React Router (multiple pages)
- Basic global state with Context API
- Project: simple "blog frontend" that fetches dummy API data (JSONPlaceholder)
- Resources: React Router docs, Context API tutorial

### DSA (≈40–50h)

**13. DSA: Intro to Mediums – 40–50h**
- Topics: binary search, basic recursion, simple linked list problems
- Problems: 15–20 mediums + more easies
- Time target: mediums in ≤60 minutes, easies trending towards ≤30 minutes
- Resources: NeetCode medium-level videos, LeetCode explore cards

---

## Month 4: Node/Express + Better DSA (≈120h)

### Dev (≈70–80h)

**14. Node.js Basics – 15–20h**
- Required: YES, deep eventually
- Node runtime, npm, modules (require/import)
- Basic scripts, event loop understanding
- Resources: Node.js official docs, freeCodeCamp Node.js course

**15. Express (Part 1) – 30–35h**
- Basic server, routes, middleware, request/response
- Error handling, status codes
- Build: simple REST API for "posts" with in-memory data
- Resources: Express.js official guide, Net Ninja Express tutorial

**16. Express (Part 2) – 20–25h**
- Folder structure (routes, controllers, middleware)
- Environment variables (dotenv)
- Better error handling with middleware
- Simple logging (console/morgan)
- Use Postman to test APIs, export collections
- Resources: Best practices guides on GitHub

### DSA (≈40–50h)

**17. DSA: Linked List, Stack, Queue – 40–50h**
- Implement these from scratch in C++/Java
- Problems: ~30–40 related questions
- Time target: easy in ≤30 minutes becomes normal
- Resources: Implement from scratch, then do LeetCode

---

## Month 5: SQL + Real APIs + DSA Trees (≈120h)

### Dev (≈70–80h)

**18. SQL (Part 1) – 30–35h**
- Required: YES, strong depth
- Install PostgreSQL/MySQL locally
- Topics: create tables, primary/foreign keys, basic joins (INNER, LEFT, RIGHT)
- SELECT, INSERT, UPDATE, DELETE queries
- ORDER BY, GROUP BY, HAVING, LIMIT
- Resources: SQLZoo interactive tutorial, freeCodeCamp SQL course

**19. SQL (Part 2) – 20–25h**
- Normalization (1NF, 2NF, 3NF basics)
- Indexing, why they matter for performance
- Transactions, ACID properties basics
- Query optimization, EXPLAIN plans
- Design DB schema for a small app (users/posts/comments)
- Resources: Database design tutorials, PostgreSQL documentation

**20. Backend Project #1 (Barebones) – 20–25h**
- Required: YES
- Node + Express + SQL (Postgres/MySQL)
- Features:
  - User registration/login (plain for now, no auth yet)
  - CRUD for posts with DB
  - Simple pagination
- Deliverables: GitHub repo, Postman collection

### DSA (≈40–50h)

**21. DSA: Trees & BST – 40–50h**
- Concepts: tree traversals (inorder, preorder, postorder), BST properties
- Problems: 25–30 tree problems
- Mediums target: getting closer to ≤50–55 minutes
- Resources: NeetCode tree videos, visualgo.net for tree animations

---

## Month 6: MongoDB + Full Stack Project + DSA Graphs (≈120h)

### Dev (≈70–80h)

**22. MongoDB – 30–35h**
- Required: YES, moderate depth
- CRUD operations, collections, documents
- Aggregations (basic pipeline)
- Indexing concepts, when to use Mongo vs SQL
- Document design best practices
- Resources: MongoDB University free courses, official docs

**23. ORM/ODM – 15–20h**
- Required: YES, basic level
- Use Prisma (for SQL) or Sequelize; use Mongoose for Mongo
- Model relationships, queries through ORM
- Resources: Prisma docs, Sequelize docs, Mongoose docs

**24. Backend Project #2: Full Stack v1 – 20–30h**
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

### DSA (≈40–50h)

**25. DSA: Graphs (BFS/DFS) – 40–50h**
- Topics: BFS, DFS, adjacency list/matrix, connected components
- Problems: 25–30 graph problems
- At this point: ~180–200 problems total
- Resources: NeetCode graph algorithms, LeetCode graph tag

---

## Month 7: Auth + Security + Better APIs + DSA DP Basics (≈120h)

### Dev (≈70–80h)

**26. Auth & Security (Deep) – 40–45h**
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

**27. Improve Existing Backend Projects – 30–35h**
- Add auth + validation to Month 5–6 projects
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

### DSA (≈40–50h)

**28. DSA: DP Basics – 40–50h**
- Topics: 0/1 knapsack, Fibonacci, LIS, grid DP, coin change
- Problems: 20–25 medium DP problems
- Medium time target: ≤45–50 minutes (moving towards the 45-min goal)
- Resources: NeetCode DP course, DP visualizations

---

## Month 8: Production Skills — Redis, Rate Limiting, Logging, Tests (≈120h)

### Dev (≈70–80h)

**29. Redis (Caching) – 20–25h**
- Required: YES, basic–good depth
- Setup Redis locally, basic commands (SET, GET, EXPIRE, DEL)
- Implement caching in Node:
  - Cache results of expensive queries
  - Set TTL (time-to-live)
  - Simple cache invalidation strategies
  - Use Redis for session storage
- Resources: Redis official docs, Redis tutorial on Node.js

**30. Rate Limiting – 10–15h**
- Required: YES, basic level
- Use express-rate-limit middleware or build with Redis
- Implement per-IP and per-user limits
- Apply to login endpoints and public APIs
- Resources: express-rate-limit docs, rate-limiting best practices

**31. Logging & Error Handling – 15–20h**
- Required: YES, basic level
- Use Winston or similar logger (not just console.log)
- Structured logging (JSON format)
- Log levels: error, warn, info, debug
- Correlation IDs for tracing requests
- Central error handler middleware
- Consistent JSON error responses
- Resources: Winston docs, structured logging patterns

**32. Testing (Unit + Integration) – 20–25h**
- Required: YES, at least moderate
- Jest setup and configuration
- Supertest for HTTP endpoint testing
- Unit tests for utility functions
- Integration tests for API routes
- Mock external dependencies
- Target: ≥70–80% coverage on at least one backend project
- Resources: Jest docs, Supertest docs, Testing best practices

### DSA (≈40–50h)

**33. DSA: Mixed Revision + More Mediums – 40–50h**
- Mix problems: arrays, graphs, trees, DP, hashmaps
- Reach ~230–250 problems total
- Goal: mediums around 45 minutes; easy ≤25–30 minutes regularly
- Do 1–2 timed sessions per week
- Resources: LeetCode premium company tags, Blind 75 list

---

## Month 9: Docker + CI/CD + Monitoring + Flagship v1 (≈120h)

### Dev (≈70–80h)

**34. Docker (Complete) – 25–30h**
- Required: YES, moderate depth
- Dockerfile for Node app (multi-stage builds)
- .dockerignore file
- docker-compose for app + database + Redis
- Run full stack locally via docker-compose
- Push image to Docker Hub (optional but useful)
- Resources: Docker official docs, Docker for Node.js guide

**35. CI/CD (GitHub Actions) – 20–25h**
- Required: YES, basic level
- GitHub Actions workflow: lint → test → build → deploy
- Run tests on every push to main
- Build Docker image on successful tests
- Deploy to Railway, Render, or similar
- Environment secrets management
- Resources: GitHub Actions docs, Deploy to Railway tutorial

**36. Monitoring + Error Tracking – 20–25h**
- Required: YES, basic level
- Integrate Sentry into Node backend
- Set up basic performance monitoring
- Log aggregation: at minimum, understand what tools exist (ELK, Datadog, etc.)
- Create simple dashboards for:
  - Request latency
  - Error rates
  - Active users
- Resources: Sentry docs, basic monitoring concepts

**37. API Documentation – 10–15h**
- Required: YES, basic level
- Use Swagger/OpenAPI or maintain very clear Postman collection
- Document all endpoints: method, path, parameters, response formats
- Include authentication requirements
- Share documentation link in README and CV
- Resources: Swagger/OpenAPI docs, Postman documentation

### DSA (≈40–50h)

**38. DSA: Targeted Interview Sets – 40–50h**
- Do company-tagged problems (Amazon/Google tags on LeetCode)
- 20–30 representative medium questions
- Start doing mock interviews (Pramp or with friends)
- Time yourself: simulate real interview pressure

👉 **From end of Month 9, START applying for internships** while continuing the plan.

---

## Month 10: Core CS + Flagship Project (≈120h)

### Dev (≈70–80h)

**39. Core CS: OS + Networks + DBMS – 40–45h**
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

**40. Flagship Project (Part 1) – 30–35h**
- Required: YES, 1–2 strong flagship apps total (2 by month 11)
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

### DSA (≈40–50h)

**41. DSA: Systematic Gaps Fixing – 40–50h**
- Identify weak topics (e.g., DP, graphs, strings); grind 20–25 focused problems
- Start 1 mock interview weekly
- Review mistakes carefully

---

## Month 11: System Design Basics + Flagship Finishing (≈120h)

### Dev (≈70–80h)

**42. System Design (Basics Only) – 30–40h**
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

**43. Flagship Project (Part 2) – 30–40h**
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

### DSA (≈40–50h)

**44. DSA: Full Mock Focus – 40–50h**
- Timed sets: 2–3 questions in ~90 minutes to simulate real interview
- Aim: easy ≤20–25 minutes, medium ≤35–45 minutes as specified
- Do mock interviews on Pramp or LeetCode Premium
- Review approach and mistakes carefully

---

## Month 12: Polish, Apply Hard, and Optional Extras (≈120h)

### Dev (≈70–80h)

**45. Polish Portfolio – 20–25h**
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

**46. Soft Skills & Interview Talking Points – 20–25h**
- Required: YES
- Practice explaining:
  - Projects: problem you solved, tech choices, challenges, performance decisions
  - Failures/debugging: what went wrong, root cause, how you fixed it
  - Behavioral: "Tell me about yourself", "Why this company", "Biggest learning"
  - STAR method for behavioral questions (Situation, Task, Action, Result)
- Do mock interviews with friends or on Pramp
- Record yourself explaining a project; watch and improve
- Prepare 2–3 good questions to ask interviewers

**47. Optional Light Extras (basic only) – 20–30h**
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

### DSA (≈40–50h)

**48. Final DSA Push – 40–50h**
- Reach ~300–350 questions total
- Weekly mocks: 2–3 sessions
- Review all mistakes
- Prepare company-specific question lists (if targeting specific companies)

---

# PHASE 2: MONTHS 13–24 (PLACEMENT FOCUS)

**Goal**: Transition from "strong intern" to "junior SDE competitive for 12–15 LPA + top companies"

### What Changes in Phase 2

1. **Add Java backend** (Spring Boot) alongside Node
2. **Deepen system design** from basic to interview-level
3. **Push DSA from 350 to 500+ problems** (more mediums, some hards)
4. **Build flagship projects in both ecosystems** (Node flagship + Spring Boot flagship)
5. **Strong project-based learning during internship**
6. **Target company-specific interview prep** in final months

---

## Month 13–14: Java Fundamentals + Spring Boot Intro (≈120h)

### Dev (≈70–80h)

**49. Java OOP & Collections – 40–45h**
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

**50. Spring Boot Fundamentals (Part 1) – 30–35h**
- Required: YES, good working knowledge
- Topics:
  - Spring Boot starter projects and conventions
  - @SpringBootApplication, configuration
  - Dependency Injection with @Autowired, constructor injection
  - Spring profiles (dev, prod)
  - Properties and YAML configuration
  - Embedded Tomcat and running apps
- Resources: Spring Boot official docs, Baeldung Spring Boot articles

### DSA (≈40–50h)

**51. DSA: Medium Push – 40–50h**
- Target: 50–60 medium-level problems
- Focus: mix of all topics (arrays, trees, graphs, DP, strings)
- Speed goal: medium in ≤40–45 minutes (trending toward 40)
- Mock interviews: 1 per week, 2–3 problems in 90 minutes
- Total problems now: ~380–400

---

## Month 15–16: Spring Boot Backend + REST APIs + System Design Basics (≈120h)

### Dev (≈70–80h)

**52. Spring Boot Fundamentals (Part 2) – 25–30h**
- Spring MVC: Controllers, request mapping, path variables, query params
- REST principles in Spring
- Exception handling with @ExceptionHandler, @ControllerAdvice
- Validation: Bean Validation, custom validators
- Response structures and HTTP status codes
- Request/response serialization with Jackson
- Resources: Spring Boot Web guide, REST best practices

**53. Spring Data JPA + Hibernate – 25–30h**
- Required: YES, good depth
- Entity modeling with annotations (@Entity, @Column, @Id, @GeneratedValue)
- Relationships: @OneToMany, @ManyToOne, @ManyToMany
- CRUD operations with repositories
- Custom queries with @Query
- Lazy loading vs eager loading
- N+1 problem and prevention
- Database migrations with Flyway or Liquibase
- Resources: Spring Data JPA docs, Hibernate docs

**54. Spring Boot Project #1 (Backend API) – 20–25h**
- Recreate one of your Node.js projects in Spring Boot
- Example: LMS backend in Spring Boot + PostgreSQL
- Features:
  - RESTful endpoints for CRUD
  - JPA/Hibernate with relationships
  - Input validation
  - Proper error responses
  - Basic logging
- Deliverables: GitHub repo, Postman collection

### DSA (≈40–50h)

**55. DSA: Hard Problems Intro + System Design Prep – 40–50h**
- Target: 40–50 medium problems + 3–5 hard problems
- Start thinking about optimization: time vs space tradeoffs
- Do mock interviews: 1–2 per week
- Total problems now: ~430–450

---

## Month 17–18: Spring Security + Advanced Spring Boot (≈120h)

### Dev (≈70–80h)

**56. Spring Security (JWT + OAuth2 Basics) – 30–35h**
- Required: YES, solid working knowledge
- Authentication and authorization
- JWT tokens: generation, validation, refresh tokens
- Password encoding (BCrypt)
- Roles and authorities: @Secured, @PreAuthorize
- CORS configuration
- API key-based auth (optional)
- OAuth2 concepts (high-level)
- Resources: Spring Security official guide, JWT with Spring

**57. Spring Boot Production Features – 20–25h**
- Spring Boot Actuator: health checks, metrics
- Caching with Spring Cache + Redis
- Logging: SLF4J and Logback configuration
- Async processing: @Async for background tasks
- Task scheduling: @Scheduled
- Error tracking integration (Sentry)
- Metrics exposure (Prometheus format optional)
- Resources: Spring Boot Actuator guide, Baeldung Spring Caching

**58. Testing with Spring Boot – 20–25h**
- Required: YES, good coverage
- JUnit 5 basics
- Spring Boot Test annotations: @SpringBootTest, @WebMvcTest
- MockMvc for testing controllers
- Mockito for mocking
- Integration tests with TestRestTemplate
- Target: 80%+ coverage on Spring Boot project
- Resources: Spring Boot Testing guide, JUnit and Mockito tutorials

### DSA (≈40–50h)

**59. DSA: Company-Specific Grinding – 40–50h**
- Target: 50–60 more medium problems
- Filter by company (Amazon, Google, Microsoft tags on LeetCode)
- Focus on weak topics identified from mocks
- Do 2 mock interviews per week
- Total problems now: ~490–510 (approaching 500+)

---

## Month 19–20: Flagship Project (Spring Boot) + TypeScript (≈120h)

### Dev (≈70–80h)

**60. Flagship Project (Spring Boot Part 1) – 40–45h**
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

**61. TypeScript + Node Refactor (Optional but Recommended) – 20–25h**
- Add TypeScript to your Node.js projects:
  - Basic types: interfaces, generics, enums
  - Function typing
  - Utility types: Partial, Omit, Pick
  - Apply to controllers, services, models
- Refactor Month 6 or Month 10 project with TypeScript
- Benefits: type safety, better IDE support, more "senior" code

### DSA (≈40–50h)

**62. DSA: Hard Problems + System Design – 40–50h**
- Target: 40–50 medium problems + 8–10 hard problems
- Start seeing patterns in hard problems
- 1–2 mock interviews per week
- Total problems now: ~540–570

---

## Month 21–22: System Design Deep + Final Polish (≈120h)

### Dev (≈70–80h)

**63. System Design (Intermediate) – 40–45h**
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

**64. Flagship Project (Spring Boot Part 2) – 20–25h**
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

**65. Node Flagship Refinement – 10–15h**
- Polish earlier Node flagship (from Month 10–11):
  - Add more features or optimize bottlenecks
  - Ensure tests and documentation are top-notch
  - Prepare live demo with clear talking points

### DSA (≈40–50h)

**66. DSA: Final Polish + Mock Blitz – 40–50h**
- Target: 50–60 more mediums + 5–8 hards
- 2–3 mock interviews per week
- Review all major patterns
- Total problems now: ~620–650+

---

## Month 23–24: Interview Prep + Final Applications (≈120h)

### Dev (≈70–80h)

**67. Project Portfolio Polish (Final) – 25–30h**
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

**68. Company-Specific Interview Prep – 30–35h**
- Target specific companies (Tier 1 or high-paying startups):
  - Research interview patterns
  - Grind company-specific DSA problems (LeetCode filters)
  - Study company tech stacks and products
  - Practice explaining your projects tailored to company needs
  - Prepare targeted behavioral stories
  - Mock interviews with friends targeting that company's style
- Prepare Q&A:
  - "Why this company?"
  - "Tell me about your biggest technical challenge"
  - "How did you optimize that API?"

**69. Final Behavioral + Communication Training – 15–20h**
- Required: YES
- Practice:
  - STAR method for all behavioral questions
  - Technical explanation clarity (whiteboard drawing skills if remote pair coding)
  - Asking good follow-up questions in design discussions
  - Handling "I don't know" gracefully
  - Showing curiosity about company's tech
- Record mock videos and review
- Do 3–5 final full mock interviews (simulated on-site if possible)

### DSA (≈40–50h)

**70. DSA: Final Grinding + Mock Interviews – 40–50h**
- Target: continue with mediums and hards
- Do 3–4 full mock interviews per week (90-minute sessions)
- Final problem count: **650–700+ problems total** (mix of easy/medium/hard, with most being medium)
- Review common patterns one last time
- Confidence building: review your best solutions

---

## Transition: Internship During Phase 2

**Key Insight**: Months 13–24 can overlap with your actual internship (likely Months 13–18 or longer).

**During Internship**:
- Month 13–18: You're working as an intern
  - Learn real production patterns from your internship mentor/code
  - Apply learnings to your own projects
  - Do light DSA prep (1 hour/day, not heavy)
  - Don't overburden yourself; learn FROM your internship
- Month 19–24: After internship ends
  - Full-time mode: intensive learning + interview prep
  - Build flagship projects based on internship learnings
  - Heavy DSA prep + system design
  - Apply aggressively to full-time roles

---

## Technologies: Yes/No/Optional (Complete View)

### **REQUIRED — Phase 1 (Internship)**

Already listed in Phase 1 section. Recap:
- C++/Java (DSA), React, Node.js, Express, SQL, MongoDB, Docker, CI/CD, JWT, Redis, Jest/Supertest, basic system design concepts, 300–350 DSA problems

### **REQUIRED — Phase 2 (Placement)**

Adding to Phase 1:
- **Java OOP + Spring Boot** (strong working knowledge)
- **Spring Data JPA + Hibernate** (solid depth)
- **Spring Security with JWT** (interview-level)
- **TypeScript basics** (apply to Node projects)
- **System Design** (intermediate; design 5–7 real systems)
- **500–700 DSA problems** (mix of medium and hard)
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

### DSA Velocity

- **Phase 1 End (Month 12)**: ~350 problems, medium in ≤45 min, easy in ≤25 min
- **Phase 2 Mid (Month 18)**: ~500 problems, medium in ≤40 min, easy in ≤20 min
- **Phase 2 End (Month 24)**: ~650–700 problems, medium in ≤35–40 min, easy in ≤15–20 min

### Project Progression

- **Month 4**: Barebones CRUD API
- **Month 6**: Full-stack app deployed
- **Month 9**: Production-ready 2nd project
- **Month 11**: Flagship Node project (fully featured)
- **Month 15**: Spring Boot backend API recreated
- **Month 20**: Flagship Spring Boot project (fully featured)
- **Month 24**: 2 polished flagships + 2–3 additional quality projects

### Application Timeline

- **Internship**: Start Month 9, secure by Month 10–12
- **Full-time roles**: Start applying Month 19 onwards
- **Target**: 50+ applications/month from Month 20–24
- **Response rate target**: 5–10% (5–10 interviews from 100 apps)
- **Offer target**: Secure 12–15 LPA role by Month 24

---

## When to Apply for Full-Time Roles (Phase 2)

- **Start applying**: Month 19 (after internship ends or overlap)
- **Heavy pushing**: Months 20–24
- **Ideal readiness**: Month 22–24
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
- **Advanced DSA**: LeetCode hard tag, company-specific collections
- **Mock Interviews**: Pramp, Interviewing.io, friends from community

---

## Daily/Weekly Habits (Phase 2)

**During Internship (Months 13–18)**:
- **Daily**: 1–2 hours dev (learning from internship code), 30 min DSA
- **Weekly**: 1 code review, 1 DSA session, 1 small project improvement

**Post-Internship (Months 19–24)**:
- **Daily**: 2–3 hours dev (flagship projects), 1–2 hours DSA + system design
- **Weekly**:
  - 2–3 DSA mock sessions
  - 1 system design practice (design a new system)
  - 1 project milestone (feature, optimization, or test coverage)
  - 1–2 mock interviews (full 90-min session)
- **Bi-weekly**: Polish one project's documentation/demo

---

## Final Checklist Before Full-Time Interviews (Month 24)

- [ ] 4–5 GitHub projects with exceptional documentation
- [ ] 2 flagship projects (Node + Spring Boot) with live deployment
- [ ] 700+ LeetCode problems solved (mix of easy/medium/hard)
- [ ] Can solve mediums consistently in ≤40 minutes
- [ ] Can do hard problems with some thought
- [ ] 5+ full system design discussions completed (on paper/whiteboard)
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

## Honest Reality Check

### Phase 1 (Months 1–12):
- Ambitious but achievable at 50 hrs/week
- Success factors: consistency, project focus, DSA discipline, aggressive applications

### Phase 2 (Months 13–24):
- Ranges from moderate to heavy depending on internship load
- During internship: lighter load (learn from real work)
- Post-internship: heavy load (2–3 hrs dev + 1–2 hrs DSA daily)
- Critical: **Don't waste internship**; apply learnings to side projects

### Key Success Factors (Both Phases):
1. **Consistency over perfection** — Show up daily, even if just 1 hour
2. **Real projects beat tutorials** — Build, deploy, get feedback
3. **DSA is non-negotiable** — Without strong DSA, interviews will fail regardless of projects
4. **Portfolio visibility** — GitHub, live demos, and talking about your work matter enormously
5. **Aggressive application strategy** — 50+ apps/month; expect 3–5% response
6. **Learn from feedback** — Each rejection/failure is data; adjust accordingly
7. **Internship is gold** — Real production code > tutorial projects. Absorb everything.
8. **Network and referrals** — After internship, leverage connections for referrals (massively higher conversion)

---

## Summary: Your Path to 12–15 LPA

**Phase 1 (Months 1–12)**:
→ Build strong foundation (Node + React + DSA)  
→ Get a solid SDE internship (apply from Month 9)  

**Phase 2 (Months 13–24)**:
→ Learn production best practices during internship (Months 13–18)  
→ Build Java/Spring Boot backend expertise (Months 15–22)  
→ Master system design at interview level (Months 17–22)  
→ Build flagship projects showing depth (Months 19–22)  
→ Apply aggressively to full-time roles (Months 20–24)  
→ **Target 12–15 LPA placement by Month 24**  

---

**Last updated**: February 2026  
**Target Phase 1 outcome**: Paid SDE internship  
**Target Phase 2 outcome**: 12–15 LPA off-campus full-time placement  
**Total investment**: ~4800 hours (50 hrs/week × 96 weeks)  
**Success depends on**: Consistency, real project building, DSA mastery, aggressive applications, and learning from internship.
