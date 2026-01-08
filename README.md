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

- [The Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html) - Robert C. Martin's original post on Clean Architecture.
- [Hexagonal Architecture](https://alistair.cockburn.us/hexagonal-architecture/) - Alistair Cockburn's definition of Ports and Adapters pattern.
- [Onion Architecture](https://jeffreypalermo.com/2008/07/the-onion-architecture-part-1/) - Jeffrey Palermo's introduction to the Onion Architecture.
- [CQRS](https://martinfowler.com/bliki/CQRS.html) - Martin Fowler's explanation of Command Query Responsibility Segregation.
- [Event Sourcing](https://martinfowler.com/eaaDev/EventSourcing.html) - Martin Fowler's article on Event Sourcing pattern.
- [Modular Monolith](https://www.kamilgrzybek.com/blog/posts/modular-monolith-primer) - Kamil Grzybek's primer on Modular Monolith architecture.
- [Microservices](https://microservices.io/) - Chris Richardson's patterns and best practices for microservices.
- [ecotone-dev/ecotone](https://github.com/ecotone-dev/ecotone-dev) - PHP framework supporting CQRS, Event Sourcing, and Modular Monolith.
- [jorge07/symfony-6-es-cqrs](https://github.com/jorge07/symfony-6-es-cqrs) - Symfony 6 boilerplate with CQRS and Event Sourcing implementation.
- [ThreeDotsLabs/wild-workouts-go-ddd-example](https://github.com/ThreeDotsLabs/wild-workouts-go-ddd-example) - Go DDD example with Clean Architecture and CQRS.
- [herbertograca/php-medieval-game](https://github.com/hgraca/explicit-architecture-php) - Explicit Architecture (Ports & Adapters + Clean Arch) in PHP.
- [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer) - Learn how to design large-scale systems with architecture patterns overview.

## Architecture Decision Records (ADR)

- [joelparkerhenderson/architecture-decision-record](https://github.com/joelparkerhenderson/architecture-decision-record) - Comprehensive collection of ADR templates and examples.
- [npryce/adr-tools](https://github.com/npryce/adr-tools) - Command-line tools for working with Architecture Decision Records.
- [adr/madr](https://github.com/adr/madr) - Markdown Any Decision Records — lean ADR template.
- [Documenting Architecture Decisions](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions) - Michael Nygard's original blog post that popularized ADRs.
- [adr/adr.github.io](https://adr.github.io/) - Homepage of the ADR GitHub organization with tooling overview.
- [log4brains](https://github.com/thomvaill/log4brains) - Docs-as-code knowledge base for ADRs with web UI.
- [mrk21/adr-viewer](https://github.com/mrk21/adr-viewer) - Generate a website from your Architecture Decision Records.

## Design Patterns

- [Refactoring.Guru](https://refactoring.guru/design-patterns) - Visual catalog of all GoF design patterns with code examples.
- [DesignPatternsPHP](https://github.com/DesignPatternsPHP/DesignPatternsPHP) - Collection of known design patterns implemented in PHP.
- [tmrts/go-patterns](https://github.com/tmrts/go-patterns) - Curated list of Go design patterns, recipes, and idioms.
- [domnikl/algorithms-and-design-patterns](https://github.com/domnikl/DesignPatternsPHP) - Another take on GoF patterns in PHP with real-world examples.
- [iluwatar/java-design-patterns](https://github.com/iluwatar/java-design-patterns) - Extensive collection of design patterns implemented in Java.
- [Tactical DDD Patterns](https://vaadin.com/blog/ddd-part-3-domain-driven-design-and-the-hexagonal-architecture) - Combining DDD tactical patterns with Hexagonal Architecture.
- [Source Making — Design Patterns](https://sourcemaking.com/design_patterns) - Comprehensive reference for design patterns with UML and examples.
- [phalcon/patterns](https://github.com/kamranahmedse/design-patterns-for-humans) - Design patterns explained in plain English with real-world examples.
- [marcel-dempers/go-microservice-pattern](https://github.com/ThreeDotsLabs/watermill) - Go library for building event-driven apps using Pub/Sub, CQRS, and Event Sourcing patterns.

## System Design

- [System Design Primer](https://github.com/donnemartin/system-design-primer) - Comprehensive resource for learning system design with real examples.
- [ByteByteGo](https://bytebytego.com/) - Alex Xu's system design course with visual explanations.
- [API Design Guide by Google](https://cloud.google.com/apis/design) - Google's API design guidelines for resource-oriented APIs.
- [Microsoft REST API Guidelines](https://github.com/microsoft/api-guidelines) - Microsoft's recommendations for designing RESTful APIs.
- [Use The Index, Luke](https://use-the-index-luke.com/) - A guide to database indexing and SQL performance for developers.
- [Redis Best Practices](https://redis.io/docs/latest/develop/get-started/) - Official Redis documentation for caching strategies and patterns.
- [RabbitMQ Tutorials](https://www.rabbitmq.com/tutorials) - Official tutorials covering message queue patterns and use cases.
- [Apache Kafka Documentation](https://kafka.apache.org/documentation/) - Complete documentation for Apache Kafka distributed streaming platform.
- [Rate Limiting Strategies](https://cloud.google.com/architecture/rate-limiting-strategies-techniques) - Google Cloud guide to rate limiting techniques.
- [karanpratapsingh/system-design](https://github.com/karanpratapsingh/system-design) - Learn system design with illustrated explanations.
- [Designing Data-Intensive Applications (notes)](https://github.com/keyvanakbary/learning-notes/blob/master/books/designing-data-intensive-applications.md) - Community notes on Martin Kleppmann's DDIA book.

## Architecture Documentation

- [C4 Model](https://c4model.com/) - Simon Brown's C4 model for visualizing software architecture.
- [Structurizr](https://structurizr.com/) - Architecture models as code using the C4 model.
- [Structurizr DSL](https://github.com/structurizr/dsl) - A text-based DSL for the Structurizr C4 model.
- [Mermaid](https://github.com/mermaid-js/mermaid) - JavaScript-based diagramming and charting tool rendered from Markdown.
- [PlantUML](https://plantuml.com/) - Open-source tool to draw UML diagrams from plain text.
- [arc42](https://arc42.org/) - Template for architecture documentation, pragmatic and practical.
- [Diagrams as Code (Mingrammer)](https://github.com/mingrammer/diagrams) - Draw cloud system architecture diagrams in Python code.
- [Ilograph](https://www.ilograph.com/) - Interactive architecture diagrams with multi-perspective views.

## Architecture Testing & Fitness Functions

- [qossmic/deptrac](https://github.com/qossmic/deptrac) - PHP static analysis tool to enforce architectural boundaries between layers.
- [phparkitect/arkitect](https://github.com/phparkitect/arkitect) - Define and test architecture rules in PHP with expressive DSL.
- [TNG/ArchUnit](https://github.com/TNG/ArchUnitNET) - .NET library for checking architecture rules in unit tests.
- [TNG/ArchUnit (Java)](https://github.com/TNG/ArchUnit) - Java library to test architecture rules as unit tests.
- [Building Evolutionary Architectures](https://www.thoughtworks.com/insights/articles/fitness-function-driven-development) - ThoughtWorks article on fitness function-driven development.
- [ta-tyshchenko/phpat](https://github.com/carlosas/phpat) - PHP Architecture Tester — easy-to-use architecture testing tool.
- [PHPStan](https://phpstan.org/) - Static analysis tool for PHP that catches bugs and enforces code quality.
- [Psalm](https://psalm.dev/) - PHP static analysis tool focused on type-related bugs.

## Domain-Driven Design

- [Domain-Driven Design Reference](https://www.domainlanguage.com/ddd/reference/) - Eric Evans' DDD reference definitions.
- [ddd-crew/ddd-starter-modelling-process](https://github.com/ddd-crew/ddd-starter-modelling-process) - Step-by-step guide to DDD modelling.
- [ddd-crew/bounded-context-canvas](https://github.com/ddd-crew/bounded-context-canvas) - A collaborative tool for designing bounded contexts.
- [ddd-crew/context-mapping](https://github.com/ddd-crew/context-mapping) - Context Mapping patterns and examples.
- [Vaughn Vernon's IDDD Samples](https://github.com/VaughnVernon/IDDD_Samples) - Implementing Domain-Driven Design sample code in Java.
- [EventStorming](https://www.eventstorming.com/) - Alberto Brandolini's collaborative modeling technique.
- [ddd-by-examples/library](https://github.com/ddd-by-examples/library) - A comprehensive DDD example in Java — library lending system.
- [jorge07/modular-monolith-ddd](https://github.com/kgrzybek/modular-monolith-with-ddd) - Full Modular Monolith with DDD in C# by Kamil Grzybek.
- [codelytv/php-ddd-example](https://github.com/CodelyTV/php-ddd-example) - PHP DDD example with Hexagonal Architecture.
- [patchlevel/event-sourcing](https://github.com/patchlevel/event-sourcing) - PHP Event Sourcing library with DDD in mind.

## Books

- [Domain-Driven Design by Eric Evans](https://www.domainlanguage.com/ddd/) - The foundational book on Domain-Driven Design.
- [Clean Architecture by Robert C. Martin](https://www.goodreads.com/book/show/18043011-clean-architecture) - A guide to software structure and design principles.
- [Designing Data-Intensive Applications by Martin Kleppmann](https://dataintensive.net/) - Essential book on distributed systems and data architecture.
- [Building Microservices by Sam Newman](https://www.oreilly.com/library/view/building-microservices-2nd/9781492034018/) - Designing fine-grained systems with microservices.
- [Patterns of Enterprise Application Architecture by Martin Fowler](https://martinfowler.com/books/eaa.html) - Classic reference for enterprise architecture patterns.
- [Implementing Domain-Driven Design by Vaughn Vernon](https://www.goodreads.com/book/show/15756865-implementing-domain-driven-design) - Practical guide to implementing DDD.
- [Software Architecture: The Hard Parts by Neal Ford et al.](https://www.oreilly.com/library/view/software-architecture-the/9781492086888/) - Modern trade-off analysis for distributed architectures.
- [A Philosophy of Software Design by John Ousterhout](https://www.goodreads.com/book/show/39996759-a-philosophy-of-software-design) - How to decompose complex software into manageable modules.
- [Fundamentals of Software Architecture by Mark Richards & Neal Ford](https://www.oreilly.com/library/view/fundamentals-of-software/9781492043447/) - Comprehensive guide to architecture styles and characteristics.

## Community & Conferences

- [Software Architecture subreddit](https://www.reddit.com/r/softwarearchitecture/) - Reddit community discussing software architecture topics.
- [DDD Europe](https://dddeurope.com/) - Premier European conference on Domain-Driven Design.
- [QCon](https://qconferences.com/) - International software development conference covering architecture.
- [GOTO Conferences](https://gotopia.tech/) - Conference series focused on software development and architecture.
- [O'Reilly Software Architecture Conference](https://www.oreilly.com/conferences/) - O'Reilly's conference on software architecture practices.
- [InfoQ — Architecture & Design](https://www.infoq.com/architecture-design/) - Articles, presentations, and news on software architecture.
- [Martin Fowler's Blog](https://martinfowler.com/) - Essential blog on software design and architecture patterns.
- [The Software Architecture Guild](https://www.youracclaim.com/) - Resources and community for software architects.
- [Technology Radar by ThoughtWorks](https://www.thoughtworks.com/radar) - Opinionated guide to technology trends in software development.

---

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author has waived all copyright and related or neighboring rights to this work.
