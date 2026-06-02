# MoveX - Distributed Ride Booking Platform

A scalable ride-booking platform built using Spring Boot microservices.

## System Architecture

![Architecture](architecture/movex-architecture.png)

## Tech Stack

- Java
- Spring Boot
- PostgreSQL
- Kafka
- Eureka Service Discovery
- WebSockets
- Docker

## Key Features

- Distributed microservice architecture
- Event-driven communication using Kafka
- Real-time ride updates via WebSockets
- Service discovery using Eureka
- JWT authentication and authorization
- Independent service deployment

## Services
| Service | Responsibility | Repository |
|----------|--------------|------------|
| Auth Service | Authentication & JWT | [Repo](https://github.com/Abhinavhaldiya/UberAuthService) |
| Booking Service | Ride lifecycle management | [Repo](https://github.com/Abhinavhaldiya/UberBookingService) |
| Location Service | Driver tracking | [Repo](https://github.com/Abhinavhaldiya/UberLocationService) |
| Review Service | Ratings & Reviews | [Repo](https://github.com/Abhinavhaldiya/UberReviewService) |
| Socket Service | Real-time notifications | [Repo](https://github.com/Abhinavhaldiya/UberSocketServer) |
| Entity Service | Shared business entities | [Repo](https://github.com/Abhinavhaldiya/UberEntityService) |
| Eureka Server | Service discovery | [Repo](https://github.com/Abhinavhaldiya/UberServiceDiscoveryEurekaServer) |
