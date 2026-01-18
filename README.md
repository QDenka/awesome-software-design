# Awesome Software Design [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources on software design, architecture patterns, ADR, system design, and practical examples for backend development.

## Contents

- [Architecture Patterns](#architecture-patterns)
- [Architecture Decision Records (ADR)](#architecture-decision-records-adr)
- [Design Patterns](#design-patterns)
- [System Design](#system-design)
- [Architecture Documentation](#architecture-documentation)
- [Architecture Testing & Fitness Functions](#architecture-testing--fitness-functions)
- [Domain-Driven Design](#domain-driven-design)
- [Books](#books)
- [Community & Conferences](#community--conferences)

---

## Architecture Patterns

- [The Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html) - Robert C. Martin's original post on Clean Architecture with dependency rule.
- [Hexagonal Architecture](https://alistair.cockburn.us/hexagonal-architecture/) - Alistair Cockburn's definition of the Ports and Adapters pattern.
- [Onion Architecture](https://jeffreypalermo.com/2008/07/the-onion-architecture-part-1/) - Jeffrey Palermo's layered architecture with domain at the core.
- [CQRS](https://martinfowler.com/bliki/CQRS.html) - Martin Fowler's explanation of Command Query Responsibility Segregation.
- [Event Sourcing](https://martinfowler.com/eaaDev/EventSourcing.html) - Storing state as a sequence of domain events instead of current state.
- [Modular Monolith](https://www.kamilgrzybek.com/blog/posts/modular-monolith-primer) - Kamil Grzybek's primer on building modular monolith systems.
- [Microservices Patterns](https://microservices.io/) - Chris Richardson's catalog of microservice architecture patterns.
- [Serverless Patterns Collection](https://serverlessland.com/patterns) - AWS curated collection of serverless architecture patterns.
- [Azure Cloud Design Patterns](https://learn.microsoft.com/en-us/azure/architecture/patterns/) - Microsoft's cloud design patterns for scalable and reliable applications.
- [AWS Cloud Design Patterns](https://docs.aws.amazon.com/prescriptive-guidance/latest/cloud-design-patterns/introduction.html) - Amazon's prescriptive guidance on cloud architecture patterns.
- [Cell-Based Architecture](https://github.com/wso2/reference-architecture/blob/master/reference-architecture-cell-based.md) - WSO2's reference architecture for cell-based distributed systems.
- [hgraca/explicit-architecture-php](https://github.com/hgraca/explicit-architecture-php) - Explicit Architecture (Ports & Adapters + Clean Arch) demo in PHP.
- [ThreeDotsLabs/wild-workouts-go-ddd-example](https://github.com/ThreeDotsLabs/wild-workouts-go-ddd-example) - Go DDD example with Clean Architecture, CQRS, and gRPC.
- [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer) - Large-scale system design with architecture patterns overview.
- [jorge07/ddd-playground](https://github.com/jorge07/ddd-playground) - Symfony DDD playground with CQRS and Event Sourcing.

## Architecture Decision Records (ADR)

- [joelparkerhenderson/architecture-decision-record](https://github.com/joelparkerhenderson/architecture-decision-record) - Comprehensive collection of ADR templates and real-world examples.
- [npryce/adr-tools](https://github.com/npryce/adr-tools) - Command-line tools for managing Architecture Decision Records.
- [adr/madr](https://github.com/adr/madr) - Markdown Any Decision Records — lightweight ADR template format.
- [Documenting Architecture Decisions](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions) - Michael Nygard's original blog post that started the ADR movement.
- [adr.github.io](https://adr.github.io/) - Central hub of the ADR GitHub organization with tools and resources.
- [log4brains](https://github.com/thomvaill/log4brains) - Docs-as-code knowledge base for ADRs with auto-generated web UI.
- [adr/e-adr](https://github.com/adr/e-adr) - Embedded Architectural Decision Records for embedding ADRs in code.
- [Kubernetes KEPs](https://github.com/kubernetes/enhancements/tree/master/keps) - Kubernetes Enhancement Proposals — real-world ADR examples at scale.
- [Spotify ADR Practice](https://engineering.atspotify.com/2020/04/when-should-i-write-an-architecture-decision-record/) - Spotify engineering on when and how to write ADRs.
- [GOV.UK RFCs](https://github.com/alphagov/govuk-rfcs) - UK Government Digital Service architecture decision records.

## Design Patterns

- [Refactoring.Guru](https://refactoring.guru/design-patterns) - Visual catalog of all GoF design patterns with code in 10+ languages.
- [DesignPatternsPHP](https://github.com/DesignPatternsPHP/DesignPatternsPHP) - All known design patterns implemented in PHP with real-world examples.
- [kamranahmedse/design-patterns-for-humans](https://github.com/kamranahmedse/design-patterns-for-humans) - Design patterns explained in plain English with real-world analogies.
- [tmrts/go-patterns](https://github.com/tmrts/go-patterns) - Curated list of Go design patterns, recipes, and idioms.
- [luk4z7/go-concurrency-guide](https://github.com/luk4z7/go-concurrency-guide) - Practical guide to Go concurrency patterns with examples.
- [iluwatar/java-design-patterns](https://github.com/iluwatar/java-design-patterns) - Extensive collection of design patterns implemented in Java.
- [Source Making — Design Patterns](https://sourcemaking.com/design_patterns) - Comprehensive reference with UML diagrams and code examples.
- [Tactical DDD Patterns](https://vaadin.com/blog/ddd-part-3-domain-driven-design-and-the-hexagonal-architecture) - Combining DDD tactical patterns with Hexagonal Architecture.
- [ThreeDotsLabs/watermill](https://github.com/ThreeDotsLabs/watermill) - Go library for event-driven apps using Pub/Sub, CQRS, and Event Sourcing.

## System Design

- [ByteByteGo](https://bytebytego.com/) - Alex Xu's system design course with visual explanations of distributed systems.
- [karanpratapsingh/system-design](https://github.com/karanpratapsingh/system-design) - Learn system design fundamentals with illustrated explanations.
- [High Scalability](https://highscalability.com/) - Real-world architecture case studies from top tech companies.
- [API Design Guide by Google](https://cloud.google.com/apis/design) - Google's resource-oriented API design guidelines.
- [Microsoft REST API Guidelines](https://github.com/microsoft/api-guidelines) - Microsoft's recommendations for designing RESTful APIs.
- [Use The Index, Luke](https://use-the-index-luke.com/) - SQL indexing and performance tuning guide for developers.
- [Redis Best Practices](https://redis.io/docs/latest/develop/get-started/) - Official Redis documentation for caching strategies and data structures.
- [RabbitMQ Tutorials](https://www.rabbitmq.com/tutorials) - Official tutorials covering messaging patterns and queue topologies.
- [Apache Kafka Documentation](https://kafka.apache.org/documentation/) - Complete documentation for Kafka distributed streaming platform.
- [Rate Limiting Strategies](https://cloud.google.com/architecture/rate-limiting-strategies-techniques) - Google Cloud guide to rate limiting algorithms and techniques.
- [DDIA Notes](https://github.com/keyvanakbary/learning-notes/blob/master/books/designing-data-intensive-applications.md) - Community notes on Martin Kleppmann's Designing Data-Intensive Applications.

## Architecture Documentation

- [C4 Model](https://c4model.com/) - Simon Brown's four-level model for visualizing software architecture.
- [Structurizr](https://structurizr.com/) - Architecture models as code using the C4 model approach.
- [Structurizr DSL](https://github.com/structurizr/dsl) - Text-based DSL for defining C4 model architecture diagrams.
- [D2 Language](https://d2lang.com/) - Modern declarative diagramming language that compiles to SVG.
- [Terrastruct](https://terrastruct.com/) - Platform for creating and maintaining architecture diagrams with D2.
- [Mermaid](https://github.com/mermaid-js/mermaid) - JavaScript-based diagramming tool rendered from Markdown-like syntax.
- [PlantUML](https://plantuml.com/) - Open-source tool to generate UML diagrams from plain text descriptions.
- [arc42](https://arc42.org/) - Pragmatic template for documenting software and system architecture.
- [Diagrams as Code](https://github.com/mingrammer/diagrams) - Draw cloud architecture diagrams in Python with provider icons.
- [dependency-cruiser](https://github.com/sverweij/dependency-cruiser) - Validate and visualize JS/TS module dependencies against architecture rules.
- [Ilograph](https://www.ilograph.com/) - Interactive architecture diagrams with multi-perspective views.

## Architecture Testing & Fitness Functions

- [qossmic/deptrac](https://github.com/qossmic/deptrac) - PHP static analysis to enforce architectural layer boundaries.
- [phparkitect/arkitect](https://github.com/phparkitect/arkitect) - Define and test PHP architecture rules with expressive DSL.
- [carlosas/phpat](https://github.com/carlosas/phpat) - PHP Architecture Tester — assert architectural rules in PHPUnit.
- [pestphp/pest-plugin-arch](https://github.com/pestphp/pest-plugin-arch) - Laravel Pest plugin for expressive architecture testing.
- [TNG/ArchUnit](https://github.com/TNG/ArchUnit) - Java library to check architecture constraints as unit tests.
- [TNG/ArchUnitNET](https://github.com/TNG/ArchUnitNET) - .NET port of ArchUnit for testing architecture rules in C#.
- [fdaines/arch-go](https://github.com/fdaines/arch-go) - Architecture testing tool for Go projects.
- [Fitness Function-Driven Development](https://www.thoughtworks.com/insights/articles/fitness-function-driven-development) - ThoughtWorks on using fitness functions to guide architecture evolution.
- [PHPStan](https://phpstan.org/) - PHP static analysis tool for finding bugs without running code.
- [Psalm](https://psalm.dev/) - PHP static analysis focused on type safety and bug prevention.

## Domain-Driven Design

- [DDD Reference](https://www.domainlanguage.com/ddd/reference/) - Eric Evans' official DDD pattern language reference.
- [ddd-crew/ddd-starter-modelling-process](https://github.com/ddd-crew/ddd-starter-modelling-process) - Step-by-step guide to start DDD modelling in a team.
- [ddd-crew/bounded-context-canvas](https://github.com/ddd-crew/bounded-context-canvas) - Collaborative tool for designing and documenting bounded contexts.
- [ddd-crew/context-mapping](https://github.com/ddd-crew/context-mapping) - Context Mapping patterns with visual examples.
- [Vaughn Vernon's IDDD Samples](https://github.com/VaughnVernon/IDDD_Samples) - Sample code from Implementing Domain-Driven Design in Java.
- [EventStorming](https://www.eventstorming.com/) - Alberto Brandolini's collaborative domain discovery technique.
- [Event Modeling](https://www.eventmodeling.org/) - Visual method for designing event-driven information systems.
- [Miro DDD Bounded Context Canvas](https://miro.com/miroverse/ddd-bounded-context-canvas/) - Ready-to-use Miro template for DDD bounded context workshops.
- [ddd-by-examples/library](https://github.com/ddd-by-examples/library) - Comprehensive DDD example in Java — library lending domain.
- [kgrzybek/modular-monolith-with-ddd](https://github.com/kgrzybek/modular-monolith-with-ddd) - Full Modular Monolith with DDD implementation in C#.
- [CodelyTV/php-ddd-example](https://github.com/CodelyTV/php-ddd-example) - PHP DDD example with Hexagonal Architecture and CQRS.
- [patchlevel/event-sourcing](https://github.com/patchlevel/event-sourcing) - PHP Event Sourcing library designed with DDD principles.

## Books

- [Domain-Driven Design — Eric Evans](https://www.domainlanguage.com/ddd/) - The foundational "Blue Book" on Domain-Driven Design.
- [Implementing Domain-Driven Design — Vaughn Vernon](https://www.goodreads.com/book/show/15756865-implementing-domain-driven-design) - Practical guide to applying DDD in real projects.
- [Learning Domain-Driven Design — Vlad Khononov](https://www.goodreads.com/book/show/54186674-learning-domain-driven-design) - Modern, accessible introduction to DDD with practical examples.
- [Clean Architecture — Robert C. Martin](https://www.goodreads.com/book/show/18043011-clean-architecture) - Guide to software structure and design principles.
- [Designing Data-Intensive Applications — Martin Kleppmann](https://dataintensive.net/) - Essential book on distributed systems, storage, and data processing.
- [Building Microservices — Sam Newman](https://www.oreilly.com/library/view/building-microservices-2nd/9781492034018/) - Designing fine-grained distributed systems with microservices.
- [Patterns of Enterprise Application Architecture — Martin Fowler](https://martinfowler.com/books/eaa.html) - Classic catalog of enterprise architecture patterns.
- [Software Architecture: The Hard Parts — Neal Ford et al.](https://www.oreilly.com/library/view/software-architecture-the/9781492086888/) - Trade-off analysis for distributed architectures.
- [A Philosophy of Software Design — John Ousterhout](https://www.goodreads.com/book/show/39996759-a-philosophy-of-software-design) - Principles for decomposing complex software into simple modules.
- [Fundamentals of Software Architecture — Richards & Ford](https://www.oreilly.com/library/view/fundamentals-of-software/9781492043447/) - Comprehensive guide to architecture styles and characteristics.
- [Architecture Patterns with Python — Percival & Gregory](https://www.goodreads.com/book/show/50083115-architecture-patterns-with-python) - DDD, event-driven, and TDD patterns applied in Python.

## Community & Conferences

- [Software Architecture Monday](https://www.youtube.com/@markrichards5014) - Mark Richards' weekly YouTube series on architecture topics.
- [Martin Fowler's Blog](https://martinfowler.com/) - Essential writing on software design, refactoring, and architecture.
- [Developer Way](https://www.developerway.com/) - In-depth articles on React architecture, patterns, and performance.
- [InfoQ — Architecture & Design](https://www.infoq.com/architecture-design/) - Articles, talks, and news on software architecture trends.
- [Technology Radar](https://www.thoughtworks.com/radar) - ThoughtWorks' opinionated guide to technology trends and adoption.
- [DDD Europe](https://dddeurope.com/) - Premier European conference on Domain-Driven Design.
- [QCon](https://qconferences.com/) - International conference on software development and architecture.
- [GOTO Conferences](https://gotopia.tech/) - Conference series covering modern software development practices.
- [Software Architecture subreddit](https://www.reddit.com/r/softwarearchitecture/) - Reddit community for discussing software architecture.

---

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
