# 🛒 SelfStore – Distributed E-commerce Backend with GenAI Integration

[![Java](https://img.shields.io/badge/Java-17-blue?logo=java)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/SpringBoot-3.x-brightgreen?logo=spring)](https://spring.io/projects/spring-boot)
[![Python](https://img.shields.io/badge/Python-3.10-yellow?logo=python)](https://www.python.org/)
[![Redis](https://img.shields.io/badge/Redis-Cache-red?logo=redis)](https://redis.io/)
[![MSSQL](https://img.shields.io/badge/Database-MSSQL-informational?logo=microsoftsqlserver)](https://www.microsoft.com/en-us/sql-server)
[![LangChain](https://img.shields.io/badge/LangChain-GenAI-orange?logo=python)](https://www.langchain.com/)

**SelfStore** is a scalable, Amazon-style e-commerce backend system built with microservices using Java, Spring Boot, Python, and Groq LLMs. It features intelligent automation using Claude’s MCP Protocol, natural language-driven product operations, and real-time payment systems.

---

## 📌 Architecture Diagram

![SelfStore Architecture](https://github.com/user-attachments/assets/193b8e34-3c1a-4f3d-b6df-3e463d2abfcd)

---

## 🔗 Microservices Repositories

| Service             | Description                                | Repository Link                                                                 |
|---------------------|--------------------------------------------|----------------------------------------------------------------------------------|
| **Product Service**     | Product APIs, Redis caching, Fakestore Adapter | [Product Service](https://github.com/sazar111/ProductService)                   |
| **User Service**        | Authentication, JWT, OAuth, BCrypt         | [User Service](https://github.com/sazar111/SelfStore-UserService)              |
| **Payment Service**     | Stripe & Razorpay payment integrations     | [Payment Service](https://github.com/sazar111/SelfStore-PaymentService)         |
| **Service Discovery**   | Eureka server for service registration     | [Service Discovery](https://github.com/sazar111/SelfStore-ServiceDiscovery)      |
| **API Gateway**         | Request routing and load balancing         | [API Gateway](https://github.com/sazar111/SelfStore-ApiGateway)                 |
| **Intelligence Service**| GenAI + MCP server with LLM + RAG         |                                                                |

---

## 🧠 Intelligence Service (GenAI-Powered)

- Built using **Python**, **LangChain**, and **Groq LLM**.
- Hosts a Claude **MCP Protocol server**, enabling natural language CRUD on `ProductService` using registered **tools**.
- External **MCP Agent** queries the service and invokes the appropriate tool based on user intent (using **ReAct model**).
- Includes a separate **RAG-based Agent** with access to the codebase for developer Q&A and system explanation.
- Vector storage with **ChromaDB**.
- All actions monitored using **LangSmith**.

---

## ⚙️ Key Features

- 🚀 **Microservice Architecture** with Spring Boot and Python services.
- 🔁 **Service Discovery** using Eureka and Spring Cloud for registration and load balancing.
- 🛡️ **Security**:
  - Spring Security with OAuth 2.0 and JWT
  - Encrypted password storage with BCrypt
- 💳 **Payment Gateway**:
  - Dynamic URL generation via Stripe and Razorpay
  - Real-time transaction update integration
- ⚡ **Performance Optimizations**:
  - Redis Cloud and local Redis for Product caching (2s → 10ms)
  - Vector search via ChromaDB (4s → 900ms)
- 🧼 **Clean Architecture**:
  - DTOs, Adapter pattern, RESTful APIs
  - Modular, scalable, and maintainable design
- 🔄 **Database Migrations**:
  - Managed via **Flyway**
  - Centralized **MSSQL** database

---

## 🧰 Tech Stack

- **Languages**: Java 17, Python 3.10
- **Frameworks**: Spring Boot, Spring Security, Spring Cloud, LangChain
- **AI**: Claude LLM, Groq, ReAct, RAG, LangSmith, MCP Protocol
- **Storage**: MSSQL, Redis (Local & Cloud), ChromaDB
- **Security**: OAuth 2.0, JWT, BCrypt
- **Payments**: Stripe, Razorpay
- **DevOps**: Flyway, Eureka, API Gateway

---

## 🧑‍💻 Skills Demonstrated

`Java · Spring Boot · Python · Redis · MSSQL · OAuth · JWT · Claude MCP · GenAI · LangChain · LangSmith · RAG · Flyway · Microservices · API Gateway · Eureka · Adapter Pattern · Low-Level Design · System Design`

---
