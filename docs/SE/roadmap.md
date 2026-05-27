# 💻 SE — Learning Roadmap

> Ordered path from fundamentals to system design mastery.

---

## 1️⃣ Fundamentals

- [ ] HTTP/HTTPS, DNS, Domain, how the web works
- [ ] OS basics: processes, threads, memory, I/O
- [ ] Data structures & algorithms (for interviews)

## 2️⃣ Java Core

- [ ] Collections framework: List, Set, Map internals (HashMap, ConcurrentHashMap)
- [ ] Concurrency: Thread, ExecutorService, CompletableFuture, synchronized, volatile
- [ ] JVM: memory model, garbage collection, class loading
- [ ] Streams API, Optional, functional interfaces
- [ ] Generics, reflection, annotations

## 3️⃣ Spring / Spring Boot

- [ ] IoC container, dependency injection, Bean lifecycle
- [ ] Spring MVC: request handling, filters, interceptors
- [ ] Spring Security: authentication, authorization, filter chain
- [ ] Spring Data JPA: repositories, query methods, specifications
- [ ] Spring Boot auto-configuration, profiles, externalized config
- [ ] AOP: cross-cutting concerns, logging, transaction management

## 4️⃣ APIs

- [ ] REST: design principles, status codes, HATEOAS, versioning
- [ ] GraphQL: schema, resolvers, N+1 problem
- [ ] gRPC: protobuf, streaming, service definition
- [ ] WebSocket: real-time communication
- [ ] Authentication: JWT, OAuth2, OpenID Connect, session-based
- [ ] Security: OWASP Top 10, CORS, CSP, rate limiting

## 5️⃣ Databases

- [ ] Relational: MySQL, PostgreSQL — indexing, query plans, normalization
- [ ] Transactions: ACID, isolation levels, deadlocks
- [ ] ORM: JPA/Hibernate, N+1 problem, lazy vs eager loading, caching (L1/L2)
- [ ] NoSQL: Redis (caching, pub/sub), MongoDB (document model)
- [ ] Database migration: Flyway, Liquibase

## 6️⃣ Design Patterns & Principles

- [ ] SOLID principles with Java examples
- [ ] Creational: Singleton, Factory, Builder
- [ ] Structural: Adapter, Decorator, Proxy
- [ ] Behavioral: Strategy, Observer, Template Method
- [ ] Clean Code practices, refactoring techniques

## 7️⃣ Microservices

- [ ] Service decomposition: bounded contexts, single responsibility
- [ ] Communication: REST, gRPC, async messaging
- [ ] API Gateway: routing, rate limiting, authentication
- [ ] Service discovery and load balancing
- [ ] Kafka: topics, partitions, consumer groups, exactly-once
- [ ] Patterns: Circuit Breaker, Retry, Saga, Outbox
- [ ] Distributed tracing, centralized logging

## 8️⃣ Testing

- [ ] Unit testing: JUnit 5, Mockito, test doubles
- [ ] Integration testing: TestContainers, @SpringBootTest
- [ ] API testing: MockMvc, REST Assured
- [ ] Testing mindset: what to test, test pyramid, TDD basics

## 9️⃣ DevOps & Deployment

- [ ] Docker: Dockerfile, multi-stage builds, compose
- [ ] CI/CD: GitHub Actions, Jenkins basics
- [ ] Cloud: AWS basics (EC2, RDS, S3, ECS)
- [ ] Monitoring: health checks, metrics, Prometheus/Grafana

## 🔟 System Design (for interviews)

- [ ] Scalability: horizontal vs vertical, caching, CDN
- [ ] Load balancing, reverse proxy
- [ ] Message queues, event-driven architecture
- [ ] Database sharding, replication, read replicas
- [ ] CAP theorem, eventual consistency
- [ ] Design exercises: URL shortener, chat system, notification service
