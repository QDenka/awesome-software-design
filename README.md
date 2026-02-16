<p align="center">
  <a href="https://github.com/QDenka/awesome-software-design">
    <img src="logo.png" width="200">
  </a>
</p>

<h1 align="center">Awesome Software Design</h1>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
</p>

> Design-in-practice: implementation patterns, decision records, verification rules, and real operational lessons.

## Contents

- [Implementation Patterns & Reference Code](#implementation-patterns--reference-code)
- [Decision Records (ADR/RFC)](#decision-records-adrrfc)
- [Architecture Verification (CI Rules / Fitness Functions)](#architecture-verification-ci-rules--fitness-functions)
- [Operational Case Studies (Curated, Short)](#operational-case-studies-curated-short)
- [Documentation as Code](#documentation-as-code)
- [Books](#books)
- [Community](#community)

---

## Implementation Patterns & Reference Code

- [ThreeDotsLabs/watermill](https://github.com/ThreeDotsLabs/watermill) - Go library for building event-driven applications with Pub/Sub, CQRS, and middleware support.
- [ThreeDotsLabs/wild-workouts-go-ddd-example](https://github.com/ThreeDotsLabs/wild-workouts-go-ddd-example) - Production-ready Go example combining Clean Architecture, CQRS, and gRPC with detailed blog series.
- [kgrzybek/modular-monolith-with-ddd](https://github.com/kgrzybek/modular-monolith-with-ddd) - Full Modular Monolith with DDD, CQRS, and integration events in C# — reference project.
- [CodelyTV/php-ddd-example](https://github.com/CodelyTV/php-ddd-example) - PHP DDD skeleton with Hexagonal Architecture, CQRS, and event bus using Symfony.
- [Serverless Patterns Collection](https://serverlessland.com/patterns) - AWS-curated serverless architecture patterns with deployable SAM/CDK templates.
- [Azure Cloud Design Patterns](https://learn.microsoft.com/en-us/azure/architecture/patterns/) - Microsoft's 30+ cloud patterns for availability, data management, and resilience.
- [AWS Cloud Design Patterns](https://docs.aws.amazon.com/prescriptive-guidance/latest/cloud-design-patterns/introduction.html) - Amazon's prescriptive guidance covering decomposition, messaging, and data patterns.
- [Microservices Patterns](https://microservices.io/) - Chris Richardson's comprehensive catalog of microservice patterns including Saga, API Gateway, and CQRS.
- [patchlevel/event-sourcing](https://github.com/patchlevel/event-sourcing) - Modern PHP Event Sourcing library with snapshots, projections, and Doctrine integration.
- [Event Modeling](https://www.eventmodeling.org/) - Visual method for designing event-driven systems with a timeline of commands, events, and views.
- [Cell-Based Architecture](https://github.com/wso2/reference-architecture/blob/master/reference-architecture-cell-based.md) - WSO2's reference architecture for building resilient distributed systems with isolated cells.

### Design Patterns

- [Refactoring.Guru](https://refactoring.guru/design-patterns) - Visual catalog of all 23 GoF patterns with UML diagrams and code in 10+ languages.
- [DesignPatternsPHP](https://github.com/DesignPatternsPHP/DesignPatternsPHP) - All known design patterns in PHP 8.1+ with real-world examples, UML diagrams, and tests.
- [kamranahmedse/design-patterns-for-humans](https://github.com/kamranahmedse/design-patterns-for-humans) - Guide explaining design patterns with real-world analogies, not academic jargon.
- [iluwatar/java-design-patterns](https://github.com/iluwatar/java-design-patterns) - Collection of GoF, enterprise, and architectural patterns implemented in Java.
- [tmrts/go-patterns](https://github.com/tmrts/go-patterns) - Idiomatic Go implementations of creational, structural, behavioral, and concurrency patterns.
- [Source Making — Design Patterns](https://sourcemaking.com/design_patterns) - Comprehensive reference with UML diagrams, code examples, and anti-pattern explanations.
- [Christopher Okhravi — Design Patterns](https://www.youtube.com/playlist?list=PLrhzvIcii6GNjpARdnO4ueTUAVR9eMBpc) - Video series walking through each GoF pattern with clear explanations and real-world context.
- [faif/python-patterns](https://github.com/faif/python-patterns) - Collection of design patterns and idioms implemented in Python with concise examples.

## Decision Records (ADR/RFC)

- [joelparkerhenderson/architecture-decision-record](https://github.com/joelparkerhenderson/architecture-decision-record) - Collection of ADR templates, examples, and best practices from real projects.
- [npryce/adr-tools](https://github.com/npryce/adr-tools) - Bash-based CLI for creating, superseding, and managing ADR documents in a project.
- [adr/madr](https://github.com/adr/madr) - Markdown Any Decision Records — lean template capturing context, decision, and consequences.
- [Documenting Architecture Decisions](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions) - Michael Nygard's original blog post that started the ADR movement and defined the format.
- [adr.github.io](https://adr.github.io/) - Central hub of the ADR GitHub organization aggregating tools, templates, and examples.
- [log4brains](https://github.com/thomvaill/log4brains) - Docs-as-code knowledge base that auto-generates a searchable static site from ADR files.
- [adr/e-adr](https://github.com/adr/e-adr) - Embedded Architectural Decision Records for capturing decisions directly in source code.
- [Kubernetes KEPs](https://github.com/kubernetes/enhancements/tree/master/keps) - Real-world architecture decision process at scale — Kubernetes Enhancement Proposals.
- [Spotify ADR Practice](https://engineering.atspotify.com/2020/04/when-should-i-write-an-architecture-decision-record/) - Spotify engineering on when, why, and how to write effective ADRs.
- [GOV.UK RFCs](https://github.com/alphagov/govuk-rfcs) - UK Government Digital Service architecture decisions — excellent public sector ADR example.
- [GitHub Actions Toolkit ADRs](https://github.com/actions/toolkit/tree/main/docs/adrs) - Architecture Decision Records from GitHub's official Actions toolkit.
- [Rust RFCs](https://github.com/rust-lang/rfcs) - Rust language design decisions captured as RFCs — one of the best public RFC processes.
- [Next.js RFCs](https://github.com/vercel/next.js/discussions/categories/rfc) - Vercel's public RFC discussions for Next.js architectural changes and new features.
- [Flutter Design Docs](https://github.com/flutter/flutter/wiki/Design-Documents) - Flutter's public design document process for major architectural decisions.

### System Design & API Foundations

- [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer) - Comprehensive resource covering scalability, caching, load balancing, and architecture trade-offs.
- [ByteByteGo](https://bytebytego.com/) - Alex Xu's system design course with visual deep dives into distributed systems internals.
- [karanpratapsingh/system-design](https://github.com/karanpratapsingh/system-design) - Free system design course covering networking, databases, caching, and real-world case studies.
- [High Scalability](https://highscalability.com/) - Real architecture case studies from Netflix, Twitter, and other high-traffic systems.
- [API Design Guide by Google](https://cloud.google.com/apis/design) - Google's resource-oriented API design standard used across all Google Cloud APIs.
- [Microsoft REST API Guidelines](https://github.com/microsoft/api-guidelines) - Microsoft's battle-tested guidelines for consistent, developer-friendly RESTful APIs.
- [Use The Index, Luke](https://use-the-index-luke.com/) - In-depth SQL indexing guide teaching developers how databases execute queries efficiently.
- [RabbitMQ Tutorials](https://www.rabbitmq.com/tutorials) - Official tutorials covering work queues, pub/sub, routing, and RPC messaging patterns.
- [Apache Kafka Documentation](https://kafka.apache.org/documentation/) - Complete reference for Kafka's distributed streaming platform, partitioning, and consumer groups.
- [Rate Limiting Strategies](https://cloud.google.com/architecture/rate-limiting-strategies-techniques) - Google Cloud guide covering token bucket, leaky bucket, and sliding window algorithms.

## Documentation as Code

- [C4 Model](https://c4model.com/) - Simon Brown's four-level model (Context, Container, Component, Code) for architecture visualization.
- [D2 Language](https://d2lang.com/) - Modern declarative diagramming language with auto-layout that compiles to SVG and PNG.
- [Mermaid](https://github.com/mermaid-js/mermaid) - JavaScript diagramming tool rendering flowcharts, sequence diagrams from Markdown syntax.
- [Diagrams as Code](https://github.com/mingrammer/diagrams) - Draw AWS, Azure, GCP, and Kubernetes architecture diagrams in Python with provider icons.
- [dependency-cruiser](https://github.com/sverweij/dependency-cruiser) - Validate and visualize JavaScript/TypeScript module dependencies against architecture rules.
- [Ilograph](https://www.ilograph.com/) - Interactive architecture diagrams with multi-perspective views and drill-down navigation.
- [Terrastruct](https://terrastruct.com/) - Commercial platform for creating interactive architecture diagrams powered by D2.
- [Structurizr](https://structurizr.com/) - Official C4 tooling by Simon Brown: architecture-as-code via DSL with interactive, zoomable diagrams.
- [PlantUML](https://plantuml.com/) - Widely-adopted diagrams-as-code tool for UML/C4 and architecture visuals with strong IDE and CI integration.

## Architecture Verification (CI Rules / Fitness Functions)

- [phparkitect/arkitect](https://github.com/phparkitect/arkitect) - Define PHP architecture rules with expressive DSL — enforce layer dependencies in CI.
- [pestphp/pest-plugin-arch](https://github.com/pestphp/pest-plugin-arch) - Fluent architecture testing for Laravel/Pest — `expect()->toUseNothing()` style assertions.
- [TNG/ArchUnit](https://github.com/TNG/ArchUnit) - Industry-standard Java library for checking architecture constraints as unit tests.
- [TNG/ArchUnitNET](https://github.com/TNG/ArchUnitNET) - .NET port of ArchUnit for enforcing architecture rules in C# projects.
- [arch-go/arch-go](https://github.com/arch-go/arch-go) - Architecture testing for Go with configurable rule sets for dependencies, naming, and layering constraints.
- [LemonAppDev/konsist](https://github.com/LemonAppDev/konsist) - Kotlin architecture linter enforcing coding conventions, project structure, and dependency rules.
- [Fitness Function-Driven Development](https://www.thoughtworks.com/insights/articles/fitness-function-driven-development) - ThoughtWorks article on using automated fitness functions to guide architecture evolution.

## Operational Case Studies (Curated, Short)

- [Spotify System Model](https://engineering.atspotify.com/2022/07/software-visualization-challenge-accepted/) - How Spotify visualizes 2000+ microservices using Backstage and the C4 model.
- [Netflix Microservices Architecture](https://medium.com/netflix-techblog/netflix-oss-and-spring-boot-coming-full-circle-4855947713a0) - How Netflix built and open-sourced their microservice infrastructure with Spring Boot.
- [Uber Domain-Oriented Microservices](https://eng.uber.com/microservice-architecture/) - How Uber evolved from monolith to 4000+ microservices with domain-oriented architecture.
- [Figma Multiplayer Architecture](https://www.figma.com/blog/how-figmas-multiplayer-technology-works/) - How Figma built real-time collaboration with CRDTs and operational transforms.
- [Slack Real-Time Messaging](https://slack.engineering/flannel-an-application-level-edge-cache-to-make-slack-scale/) - How Slack built Flannel, an edge cache handling millions of concurrent WebSocket connections.
- [GitHub Moving to Microservices](https://github.blog/engineering/architecture-optimization/how-we-improved-push-processing-on-github/) - How GitHub re-architected push processing for better reliability and performance.
- [Stripe's Approach to API Design](https://stripe.com/blog/payment-api-design) - How Stripe designs backward-compatible APIs at scale with versioning and careful evolution.
- [Discord Architecture](https://discord.com/blog/how-discord-stores-trillions-of-messages) - How Discord migrated from Cassandra to ScyllaDB to store trillions of messages.
- [Shopify Modular Monolith](https://shopify.engineering/shopify-monolith) - How Shopify deconstructed their monolith into components while staying on a single deployment.
- [Cloudflare Workers Architecture](https://blog.cloudflare.com/how-we-built-pingora-the-proxy-that-connects-cloudflare-to-the-internet/) - How Cloudflare built Pingora, their custom Rust proxy replacing Nginx.

## Books

- [Domain-Driven Design — Eric Evans](https://www.domainlanguage.com/ddd/) - The foundational "Blue Book" defining ubiquitous language, bounded contexts, and strategic design.
- [Implementing Domain-Driven Design — Vaughn Vernon](https://www.goodreads.com/book/show/15756865-implementing-domain-driven-design) - Practical "Red Book" bridging DDD theory to working code with Aggregates and Event Sourcing.
- [Learning Domain-Driven Design — Vlad Khononov](https://www.goodreads.com/book/show/54186674-learning-domain-driven-design) - Modern, accessible DDD introduction connecting strategic and tactical patterns to real projects.
- [Clean Architecture — Robert C. Martin](https://www.goodreads.com/book/show/18043011-clean-architecture) - Principles for structuring software so business rules remain independent of frameworks and databases.
- [Designing Data-Intensive Applications — Martin Kleppmann](https://dataintensive.net/) - Essential deep dive into distributed systems, replication, partitioning, and stream processing.
- [Building Microservices — Sam Newman](https://www.oreilly.com/library/view/building-microservices-2nd/9781492034018/) - Comprehensive guide to microservice decomposition, communication, and deployment strategies.
- [Patterns of Enterprise Application Architecture — Martin Fowler](https://martinfowler.com/books/eaa.html) - Classic catalog of enterprise patterns (Unit of Work, Repository, Data Mapper) still relevant today.
- [Software Architecture: The Hard Parts — Neal Ford et al.](https://www.oreilly.com/library/view/software-architecture-the/9781492086888/) - Decision framework for distributed architecture trade-offs like data ownership and service granularity.
- [A Philosophy of Software Design — John Ousterhout](https://www.goodreads.com/book/show/39996759-a-philosophy-of-software-design) - Concise guide to reducing complexity through deep modules and strategic interface design.
- [Fundamentals of Software Architecture — Richards & Ford](https://www.oreilly.com/library/view/fundamentals-of-software/9781492043447/) - Comprehensive overview of architecture styles, characteristics, and the architect's soft skills.
- [Architecture Patterns with Python — Percival & Gregory](https://www.goodreads.com/book/show/50083115-architecture-patterns-with-python) - Hands-on DDD, event-driven architecture, and TDD patterns applied in Python with working code.
- [Release It! (2nd Edition) — Michael T. Nygard](https://pragprog.com/titles/mnee2/release-it-second-edition/) - Stability patterns (circuit breakers, bulkheads) and anti-patterns for designing production-ready distributed systems.
- [Team Topologies — Matthew Skelton & Manuel Pais](https://teamtopologies.com/book) - Practical application of Conway's Law: team interaction modes, stream-aligned teams, platform teams, and cognitive load.
- [Balancing Coupling in Software Design — Vlad Khononov](https://www.informit.com/store/balancing-coupling-in-software-design-universal-design-9780137353484) - Three-dimensional coupling model (strength, distance, volatility) with practical guidance for controlling dependencies.

## Community

- [Software Architecture Monday](https://www.youtube.com/@markrichards5014) - Mark Richards' weekly YouTube series breaking down architecture concepts in 10-minute episodes.
- [Martin Fowler's Blog](https://martinfowler.com/) - Decades of essential writing on refactoring, microservices, and enterprise architecture patterns.
- [InfoQ — Architecture & Design](https://www.infoq.com/architecture-design/) - Curated articles, conference talks, and trend reports on software architecture.
- [Technology Radar](https://www.thoughtworks.com/radar) - ThoughtWorks' quarterly opinionated guide to emerging tools, techniques, and platforms.
- [DDD Europe](https://dddeurope.com/) - Premier European conference on Domain-Driven Design with workshops and keynotes.
- [QCon](https://qconferences.com/) - International conference featuring practitioner talks on architecture and engineering culture.
- [GOTO Conferences](https://gotopia.tech/) - Conference series with talks from industry leaders on modern software development practices.
- [Software Architecture subreddit](https://www.reddit.com/r/softwarearchitecture/) - Active Reddit community for discussing architecture patterns, trade-offs, and career advice.

---

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
