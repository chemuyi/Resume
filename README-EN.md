<h1 align=center>Resume</h1>


## Personal Information
<img src="mmexport1767945535853.jpg" width='80px' hight='80px' align=right></img>
- Name: Zhang Xiang / Male / 1993
- Experience: 6 years
- Position Sought: Software Development Engineer
- Education:
    - 2017–2020: East China Normal University · M.S. · Software Engineering
    - 2012–2016: Jiangsu University of Science and Technology · B.S. · Software Engineering
- Phone: 18621817752
- Email: 18621817752@163.com
- WeChat: gongsunmiao



## Technical Skills

- Proficient in Java backend development with Spring Boot microservices; experienced in multi-module architecture design and refactoring for large-scale projects
- Skilled in Java concurrency programming, capable of independently designing async task orchestration, thread pool management, and distributed locking solutions
- Familiar with common design patterns (Factory, Template Method, Strategy, Observer, etc.) with extensive production-level practice
- Hands-on experience with Spring StateMachine for driving complex business workflows
- Proficient in Elasticsearch with self-developed data migration solutions; experienced in cluster operations and health monitoring
- Familiar with Java security (certificate management, mutual TLS authentication, encrypted communication) with security vulnerability remediation experience
- Competent in Go, capable of building backend projects from scratch; familiar with Go concurrency model and interface-driven design
- Experienced in Kubernetes Operator development and Helm Chart architecture design; knowledgeable in cloud-native ecosystem
- Proficient in JUnit and Mockito testing frameworks; committed to test coverage with comprehensive test system building experience
- Familiar with Prometheus, Grafana, Jaeger and other observability tools; experienced in microservice monitoring and distributed tracing

---

## Work Experience

### Dell Technologies · Senior Software Engineer

**Jan 2020 – Mar 2026**

Dell PPDM (PowerProtect Data Manager) is an enterprise-grade data protection and management platform deployed across thousands of enterprises worldwide. My team was responsible for the full lifecycle management of the platform, ensuring its deployment, operation, and upgrade.

**Responsibilities:**
- Designed, developed, tested, and maintained core upgrade platform modules as the primary developer of the upgrade module within the team
- Deeply involved in migrating the upgrade system from traditional VM architecture to Kubernetes cloud-native architecture
- Independently built a Go-based upgrade framework from scratch to support multiple deployment modes
- Consistently produced technical design documents, research reports, and test plans with a focus on engineering standards

---

## Project Experience

### Project 1: Enterprise Microservice Upgrade Platform (Java, Core Project)

**Description:** A large-scale Spring Boot microservice upgrade orchestration system responsible for coordinating zero-downtime, rollback-capable version upgrades across 50+ microservices in global customer environments. The project adopts a multi-module Maven architecture supporting both K8s and VM deployment modes.

**My Responsibilities & Contributions:**
- **Architecture Design:** Participated in designing and evolving a clear multi-layer modular architecture; enabled the same business logic to run across different deployment environments through interface abstraction; participated in multiple major module splits and reorganizations
- **Concurrency & State Management:** Designed async orchestration for parallel multi-component upgrades; implemented distributed locking to ensure concurrency safety; drove the full upgrade lifecycle with Spring StateMachine, implementing cross-process state recovery mechanisms more complex than database transactions
- **REST API System:** Designed a complete upgrade status and progress query API; transformed the upgrade process from script-driven to API-driven; implemented request validation, version conflict handling, and global exception interception following enterprise API standards
- **Data Layer:** Built a data access layer and cluster health monitoring system on Elasticsearch; independently developed a versioned schema migration framework supporting smooth cross-version data structure upgrades
- **Security Hardening:** Built a complete certificate management and mutual TLS authentication system; fixed path traversal vulnerabilities
- **Testing:** Built a high-coverage unit and integration testing system; drove a project-wide testing framework upgrade; authored multiple systematic test plans

### Project 2: Kubernetes Operator & Cloud-Native Migration (Java)

**Description:** Migrated the product from traditional VM deployment to Kubernetes, requiring the design of an entirely new declarative install, upgrade, and uninstall orchestration mechanism.

**My Responsibilities & Contributions:**
- Developed a custom Kubernetes Operator in Java to enable declarative lifecycle management (install → upgrade → uninstall)
- Responsible for splitting 50+ microservices from a single deployment package into a multi-group architecture; designed shared template libraries and dynamic version management to resolve cross-group configuration ownership and permission challenges
- Completed the containerization of the upgrade service with standardized REST API interfaces

### Project 3: Go Upgrade Orchestration Engine

**Description:** Built an independent upgrade orchestration framework from scratch in Go, targeting non-K8s deployment modes (Bare Metal, etc.).

**My Responsibilities & Contributions:**
- Deeply involved in the architecture design and development; implemented a three-layer orchestration abstraction model supporting flexible serial and parallel task composition
- Applied Go interface-driven design and multiple design patterns to achieve a highly extensible architecture; test code volume exceeds production code
- The framework supports three different deployment modes, validating the architecture's generality and extensibility

---

## Self-Assessment

- **Solid Technical Foundation:** 6 years focused on Java backend development with deep understanding and extensive practice in concurrency programming, state machines, design patterns, and modular architecture; capable of independently owning the design and development of complex modules
- **Failure-Oriented Design Mindset:** Extensive experience building enterprise-grade zero-downtime upgrade systems; developed a systematic defensive approach including pre-checks, timeout fallbacks, idempotent retries, and recoverable state — transferable to payments, transactions, scheduling, and other high-reliability domains
- **Dual-Language Capability:** Java as primary language (6 years), Go as secondary language (2 years); able to select the appropriate tech stack based on context and ramp up quickly on new projects
- **Strong Engineering Quality Mindset:** Committed to test-first development with emphasis on test coverage and systematic test planning; solid documentation habits with dozens of technical documents produced
- **Self-Driven Growth:** Grew from junior developer to senior engineer capable of independently owning core modules over 6 years; strong self-learning ability and problem analysis skills
