![diagram-export-4-30-2025-12_17_50-AM](https://github.com/user-attachments/assets/ec0a4a10-30ac-4dc9-84e1-52ef7ffe2d94)# SelfStoreHome
ReadMe for SelfStore
Different Services:
-Product Service: https://github.com/sazar111/ProductService
-User Service: https://github.com/sazar111/SelfStore-UserService
-Payment Service: https://github.com/sazar111/SelfStore-PaymentService
-Service Discovery: https://github.com/sazar111/SelfStore-ServiceDiscovery
-Api Gateway: https://github.com/sazar111/SelfStore-ApiGateway
-Intelligence Service:

Architecture Diagram:
![diagram-export-4-30-2025-12_17_50-AM](https://github.com/user-attachments/assets/193b8e34-3c1a-4f3d-b6df-3e463d2abfcd)

Summary:
🚀 Built a distributed Amazon-style E-commerce backend using Java, Spring Boot, Python, GenAI, and MSSQL, architected for scale, performance, and reliability.\n
-> Designed and implemented 6+ specialized microservices including Product, User (Auth), Payment (Stripe/Razorpay), API Gateway, Intelligence (LLM), and Service Discovery.
-> Developed a GenAI-powered Intelligence Service using Groq LLM Agents, following Claude’s MCP Protocol to host an MCP server. CRUD operations enabled via natural language using tool integration ,ReAct model and RAG (Retrieval-Augmented Generation) to minimize hallucinations and increased accuracy.
-> Fortified system security with Spring Security, OAuth 2.0, JWT authentication, and encrypted password management via BCrypt.
-> Boosted Product Service API performance from 2s to 900ms using Redis Cloud caching, further optimized to 10ms with local Redis caching and seamless Fakestore API integration via the Adapter pattern.
-> Engineered real-time payment flows by integrating Stripe and Razorpay, dynamically generating payment URLs and instantly updating transaction statuses.
-> Connected microservices through Eureka and Spring Cloud, enabling dynamic service discovery, load balancing, and health monitoring.
-> Streamlined database migrations and management with Flyway, leveraging centralized MSSQL storage across the platform.
-> Launched a RAG-based agent backed by ChromaDB, reducing vector search response times from 4s to 900ms, powering smart Q&A and dynamic system explanations via an interactive UI.
-> Applied clean architecture principles, scalable RESTful API design, and modular design patterns to ensure maximum maintainability, performance, and growth readiness.
Tools: Java, Spring Boot, Spring Security, OAuth 2.0, JWT, BCrypt, Python, Groq LLM, Claude MCP Protocol, Redis (Cloud & Local), ChromaDB, Stripe, Razorpay, Eureka, Spring Cloud, Flyway, MSSQL, Fakestore API.
🚀 Built a distributed Amazon-style E-commerce backend using Java, Spring Boot, Python, GenAI, and MSSQL, architected for scale, performance, and reliability. -> Designed and implemented 6+ specialized microservices including Product, User (Auth), Payment (Stripe/Razorpay), API Gateway, Intelligence (LLM), and Service Discovery. -> Developed a GenAI-powered Intelligence Service using Groq LLM Agents, following Claude’s MCP Protocol to host an MCP server. CRUD operations enabled via natural language using tool integration ,ReAct model and RAG (Retrieval-Augmented Generation) to minimize hallucinations and increased accuracy. -> Fortified system security with Spring Security, OAuth 2.0, JWT authentication, and encrypted password management via BCrypt. -> Boosted Product Service API performance from 2s to 900ms using Redis Cloud caching, further optimized to 10ms with local Redis caching and seamless Fakestore API integration via the Adapter pattern. -> Engineered real-time payment flows by integrating Stripe and Razorpay, dynamically generating payment URLs and instantly updating transaction statuses. -> Connected microservices through Eureka and Spring Cloud, enabling dynamic service discovery, load balancing, and health monitoring. -> Streamlined database migrations and management with Flyway, leveraging centralized MSSQL storage across the platform. -> Launched a RAG-based agent backed by ChromaDB, reducing vector search response times from 4s to 900ms, powering smart Q&A and dynamic system explanations via an interactive UI. -> Applied clean architecture principles, scalable RESTful API design, and modular design patterns to ensure maximum maintainability, performance, and growth readiness. Tools: Java, Spring Boot, Spring Security, OAuth 2.0, JWT, BCrypt, Python, Groq LLM, Claude MCP Protocol, Redis (Cloud & Local), ChromaDB, Stripe, Razorpay, Eureka, Spring Cloud, Flyway, MSSQL, Fakestore API.
Skills: Java · Spring Framework · Generative AI · Model Context Protocol · Redis · Flyway · Vector Databases · Databases · MySQL · OAuth · bcrypt · Low-Level Design
