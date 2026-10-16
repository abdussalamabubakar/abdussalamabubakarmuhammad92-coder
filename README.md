# Abubakar Abdussalam Muhammad

### Software Engineer | Backend Systems | Full-Stack Product Engineering | AI & Security

I build software systems from the problem definition to the implementation.

My work spans backend engineering, full-stack applications, AI-powered systems, and security-conscious software design. I enjoy understanding how a system should work beneath the interface: its data model, business rules, APIs, failure modes, security boundaries, and the trade-offs that shape its architecture.

I independently design and build complete software systems, and I also contribute to existing codebases where I take ownership of substantial engineering features.

**Currently seeking full-time remote software engineering opportunities.**

[GitHub](https://github.com/abdussalamabubakar) ·
[LinkedIn](https://linkedin.com/in/abdussalam-abubakar-muhammad-b72687394) ·
[Email](mailto:abdussalamabubakarmuhammad92@gmail.com)

---

## What I Bring to Engineering

I care about more than getting an application to work. I care about why it works, what happens when things fail, and whether the underlying design will remain understandable and reliable as the system evolves.

- **Backend engineering:** Designing APIs, data models, business logic, authentication, authorization, and service boundaries.
- **Full-stack development:** Connecting backend systems to usable interfaces and carrying features across the application.
- **Systems thinking:** Modeling business workflows, state transitions, concurrency, data integrity, and interactions between components.
- **Security-minded development:** Considering access control, isolation, input validation, secrets, abuse cases, and failure scenarios.
- **Reliability and correctness:** Using transactions, database constraints, idempotency, automated tests, and explicit failure handling where appropriate.
- **AI integration:** Building agent workflows, integrating model providers, implementing tool calling, and connecting AI capabilities to application infrastructure.
- **Engineering judgment:** Choosing appropriate abstractions, documenting trade-offs, and avoiding unnecessary complexity.
- **Collaborative delivery:** Working with Git branches, meaningful commits, pull requests, automated tests, and existing codebases.

## Selected Engineering Work

### 1. Africa AI Developer Cloud — Naszat Labs

**AI Integration Engineering | Go | Fiber | Next.js | TypeScript | PostgreSQL | Redis**

Contributed to a multi-tenant AI and cloud platform designed to make AI models and cloud services accessible to developers through a usage-metered platform.

I was invited to lead the AI integration work within an existing codebase. My contribution covered substantial backend functionality, AI agent execution, provider integrations, frontend integration, and improvements to billing, security, and reliability.

**Engineering highlights:**

- Built an AI agent execution loop covering model routing, credit reservation, iterative model and tool execution, and final billing.
- Implemented five sandboxed tools for file operations, command execution, codebase search, and file listing.
- Added workspace path-containment protections and optional Docker isolation with restricted network access and resource limits.
- Integrated multiple model providers through a common adapter architecture.
- Implemented developer API keys with hashed key storage, scopes, expiration, revocation, and Redis-backed rate limiting.
- Strengthened payment and billing flows through verification, idempotency, transactional credit handling, and fail-closed pricing behaviour.
- Tested concurrent wallet reservations using PostgreSQL row locking.
- Contributed notifications, usage analytics, integration tests, documentation, and CI/CD improvements.

**Delivery:** Phase 1 changes were submitted through a feature branch and pull request, then merged by the project owner. The AI agent is live.

This work strengthened my experience in extending an existing architecture, handling financial correctness, integrating external AI services, and delivering substantial changes through a collaborative engineering workflow.

---

### 2. SUG E-Voting System

**Independent Project Ownership | Python | Django | PostgreSQL | Redis | Celery**

A student-government election platform built around voter eligibility, election lifecycle management, role-based access, ballot handling, and auditability.

I owned the technical direction and implementation across the backend and frontend.

**Engineering highlights:**

- Designed the data model and election lifecycle.
- Implemented authentication and role-based workflows for voters, administrators, and election officers.
- Separated voter participation records from ballot records to establish an application-level anonymity boundary.
- Implemented transactional voting logic and database row locking to prevent concurrent duplicate voting.
- Added candidate approval, voter eligibility checks, CSV imports, result exports, and audit logging.
- Wrote tests covering duplicate voting and concurrent submissions.
- Documented architectural decisions, the threat model, the anonymity model, and known limitations.

**Engineering focus:** Security-sensitive data modeling, transactional correctness, concurrency control, authorization, and auditability.

---

### 3. Supply Chain Monitoring System (SCMS)

**Independent Project Ownership | Python | Django | React | PostgreSQL | Redis | Docker**

A supply-chain operations system combining inventory management, shipment monitoring, simulated sensor telemetry, alerting, forecasting, and tamper-evident records.

I designed and implemented the system across the backend and frontend, including its core data models, workflows, and engineering decisions.

**Engineering highlights:**

- Modeled shipment lifecycles using explicit state transitions and business rules.
- Implemented simulated telemetry for temperature, humidity, vibration, and location.
- Built breach detection and alert-generation workflows.
- Implemented a SHA-256 hash-chained ledger for tamper-evident transaction history.
- Developed demand forecasting and inventory recommendations using historical demand, lead times, reorder points, and safety stock.
- Designed background tasks for shipment simulation, delay detection, and scheduled forecasting.
- Developed focused engineering implementations covering authorization, concurrency, state machines, integrity verification, forecasting, telemetry monitoring, and inventory logic.

**Engineering focus:** Domain modeling, operational workflows, data integrity, background processing, forecasting, and system reliability.

---

### 4. StudyShelf

**Independent Project Ownership | Python | Django REST Framework | React | TypeScript | PostgreSQL**

A full-stack academic resource platform where students can discover and download course materials while contributors and administrators operate through controlled workflows.

I designed and built the application end-to-end, including its product structure, backend, API, frontend, access model, and deployment approach.

**Engineering highlights:**

- Built a single-origin Django and React application.
- Designed an invitation-based contributor system using one-time, expiring, and revocable invitation links.
- Allowed students to browse resources without requiring accounts.
- Implemented resource browsing, PDF viewing, downloads, batch uploads, and contributor and administrator workflows.
- Wrote 42 backend tests covering authentication, invitations, permissions, resource ownership, password resets, downloads, and administration.
- Documented architectural trade-offs through 13 Architecture Decision Records (ADRs).
- Investigated application-serving failures and added regression coverage for missing frontend assets.
- Deliberately deferred unnecessary infrastructure until justified by actual requirements.

**Engineering focus:** End-to-end product delivery, access-control design, testing, debugging, architecture decisions, and pragmatic engineering.

---

## Technical Skills

### Languages
Python · Go · TypeScript · JavaScript · SQL

### Backend & APIs
Django · Django REST Framework · FastAPI · Go Fiber · REST APIs · JWT · Celery

### Frontend
React · Next.js · TypeScript · Tailwind CSS

### Databases & Data
PostgreSQL · SQLite · Redis · Relational Data Modeling · Transactions · Concurrency Control

### Infrastructure & Delivery
Docker · Docker Compose · Git · GitHub Actions · Linux/WSL2 · Caddy · MinIO · CI/CD

### Security & Reliability
Authentication · Authorization · RBAC · Input Validation · API Security · Sandboxing · Audit Logging · Data Integrity · Idempotency · Failure Handling · Automated Testing

### AI & Integrations
LLM APIs · AI Agents · Tool Calling · Multi-Provider Model Integration · Usage Metering · Payment Integrations

---

## How I Approach Engineering

**Understand before implementing.**

I prefer understanding the problem, the existing architecture, and the constraints before making changes.

**Model the problem, not just the interface.**

I think about the underlying entities, relationships, business rules, state transitions, and invariants that the application must preserve.

**Correctness matters.**

For security-sensitive or financial workflows, I pay particular attention to authorization, concurrency, transactions, validation, and failure handling.

**Use complexity deliberately.**

I don't consider additional infrastructure or abstractions inherently better. I prefer designs whose complexity is justified by the problem and whose trade-offs are understood.

**Use AI as leverage, not a substitute for judgment.**

I use AI coding tools to accelerate exploration, implementation, and debugging. I remain responsible for technical decisions, reviewing changes, verifying behaviour, and determining whether an implementation is appropriate.

**Make decisions explainable.**

I value tests, architecture documentation, meaningful commits, and explicit trade-offs because engineering work should be understandable beyond the moment it was written.

---

## Currently Interested In

- Backend and full-stack product engineering
- AI-powered applications and agent infrastructure
- Cloud infrastructure and security automation
- Reliable APIs and data-intensive systems
- Distributed and asynchronous processing
- Security-conscious system design

---

## Education

**B.Sc. Cybersecurity**  
Federal University Dutse, Nigeria

My cybersecurity background informs how I approach software engineering, particularly around trust boundaries, authorization, data handling, and failure scenarios.

---

## Let's Connect

I'm interested in joining a team where engineers take ownership, think critically about product and system design, and work together to build useful, reliable software.

**Open to full-time remote software engineering roles.**

- GitHub:(https://github.com/abdussalamabubakar)
- LinkedIn: [Abubakar Abdussalam Muhammad](https://linkedin.com/in/abdussalam-abubakar-muhammad-b72687394)
- Email: [abdussalamabubakarmuhammad92@gmail.com](mailto:abdussalamabubakarmuhammad92@gmail.com)
