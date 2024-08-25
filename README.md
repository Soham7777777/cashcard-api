# Cashcard Management API
---

## Overview

This project is a REST API built with Java Spring Boot that provides basic CRUD (Create, Read, Update, Delete) operations for managing cashcards. The API includes authentication and authorization features to ensure that only authorized users can access or modify cashcard data.

## Features

- CRUD Operations: Perform Create, Read, Update, and Delete operations on cashcards.
- Authentication: Secure endpoints with authentication to ensure that only logged-in users can access the API.
- Authorization: Role-based access control to manage permissions and protect sensitive data.\

## Technologies Used

- Java Spring Boot: Framework for building the REST API.
- Spring Security: Provides authentication and authorization.
- H2 Database: In-memory database used for development and testing (can be replaced with other databases like MySQL or PostgreSQL).
- Gradle: Dependency management and build automation tool.

## Installation

**Prerequisites:**

- JDK 17 or later
- Gradle

```
git clone https://github.com/Soham7777777/cashcard-api.git
cd cashcard-api
./gradlew build
java -jar build/libs/cashcard-0.0.1-SNAPSHOT.jar
```

## Testing

`./gradlew test`

## Run Locally

`./gradlew bootrun`