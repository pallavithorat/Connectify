# Connectify
A professional networking platform designed to help individuals connect, collaborate, and grow their careers by building meaningful relationships and opportunities.
## **Table of Contents**
- [Project Overview](#project-overview)
- [Key Feature](#key-features)
- [Tech Stack](#tech-stack)
- [Architecture](#architecture)
- [Microservices](#microservices-overview)

## **Project Overview**
Connectify is a modern networking platform designed for professionals to foster meaningful collaborations and career growth.
Users can connect with peers, share insights, and discover opportunities in a dynamic and secure environment.

## **Key Features**
- User authentication and authorization

- Profile creation and management

- Real-time messaging and notifications

- Recommendation system for meaningful connections

- Event and activity tracking

- Microservices architecture for scalable performance

## **Tech Stack**

- **Languages:** Java, PostgreSQL

- **Frameworks:** Spring Boot, Resilience4j

- **Databases:** PostgreSQL, Neo4j

- **Message Broker:** Apache Kafka

- **Service Discovery:** Eureka

- **API Communication:** OpenFeign

- **Containerization:** Docker, Kubernetes


## **Architecture**

Connectify is built using a microservices architecture, ensuring modularity, scalability, and maintainability.
It utilizes service discovery and resilient communication patterns to ensure a reliable user experience.

![Microservices Architecture](https://github.com/pallavithorat/Connectify/raw/main/microservicesSysDesign.png)


## **Microservices Overview**
- **API Gateway:** Routes requests to the appropriate microservices.

- **Connections Service:** Manages user connections and recommendations.

- **User Service:** Handles user registration, authentication, and profile management.

- **Posts Service:** Manages posting, liking, and unliking posts, allowing users to engage with shared content.

- **Messaging Service:** Supports real-time user communication.




