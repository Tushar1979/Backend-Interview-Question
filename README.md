# Backend-Interview-Question

⭐ 1. JavaScript & Node.js Core (Advanced)
Core Concepts
Explain how the Node.js event loop works in detail. What are phases like poll, timers, check, close callbacks?


Difference between microtasks & macrotasks? How does it impact performance?


How do Worker Threads work in Node? When do you use them?


What is the difference between Cluster mode and Worker Threads?


How is Node.js single-threaded yet handles concurrency?


Explain libuv and its thread pool.


What are Streams? Explain types: Readable, Writable, Duplex, Transform.


What is Backpressure in streams?


Explain Node.js Buffer and use cases.


What is the purpose of process.nextTick() vs setImmediate()?


Why is synchronous code dangerous in Node.js?


What are Memory leaks in Node.js? How do you detect and fix them?


How does V8 manage memory?


Explain custom error handling strategy in Node applications.


Explain the Module caching mechanism in Node.js.



⭐ 2. Express.js / API Architecture (Senior Level)
Express Concepts
Explain the middleware pattern in Express and how the pipeline works.


How do you structure a large Express application (layers, modules, services)?


How to implement a global error handler in Express?


What is the purpose of Router-level middleware?


How do you protect APIs using rate-limiting?


How do you implement file uploads efficiently (streaming vs memory upload)?


JWT vs Session-based auth — what do you choose and why?


How to implement RBAC (Role-Based Access Control) properly?


How do you write a custom authentication middleware?


How would you design a multi-tenant system in Express?



⭐ 3. MongoDB (Expert-Level)
Data Modeling
When should you embed vs reference data in MongoDB?


Explain schema design for an e-commerce platform.


What is a write concern and read concern?


Explain replica set architecture.


What are transactions in MongoDB? When should you use them?


Explain sharding in MongoDB. How do you choose a shard key?


What are index types in MongoDB (compound, partial, TTL, text, hashed)?


Explain Mongo’s aggregation pipeline with real-world example.


How do you profile slow Mongo queries?


What is a covered query?


What is Schema versioning? How do you support rolling upgrades?


How to handle large collections with millions of documents efficiently?


How would you avoid hot shard issues?



⭐ 4. Redis / Caching / Message Queues
Caching
Explain Redis architecture (single-threaded but fast — why?).


What are Redis eviction policies?


How to design a distributed cache invalidation system?


Write-through vs Write-behind cache: which one to use?


How do you implement rate limits using Redis?


Message Queues
Explain RabbitMQ vs Kafka — differences & use cases.


What is exactly-once message delivery? Is it achievable?


Explain dead-letter queues.


What is Kafka partitioning strategy and consumer group?



⭐ 5. System Design (Backend-Focused)
High-Level Design Questions
Design a scalable Notification System.


Design a Chat Application (WhatsApp-like).


Design Instagram Feed.


Design Uber backend.


Design a real-time location tracking system.


Design an E-commerce Search System with filters & ranking.


Design a Job Scheduler (like cron but distributed).


Design an API Gateway.


Conceptual
Vertical vs horizontal scaling — which to choose?


How do CDNs reduce load on backend?


Explain Circuit Breaker Pattern.


Explain Rate Limiter algorithms (Token Bucket, Leaky Bucket, Fixed Window).


What is backpressure in distributed systems?


Explain CQRS and Event Sourcing.


What is idempotency in APIs? How to implement it?


Difference between monolithic, microservices, modular monolith.



⭐ 6. Security (Backend-Focused)
Application Security
Explain XSS, CSRF, SSRF, SQL/NoSQL injection.


How do you secure JWT tokens?


Access token vs Refresh token?


How do you detect & block token hijacking?


What is Content Security Policy (CSP)?


What are security headers and how does Helmet help?


How do you store passwords securely?


How to mitigate DOS attacks?


How do you secure file uploads?


What is OAuth2 Authorization Code Flow?



⭐ 7. DevOps & Deployment (Real-World Experience)
DevOps Concepts
Explain your CI/CD pipeline design.


What is a blue-green deployment?


What is rolling deployment?


How do you handle zero-downtime deployments?


Explain Docker multi-stage builds.


What are health checks in Docker/Kubernetes?


What is an Ingress controller?


Explain horizontal pod autoscaling.


What is service mesh?


What is infrastructure as code (Terraform)?



⭐ 8. API Design & Best Practices
API Engineering
REST vs GraphQL — when and why?


What is pagination strategy? Offset vs Cursor?


How do you implement Idempotent APIs (PUT, DELETE)?


Explain API versioning strategies.


How do you design a fault-tolerant distributed API?


Why use OpenAPI (Swagger)?


How do you test backend APIs? (Jest + Supertest)


What is HATEOAS?


How do you ensure backward compatibility?



⭐ 9. Real-World Experience Questions (Hiring Managers Ask)
Explain a time you optimized backend performance & what changed.


Describe a large-scale challenge you solved involving millions of records.


How do you debug production issues?


Explain how you monitor logs, uptime, and performance.


What's the most complex API you've designed and why?


How do you prevent accidental downtime during deployments?


Have you ever designed your own internal library/framework?


How do you mentor junior backend developers?
