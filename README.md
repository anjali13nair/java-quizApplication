# Quiz Application - Microservices Architecture

This repository contains a **Quiz Application** developed using **Spring Boot** and a **Microservices architecture**. The project demonstrates the implementation of a distributed system with multiple independent services, showcasing best practices for building scalable and maintainable applications.

---

## Services

### 1. Service Registry
- Acts as a centralized directory for all microservices.
- Enables efficient service discovery and communication.

### 2. API Gateway
- Serves as the single entry point for client requests.
- Routes requests to appropriate microservices.
- Handles cross-cutting concerns such as authentication, logging, and rate limiting.

### 3. Question Service
- Manages the creation, storage, and retrieval of quiz questions.
- Provides endpoints for adding new questions and fetching existing ones.

### 4. Quiz Service
- Orchestrates the quiz-taking process.
- Integrates with the Question Service to present questions to users.
- Handles user responses and maintains the flow of the quiz.

---

## Key Features
- **Microservices Architecture**  
  Each service is independently deployable and scalable, promoting flexibility and maintainability.

- **Service Discovery**  
  The Service Registry allows dynamic discovery of services, facilitating seamless communication between them.

- **Centralized Routing**  
  The API Gateway manages all incoming requests, directing them to the appropriate service and handling common concerns.

---

## Technology Stack
- **Spring Boot**: Framework for building the microservices.
- **Spring Cloud**: Tools for service discovery, routing, and cloud-native patterns.
- **Java**: The primary programming language.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/anjali13nair/java-quizApplication.git

2. Navigate to each service directory and build the services:
    ```bash
      mvn clean install

3. Start the services in the following order:
-Service Registry
-API Gateway
-Question Service
-Quiz Service

4. Access the application through the API Gateway URL.


## Contact
If you have any questions, suggestions, or feedback, feel free to reach out:  
- **GitHub**: [@anjali13nair](https://github.com/anjali13nair)
- **Email**: anjalinnair13@gmail.com
- **LinkedIn**:[Anjali Nair](https://www.linkedin.com/in/anjalinnair13/)

