# 🛒 SelfStore – Distributed E-commerce Backend with GenAI Integration | Backend

[![Java](https://img.shields.io/badge/Java-17-blue?logo=java)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/SpringBoot-3.x-brightgreen?logo=spring)](https://spring.io/projects/spring-boot)
[![Python](https://img.shields.io/badge/Python-3.10-yellow?logo=python)](https://www.python.org/)
[![Redis](https://img.shields.io/badge/Redis-Cache-red?logo=redis)](https://redis.io/)
[![MSSQL](https://img.shields.io/badge/Database-MSSQL-informational?logo=microsoftsqlserver)](https://www.microsoft.com/en-us/sql-server)
[![LangChain](https://img.shields.io/badge/LangChain-GenAI-orange?logo=python)](https://www.langchain.com/)

**SelfStore** is a scalable, Amazon-style e-commerce backend system built using microservices with Java, Spring Boot, Python, and Groq LLMs. It integrates intelligent automation via Claude’s MCP Protocol, allowing natural language-driven product operations and real-time payment handling.

---

## 📌 Architecture Diagram

![SelfStore Architecture](https://github.com/user-attachments/assets/193b8e34-3c1a-4f3d-b6df-3e463d2abfcd)

---

## 🔗 Microservices Repositories

| Service               | Description                                | Repository Link                                                                   |
|------------------------|--------------------------------------------|------------------------------------------------------------------------------------|
| **Product Service**     | Product APIs, Redis caching, Fakestore Adapter | [Product Service](https://github.com/sazar111/ProductService)                     |
| **User Service**        | Authentication, JWT, OAuth 2.0, BCrypt      | [User Service](https://github.com/sazar111/SelfStore-UserService)                |
| **Payment Service**     | Stripe & Razorpay integration               | [Payment Service](https://github.com/sazar111/SelfStore-PaymentService)           |
| **Service Discovery**   | Eureka for service registry                 | [Service Discovery](https://github.com/sazar111/SelfStore-ServiceDiscovery)        |
| **API Gateway**         | Centralized routing and load balancing     | [API Gateway](https://github.com/sazar111/SelfStore-ApiGateway)                   |
| **Intelligence Service**| GenAI + MCP Server + RAG                   |                                                                       |

---

## 🧠 Intelligence Service (GenAI-Powered)

- Built with **Python**, **LangChain**, and **Groq LLMs**.
- Hosts a Claude **MCP Protocol server** enabling **natural language-based CRUD** for `ProductService` using LangChain tools.
- Uses **ReAct** for reasoning and tool selection.
- Includes a **RAG-based Agent** that provides code explanations and smart answers to developer queries.
- Vector database powered by **ChromaDB**.
- Observability and debugging handled via **LangSmith**.

---

## 📸 Feature Snippets

| Screenshot | Description |
|-----------|-------------|
| ![RAG UI](https://github.com/user-attachments/assets/1acef969-e2fb-44b7-8f7c-77c33e9874e7) | 🔍 RAG Agent answering how the system works |
| ![MCP Agent](https://github.com/user-attachments/assets/fd92204e-8232-4645-906b-9b6aeb9f4268) | 🛠️ Creating a product via natural language with MCP Agent |
| ![Payment](https://github.com/user-attachments/assets/3d3ca512-2e86-40bc-9685-06017e681dd1) | 💳 Stripe-based real-time payment flow |

---

## ⚙️ Key Features

- 🚀 **Modular Microservices** with Spring Boot and Python
- 🔁 **Service Discovery** via Eureka and Spring Cloud
- 🛡️ **Security**:
  - OAuth 2.0, JWT-based authentication
  - BCrypt encrypted passwords
- 💳 **Payment Systems**:
  - Stripe & Razorpay integration
  - Dynamic URLs and real-time payment updates
- ⚡ **Optimized Performance**:
  - Redis Cloud + local Redis caching (2s → 10ms)
  - RAG vector search with ChromaDB (4s → 900ms)
- 🧼 **Clean Architecture**:
  - DTOs, Adapter Pattern, RESTful APIs
- 🔄 **Database Migrations** with Flyway
- 🧠 **Intelligence Layer** using GenAI, MCP, ReAct, and RAG

---

## 🧰 Tech Stack

- **Languages**: Java 17, Python 3.10  
- **Frameworks**: Spring Boot, Spring Security, Spring Cloud, LangChain  
- **AI/LLM**: Claude, Groq, MCP Protocol, RAG, LangSmith  
- **Storage**: MSSQL, Redis (local/cloud), ChromaDB  
- **Auth & Security**: OAuth 2.0, JWT, BCrypt  
- **Payments**: Stripe, Razorpay  
- **DevOps**: Flyway, Eureka, API Gateway  

---

## 🧑‍💻 Skills Demonstrated

`Java · Spring Boot · Python · Redis · MSSQL · OAuth · JWT · Claude MCP · GenAI · LangChain · LangSmith · RAG · Flyway · Microservices · API Gateway · Eureka · Adapter Pattern · System Design · Low-Level Design`

---

