Java Version & Framework

- Java 17 with Spring Boot 3.2.0 (Maven-based)
- 1,242 Java source files across the project

  ---
Java 17 Language Features
┌────────────────────┬─────────────────────────────────────────────────────┐
│      Feature       │                        Usage                        │
├────────────────────┼─────────────────────────────────────────────────────┤
│ Records            │ 10 files using record syntax for immutable data     │
├────────────────────┼─────────────────────────────────────────────────────┤
│ Switch Expressions │ 64 instances with arrow-style syntax                │
├────────────────────┼─────────────────────────────────────────────────────┤
│ var keyword        │ Local variable type inference (3 instances)         │
├────────────────────┼─────────────────────────────────────────────────────┤
│ Lambdas            │ 496+ across 151 files                               │
├────────────────────┼─────────────────────────────────────────────────────┤
│ Streams API        │ 990+ usages (map, filter, collect, flatMap, toList) │
├────────────────────┼─────────────────────────────────────────────────────┤
│ Optional           │ Safe null-handling in 17+ files                     │
└────────────────────┴─────────────────────────────────────────────────────┘
  ---
Spring Boot Features

- Spring MVC / REST — 452+ HTTP endpoint mappings across 76+ controllers
- Spring Security — JWT, OAuth2 (Google, LinkedIn), AWS Cognito (3 pools)
- Spring Data JPA — 91+ entities, 155+ repositories, 270+ pagination usages
- Spring Data MongoDB — Dual database strategy (SQL + NoSQL)
- Spring WebFlux — Reactive WebClient for 7+ external service integrations
- Spring Cache — Caffeine-based caching with @Cacheable (14 files)
- Spring AOP — @Aspect for notifications, permissions, logging
- Spring Async — @EnableAsync with async method execution
- Spring Validation — 498+ Jakarta validation annotations + custom validators
- Spring Mail — Email sending via AWS SES
- Thymeleaf — Server-side template engine
- Quartz Scheduler — 25+ scheduled jobs with cron expressions

  ---
External Integrations

- AWS — S3, SES, SNS, Cognito, Lambda
- Payments — RazorPay, RevenueCat, iOS In-App Purchase
- Firebase — Push notifications
- WhatsApp API — Messaging
- PostHog — Product analytics (19+ events)
- Bitly — URL shortening
- iText PDF / Apache POI / OpenCSV — File processing (PDF, Excel, CSV)

  ---
Design Patterns & Architecture

- Service Layer (109+ @Service classes) + Repository Pattern (155+ repos)
- DTO Pattern (150+ DTOs) with Jackson JSON annotations
- Factory, Strategy, Builder, Observer, Decorator patterns
- Lombok — Massive usage (@Builder 624x, @Getter 665x, @AllArgsConstructor 932x)
- OpenAPI/Swagger — 1,519+ annotations for API documentation

  ---
Security & Enterprise Features

- 8+ custom security filters (JWT auth, multi-login detection, feature usage limits)
- Role-based access control (RBAC)
- Audit trail — 141+ audit annotations (@CreatedDate, @LastModifiedDate, @Version)
- Feature flags & usage quotas
- Exception handling — @ControllerAdvice with custom exceptions and error codes
- Internationalization (i18n) — Multi-language support

  ---
Testing

- Spring Boot Test, TestContainers, Spring Security Test
- 196+ test annotations across 30+ integration test suites
- @SpringBootTest, @WebMvcTest, @DataMongoTest, @ParameterizedTest

  ---
In short: This is a mature, enterprise-grade Spring Boot 3.2 / Java 17 application with a dual-database architecture, comprehensive security, reactive programming, job
scheduling, extensive third-party integrations, and clean layered architecture following industry best practices.
