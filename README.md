# Seanie Stack

**Final Year BSc Computer Systems student - backend and systems engineering**

Listowel, Co. Kerry | [seaniestack345@gmail.com](mailto:seaniestack345@gmail.com) | +353 87 453 8221 | [LinkedIn](https://linkedin.com/in/seanie-stack) | [GitHub](https://github.com/seanieStack)

A PDF version of this CV is available in [`SeanieStackCV.pdf`](SeanieStackCV.pdf).

---

## Professional Summary

Final Year BSc Computer Systems student focused on backend and systems engineering, with 8 months of professional experience building production Java / Spring Boot services, including a performance fix that cut API response times by **91%**. Comfortable across Java, Python, C, Rust and Go with a Linux and Docker toolchain. Eligible to work in Ireland and the UK.

---

## Education

**University of Limerick**, Sept 2022 - Jan 2027
BSc Computer Systems | 3.11 QCA | Second Class Honours, Grade 1 (2.1)

---

## Professional Experience

### Ostia Solutions, Bray, Co. Wicklow

**Software Development Intern**, May 2024 - Jan 2025

- Worked across test development and performance testing during an 8-month placement, contributing to the quality and reliability of production Spring Boot Java services.
- Designed and implemented automated test suites using JUnit, JMeter and Postman, increasing test coverage and catching bugs earlier in the release cycle.
- Identified and fixed a cache misconfiguration across all major API endpoints, reducing average response time by **91%** and improving throughput under load.
- Investigated and reported performance bottlenecks using load testing and profiling, while working alongside senior developers to ship fixes.
- Operated in an agile team environment using git for version control and standard CI workflows for build, test and deployment.

---

## Projects

### RJScript, Final Year Project (2025 - 2026)

`Java`, `ANTLR4` | [Repository](https://github.com/seanieStack/RJScript-FYP)

- Designed and implemented a dynamically-typed scripting language from scratch in Java (~12,000 lines of code), including lexer, parser, AST, and tree-walk interpreter built on ANTLR4.
- Implemented core language features including variables, arithmetic and logical operators with short-circuit evaluation, functions with closures, lexical scoping, strings, floats, arrays with negative indexing, and modulo.
- Built a two-tier standard library and module system, plus a Java embedding API (`RJScriptEngine`) allowing host applications to execute RJScript code and exchange values with the JVM.
- Added source-location-aware error reporting and configurable debug flags to improve the developer experience when writing and debugging RJScript programs.

### E-Library Microservice Backend (2026)

`Java`, `Spring Boot`, `RabbitMQ`, `Docker` | [Repository](https://github.com/seanieStack/SoftwareArchitectureProject)

- Built a microservices-based e-library application split into a core service (catalogue, loans, users) and a support service (fines, notifications), communicating asynchronously via RabbitMQ.
- Used RabbitMQ message queues to decouple fine processing and user notifications from the main request path, improving responsiveness and resilience to downstream failures.
- Containerised all services with Docker and orchestrated local deployment with Docker Compose, including dependency services such as the message broker and database.

---

## Technical Skills

| Category | |
| --- | --- |
| **Languages** | Java, Python, C, Rust (basic), Go (basic) |
| **Frameworks and Libraries** | Spring Boot, ANTLR4, JUnit, Mockito, JMeter |
| **Tools and Platforms** | Git, Docker, Docker Compose, Maven, Gradle, RabbitMQ, Linux (Arch) |
| **Databases** | MySQL, Redis, PostgreSQL |
| **Concepts** | Compilers and interpreters, language design, backend systems, microservices, performance testing, automated testing, message queues, REST APIs |
