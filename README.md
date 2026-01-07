# 🧑‍💼 GraphQL Employee Server (Schema + Resolvers)

A backend GraphQL service implementation that powers an existing Angular employee directory client.
This project focuses on building the **GraphQL schema** and **resolvers** required for the client to persist and retrieve employee records.

The goal is a minimal but functional GraphQL server that supports the client’s queries and mutations.

---

## ✨ Features

- 🧾 GraphQL schema definition (`employee.graphqls`)
- 🧠 Resolver implementation (`EmployeesResolver`) for:
  - ✅ Creating employee records
  - 📋 Fetching all employees for table display
- 🔌 Compatible with a pre-built Angular client (GraphQL-powered version of the employee directory)

---

## 🛠 Tech Stack

- **Spring Boot (GraphQL)** *(or equivalent GraphQL server framework, depending on your starter code)*
- **GraphQL Schema (.graphqls)**
- **Resolvers**
- **Java / Kotlin**

---

## 🚀 Run Locally

> Commands may vary slightly based on your build tool.

### Gradle
```bash
./gradlew bootRun
```

### Maven
```bash
mvn spring-boot:run
```

Server runs on: `http://localhost:8080` *(typical default)*

---

## 🧪 Quick Test (GraphQL)

Use a GraphQL client (GraphiQL, Insomnia, Postman) to verify:

- Query: list all employees
- Mutation: add employee
- Query again: confirm persistence/return data

---

## 🧠 What This Project Demonstrates

- Designing GraphQL contracts to match client needs
- Implementing resolvers that map GraphQL operations to backend logic
- Building a “just enough” server to unblock frontend integration (real-world skill)

---


📌 *A practical GraphQL backend implementation designed to integrate cleanly with a real Angular client.*
