# X-Transact: Microservices-Based Banking System

A scalable banking system built using microservices architecture with Spring Boot and Spring Cloud, supporting Accounts, Cards, and Loans services.

## 🚀 Features
- Microservices architecture with independent services
- API Gateway for centralized routing
- Service discovery using Eureka
- Centralized configuration using Config Server
- Secure authentication using Keycloak (JWT)
- Asynchronous communication using Kafka
- Rate limiting using Redis
- Inter-service communication using OpenFeign
- Containerization using Docker

## 🏗️ Architecture
- API Gateway → routes requests
- Eureka → service discovery
- Config Server → centralized config
- Microservices → business logic
- Kafka → async communication
- Redis → rate limiting

## 🛠️ Tech Stack
- Backend: Spring Boot, Spring Cloud
- Security: Keycloak, JWT
- Messaging: Kafka
- Cache: Redis
- DevOps: Docker, Kubernetes
- Database: H2

## ▶️ How to Run
1. Start Config Server
2. Start Eureka Server
3. Start all microservices
4. Start API Gateway
5. Access APIs via Gateway

## 📌 Future Improvements
- Add persistent DB (MySQL/Postgres)
- Implement distributed tracing (Zipkin)
- Add monitoring dashboard
