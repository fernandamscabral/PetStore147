# Playwright API Tests – Swagger PetStore

This repository contains API test automation examples for the [Swagger PetStore API](https://petstore.swagger.io/).


The project was created during QA training activities and demonstrates common API testing concepts using Playwright.

---

## 📚 Context

This project was developed during the *Formação em Teste de Software e QA* at [Iterasys](https://iterasys.com.br/) (class 147).

The goal of the project was to introduce API testing with Playwright and demonstrate concepts such as:

- CRUD operations
- request and response validation
- authentication and token usage
- test data management
- Data-Driven Testing (DDT)

The implementation was developed alongside instructor guidance as part of the training activities.

## 🛠️ Tech Stack

- JavaScript
- Playwright
- REST API Testing
- CSV
- Swagger / OpenAPI

## 🌐 API Under Test

- API: Swagger PetStore
- Documentation: https://petstore.swagger.io/
- Specification: OpenAPI / Swagger

## 🧠 Testing Approach

This project demonstrates different API testing techniques using Playwright:

- CRUD operation validation
- request and response assertions
- authentication and token extraction examples
- authenticated requests using bearer tokens
- test data externalization
- Data-Driven Testing (DDT) with CSV files
- reusable API test structure

## 📌 Test Coverage

The project includes examples for:

### Pet Entity

- Create Pet (POST)
- Get Pet by ID (GET)
- Update Pet (PUT)
- Delete Pet (DELETE)

### Authentication

- login request example
- token extraction
- authenticated request example

### Data-Driven Testing

- CSV test data
- parameterized API requests
- data-driven POST Pet example

## 🗂️ Project Structure

```text
data/
  csv/
    pets.csv
  json/
    pet.json

tests/
  api/
    pet.spec.js

docs/
  comentarios.txt

playwright.config.js
package.json
```
### Structure overview

- **data/csv/** → CSV test data used for DDT examples
- **data/json/** → JSON payloads used in API requests
- **tests/api/** → Playwright API test suites
- **docs/** → class notes and supporting comments
- **playwright.config.js** → Playwright configuration and base URL settings
- **package.json** → project dependencies and execution scripts
---

## 📌 Project Status

This repository represents the final state of the PetStore API testing exercises developed during QA training at Iterasys.

It is maintained as a study and portfolio project demonstrating Playwright API testing concepts and techniques.

## ▶️ How to Run the Tests

Install dependencies:

```bash
npm install
```

Run all tests:

```bash
npx playwright test
```

---

## 📚 Notes

Swagger PetStore is a public API commonly used for learning and practicing API testing.

This project does not aim to provide full API coverage.

Its purpose is to demonstrate core API testing concepts with Playwright through practical examples developed during QA training.