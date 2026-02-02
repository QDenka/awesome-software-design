# Awesome Software Design [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Turning requirements into well-structured code through patterns, principles, and documented decisions.

## Contents

- [Patterns in Practice](#patterns-in-practice)
- [Domain-Driven Design](#domain-driven-design)
- [Design Patterns](#design-patterns)
- [Architecture Decision Records (ADR)](#architecture-decision-records-adr)
- [System Design](#system-design)
- [Design Documentation](#design-documentation)
- [Design Verification](#design-verification)
- [Real-World Architecture Examples](#real-world-architecture-examples)
- [Books](#books)
- [Community & Conferences](#community--conferences)

---

## Patterns in Practice

- [ThreeDotsLabs/wild-workouts-go-ddd-example](https://github.com/ThreeDotsLabs/wild-workouts-go-ddd-example) - Production-ready Go example combining Clean Architecture, CQRS, and gRPC with detailed blog series.
- [kgrzybek/modular-monolith-with-ddd](https://github.com/kgrzybek/modular-monolith-with-ddd) - Full Modular Monolith with DDD, CQRS, and integration events in C# — 13k+ stars reference project.
- [CodelyTV/php-ddd-example](https://github.com/CodelyTV/php-ddd-example) - PHP DDD skeleton with Hexagonal Architecture, CQRS, and event bus using Symfony.
- [Serverless Patterns Collection](https://serverlessland.com/patterns) - AWS-curated serverless architecture patterns with deployable SAM/CDK templates.
- [Azure Cloud Design Patterns](https://learn.microsoft.com/en-us/azure/architecture/patterns/) - Microsoft's 30+ cloud patterns for availability, data management, and resilience.
- [AWS Cloud Design Patterns](https://docs.aws.amazon.com/prescriptive-guidance/latest/cloud-design-patterns/introduction.html) - Amazon's prescriptive guidance covering decomposition, messaging, and data patterns.
- [Microservices Patterns](https://microservices.io/) - Chris Richardson's comprehensive catalog of microservice patterns including Saga, API Gateway, and CQRS.
- [Cell-Based Architecture](https://github.com/wso2/reference-architecture/blob/master/reference-architecture-cell-based.md) - WSO2's reference architecture for building resilient distributed systems with isolated cells.
- [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer) - 335k+ stars resource covering scalability, caching, load balancing, and architecture trade-offs.

## Domain-Driven Design

- [DDD Reference](https://www.domainlanguage.com/ddd/reference/) - Eric Evans' official DDD pattern language reference — the canonical terminology guide.
- [ddd-crew/ddd-starter-modelling-process](https://github.com/ddd-crew/ddd-starter-modelling-process) - Step-by-step facilitation guide for running DDD modelling sessions in teams.
- [ddd-crew/bounded-context-canvas](https://github.com/ddd-crew/bounded-context-canvas) - Visual tool for designing bounded contexts with inbound/outbound communication flows.
- [ddd-crew/context-mapping](https://github.com/ddd-crew/context-mapping) - Context Mapping patterns (ACL, Open Host, Shared Kernel) with visual diagrams.
- [Vaughn Vernon's IDDD Samples](https://github.com/VaughnVernon/IDDD_Samples) - Companion code for "Implementing Domain-Driven Design" covering Aggregates, Repositories, and Events.
- [EventStorming](https://www.eventstorming.com/) - Alberto Brandolini's collaborative workshop technique for discovering domain events and boundaries.
- [Event Modeling](https://www.eventmodeling.org/) - Visual method for designing event-driven systems with a timeline of commands, events, and views.
- [Miro DDD Bounded Context Canvas](https://miro.com/miroverse/ddd-bounded-context-canvas/) - Ready-to-use Miro template for running bounded context design workshops remotely.
- [ddd-by-examples/library](https://github.com/ddd-by-examples/library) - Comprehensive DDD implementation in Java covering lending domain with Aggregates, Policies, and Events.
- [patchlevel/event-sourcing](https://github.com/patchlevel/event-sourcing) - Modern PHP Event Sourcing library with snapshots, projections, and Doctrine integration.

## Design Patterns

- [Refactoring.Guru](https://refactoring.guru/design-patterns) - Visual catalog of all 23 GoF patterns with UML diagrams and code in 10+ languages.
- [DesignPatternsPHP](https://github.com/DesignPatternsPHP/DesignPatternsPHP) - All known design patterns in PHP 8.1+ with real-world examples, UML diagrams, and tests.
- [kamranahmedse/design-patterns-for-humans](https://github.com/kamranahmedse/design-patterns-for-humans) - 47k+ stars guide explaining design patterns with real-world analogies, not academic jargon.
- [iluwatar/java-design-patterns](https://github.com/iluwatar/java-design-patterns) - 93k+ stars collection of GoF, enterprise, and architectural patterns implemented in Java.
- [tmrts/go-patterns](https://github.com/tmrts/go-patterns) - Idiomatic Go implementations of creational, structural, behavioral, and concurrency patterns.
- [Source Making — Design Patterns](https://sourcemaking.com/design_patterns) - Comprehensive reference with UML diagrams, code examples, and anti-pattern explanations.
- [ThreeDotsLabs/watermill](https://github.com/ThreeDotsLabs/watermill) - Go library for building event-driven applications with Pub/Sub, CQRS, and middleware support.

## Architecture Decision Records (ADR)

- [joelparkerhenderson/architecture-decision-record](https://github.com/joelparkerhenderson/architecture-decision-record) - 15k+ stars collection of ADR templates, examples, and best practices from real projects.
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

## System Design

- [ByteByteGo](https://bytebytego.com/) - Alex Xu's system design course with visual deep dives into distributed systems internals.
- [karanpratapsingh/system-design](https://github.com/karanpratapsingh/system-design) - Free system design course covering networking, databases, caching, and real-world case studies.
- [High Scalability](https://highscalability.com/) - Real architecture case studies from Netflix, Twitter, and other high-traffic systems.
- [API Design Guide by Google](https://cloud.google.com/apis/design) - Google's resource-oriented API design standard used across all Google Cloud APIs.
- [Microsoft REST API Guidelines](https://github.com/microsoft/api-guidelines) - Microsoft's battle-tested guidelines for consistent, developer-friendly RESTful APIs.
- [Use The Index, Luke](https://use-the-index-luke.com/) - In-depth SQL indexing guide teaching developers how databases execute queries efficiently.
- [RabbitMQ Tutorials](https://www.rabbitmq.com/tutorials) - Official tutorials covering work queues, pub/sub, routing, and RPC messaging patterns.
- [Apache Kafka Documentation](https://kafka.apache.org/documentation/) - Complete reference for Kafka's distributed streaming platform, partitioning, and consumer groups.
- [Rate Limiting Strategies](https://cloud.google.com/architecture/rate-limiting-strategies-techniques) - Google Cloud guide covering token bucket, leaky bucket, and sliding window algorithms.
- [DDIA Notes](https://github.com/keyvanakbary/learning-notes/blob/master/books/designing-data-intensive-applications.md) - Detailed community notes on Kleppmann's DDIA covering replication, partitioning, and consensus.

## Design Documentation

- [C4 Model](https://c4model.com/) - Simon Brown's four-level model (Context, Container, Component, Code) for architecture visualization.
- [D2 Language](https://d2lang.com/) - Modern declarative diagramming language with auto-layout that compiles to SVG and PNG.
- [Mermaid](https://github.com/mermaid-js/mermaid) - 85k+ stars JavaScript diagramming tool rendering flowcharts, sequence diagrams from Markdown syntax.
- [Diagrams as Code](https://github.com/mingrammer/diagrams) - Draw AWS, Azure, GCP, and Kubernetes architecture diagrams in Python with provider icons.
- [dependency-cruiser](https://github.com/sverweij/dependency-cruiser) - Validate and visualize JavaScript/TypeScript module dependencies against architecture rules.
- [Ilograph](https://www.ilograph.com/) - Interactive architecture diagrams with multi-perspective views and drill-down navigation.
- [Terrastruct](https://terrastruct.com/) - Commercial platform for creating interactive architecture diagrams powered by D2.

## Design Verification

- [phparkitect/arkitect](https://github.com/phparkitect/arkitect) - Define PHP architecture rules with expressive DSL — enforce layer dependencies in CI.
- [carlosas/phpat](https://github.com/carlosas/phpat) - PHP Architecture Tester running as PHPStan extension — assert dependency rules in your test suite.
- [pestphp/pest-plugin-arch](https://github.com/pestphp/pest-plugin-arch) - Fluent architecture testing for Laravel/Pest — `expect()->toUseNothing()` style assertions.
- [TNG/ArchUnit](https://github.com/TNG/ArchUnit) - Industry-standard Java library for checking architecture constraints as unit tests.
- [TNG/ArchUnitNET](https://github.com/TNG/ArchUnitNET) - .NET port of ArchUnit for enforcing architecture rules in C# projects.
- [fdaines/arch-go](https://github.com/fdaines/arch-go) - Architecture testing for Go — validate package dependencies, naming, and function rules.
- [LemonAppDev/konsist](https://github.com/LemonAppDev/konsist) - Kotlin architecture linter enforcing coding conventions, project structure, and dependency rules.
- [Fitness Function-Driven Development](https://www.thoughtworks.com/insights/articles/fitness-function-driven-development) - ThoughtWorks article on using automated fitness functions to guide architecture evolution.
- [PHPStan](https://phpstan.org/) - PHP static analysis finding bugs at level 0–9 without running code — 13k+ stars.
- [Psalm](https://psalm.dev/) - PHP static analysis focused on type safety with template types and taint analysis.

## Real-World Architecture Examples

- [Spotify System Model](https://engineering.atspotify.com/2022/07/software-visualization-challenge-accepted/) - How Spotify visualizes 2000+ microservices using Backstage and the C4 model.
- [Netflix Tech Blog](https://netflixtechblog.com/) - Deep dives into distributed systems powering 200M+ subscribers — chaos engineering, data pipelines, and resilience.
- [Uber Domain-Oriented Microservices](https://www.uber.com/en-US/blog/microservice-architecture/) - How Uber evolved from monolith to 4000+ microservices with domain-oriented architecture.
- [Figma Multiplayer Architecture](https://www.figma.com/blog/how-figmas-multiplayer-technology-works/) - How Figma built real-time collaboration with CRDTs and operational transforms.
- [Slack Architecture](https://slack.engineering/) - Engineering blog covering message storage, search infrastructure, and real-time event delivery.
- [GitHub Architecture](https://github.blog/engineering/) - Behind-the-scenes of GitHub's infrastructure, deployment, and reliability engineering.
- [Stripe's Approach to API Design](https://stripe.com/blog/payment-api-design) - How Stripe designs backward-compatible APIs at scale with versioning and careful evolution.
- [Discord Architecture](https://discord.com/blog/how-discord-stores-trillions-of-messages) - How Discord migrated from Cassandra to ScyllaDB to store trillions of messages.
- [Shopify Modular Monolith](https://shopify.engineering/shopify-monolith) - How Shopify deconstructed their monolith into components while staying on a single deployment.
- [Cloudflare Engineering Blog](https://blog.cloudflare.com/tag/engineering/) - Deep technical posts on edge computing, DNS, and global network architecture.

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

## Community & Conferences

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
