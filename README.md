# spring-boot-hello-world
Simple Spring Boot project demonstrating the creation of a Hello World REST API. Includes basic REST endpoints, JSON responses, and URI parameter handling.

# Spring Boot Hello World Project

This project demonstrates the creation of a Hello World REST API using Spring Boot. It includes basic REST endpoints, JSON responses, and URI parameter handling.

## Getting Started

### Prerequisites

- Java Development Kit (JDK)
- Integrated Development Environment (IDE) - Optional
- Maven

### Running the Application

1. Clone the repository:
   bash

   git clone <https://github.com/arpitamishra27/spring-boot-hello-world.git>

2. Navigate to the project directory:

 bash
 cd helloworld-springboot

3. Run the application:
    mvn spring-boot:run

The application will start, and you can access the Hello World API at http://localhost:8080/welcome.

### Endpoints
/welcome: Returns a simple "Hello World!!!" message.
/welcome-with-object: Returns a JSON response with a message.
/welcome-with-parameter/name/{name}: Returns a personalized greeting based on the provided name.

### Live Reload
Enable Live Reload for automatic application restart and browser refresh during development. You can use browser extensions available at livereload.com/extensions.

