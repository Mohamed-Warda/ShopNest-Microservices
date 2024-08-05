# ShopNest-Microservices
ShopNest is a comprehensive microservices project designed to showcase advanced techniques and best practices for building scalable and cloud-native applications using .NET 8. This project integrates various modern technologies to develop a robust e-commerce platform.

## Project Overview

ShopNest demonstrates the implementation of microservices using the following technologies:

- **ASP.NET Web API**
- **Docker**
- **RabbitMQ**
- **MassTransit**
- **gRPC**
- **YARP API Gateway**
- **PostgreSQL**
- **Redis**
- **SQLite**
- **SQL Server**
- **Marten**
- **Entity Framework Core**
- **CQRS**
- **MediatR**
- **Domain-Driven Design (DDD)**
- **Vertical and Clean Architecture**

## Project Modules

### Catalog Microservice
- **ASP.NET Core Minimal APIs** using .NET 8 and C# 12.
- **Vertical Slice Architecture** with feature folders.
- **CQRS** implementation with MediatR and FluentValidation.
- **Marten** for transactional document storage on PostgreSQL.
- **Carter** for defining Minimal API endpoints.
- **Docker** configuration for multi-container setups.

### Basket Microservice
- **ASP.NET 8 Web API** with REST principles and CRUD operations.
- **Redis** for distributed caching.
- **Design Patterns** including Proxy, Decorator, and Cache-aside.
- **gRPC** service consumption for synchronous communication.
- **MassTransit** and **RabbitMQ** for message brokering.

### Discount Microservice
- **ASP.NET gRPC Server** for high-performance communication.
- **Protobuf** for defining messages and data structures.
- **Entity Framework Core** with SQLite for data management.
- **SQLite** setup and containerization.

### Ordering Microservice
- **DDD, CQRS, and Clean Architecture** using best practices.
- **CQRS** with MediatR, FluentValidation, and Mapster.
- **Domain and Integration Events** for event-driven design.
- **EF Core** Code-First approach with SqlServer configuration.

### YARP API Gateway
- **YARP Reverse Proxy** for implementing API Gateways.
- **Routing, Clustering, and Path Transformation**.
- **Rate Limiting** using FixedWindowLimiter.
- **Sample microservices/containers** for API gateway routing.

### WebUI ShoppingApp Microservice
- **ASP.NET Core Web Application** with Bootstrap 4 and Razor templates.
- **Refit Library** for consuming YARP API Gateway APIs.
- **Razor Tools** including View Components, Partial Views, and Tag Helpers.
- **Docker Compose** for orchestrating microservices and backing services.

## Getting Started

To get started with ShopNest, clone the repository and follow the setup instructions in the documentation provided within each module. Ensure you have Docker and the required tools installed for a smooth development experience.

## Tools Used
- **JetBrains Rider** or any preferred code editor.
- **Docker Desktop** for containerization and managing different database providers.
