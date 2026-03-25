# acnecare_api

## Overview
acnecare_api is a Spring Boot–based REST API backend for the AcneCare system. The project includes:
User management and authentication using JWT
Role- and permission-based authorization with Spring Security
File upload handling and serving from the local file system
Real-time updates via WebSocket (STOMP + SockJS) for posts, likes, comments, appointments, etc.
Data persistence using JPA with MySQL (and H2 for testing)

## Technology Stack
- Java 21 (Eclipse Temurin)
- Spring Boot (Spring MVC, Spring Security, OAuth2 Resource Server, WebSocket)
- Spring Data JPA (Hibernate)
- MySQL (run local/dev)
- H2 (test)
- Maven Wrapper (`./mvnw`)
