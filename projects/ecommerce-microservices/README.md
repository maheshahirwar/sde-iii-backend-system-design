# E-Commerce Microservices System

## Overview
A large-scale e-commerce backend built using microservices and deployed on AWS.

This project demonstrates **SDE-III level ownership and architecture skills**.

---

## Services
- User Service
- Product Service
- Cart Service
- Order Service
- Payment Service
- Inventory Service

---

## Tech Stack
- Java, Spring Boot
- JWT Authentication
- MySQL
- Redis (Caching)
- Kafka (Event-driven)
- Docker
- AWS ECS, RDS, S3, API Gateway

---

## Architecture
- Microservices-based
- Event-driven (Kafka)
- Stateless services
- Cache-aside pattern

(Add architecture diagram here)

---

## Key Design Decisions
- Why Cart is Redis-based
- Why Order is event-driven
- How idempotency is handled
- Failure recovery strategies

---

## Scaling Strategy
- Horizontal scaling of services
- Read-heavy optimization using Redis
- Async processing for payments

---

## Interview Talking Points
- Service decomposition
- Consistency trade-offs
- Payment failure handling
- AWS deployment strategy
