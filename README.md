# OrderProcessingApi

A Spring Boot application for managing and processing orders efficiently, with persistence, exception handling, and automated tests.

## Overview

This project is designed to handle order-related operations through a REST API, with a clean service-based architecture and support for persistence and validation.

## Project Structure

```text
OrderProcessingApi/
├── .mvn/
│   └── wrapper/                 # Maven wrapper files
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── OrderProcessingApi/
│   │   │           ├── controller/   # REST controllers
│   │   │           ├── exception/    # Custom exceptions and exception handlers
│   │   │           ├── model/        # Domain models
│   │   │           ├── repository/   # Data access layer
│   │   │           ├── service/      # Business logic
│   │   │           ├── view/         # CRUD views / presentation layer
│   │   │           └── OrderProcessingApiApplication.java
│   │   └── resources/
│   │       └── application.properties
│   └── test/
│       └── java/                 # Unit and integration tests
├── pom.xml                       # Maven project configuration
├── orders.txt                    # Sample order data file
├── order_2.txt                   # Additional sample order file
├── README.md                     # Project documentation
└── .gitignore                    # Git ignore settings
```

## Features

- Spring Boot-based API for order processing
- Data persistence support
- Centralized exception handling
- Service-layer business logic
- Automated testing setup
- Simple sample order files for testing and demonstration

## Prerequisites

Before running the application, make sure you have:

- Java 17 or later
- Maven
- An IDE such as IntelliJ IDEA or VS Code, or a terminal for running commands

## Getting Started

1. Clone the repository.
2. Open the project in your IDE or terminal.
3. Run the application with Maven:

```bash
mvn spring-boot:run
```

4. If you are using the Maven wrapper:

```bash
./mvnw spring-boot:run
```

## Running Tests

```bash
mvn test
```

## Notes

This project is intended to demonstrate a structured order processing workflow and can be extended with additional endpoints, validation, and persistence logic depending on the application requirements.
