# E-Commerce API Automation

## Project Overview
This project automates E-Commerce REST APIs using Postman and JavaScript. It covers positive, negative, authentication, data-driven and response validation scenarios.

## Tools & Technologies
- Postman
- JavaScript (Postman Tests & Pre-request Scripts)
- Newman
- Newman HTML Extra Reporter
- GitHub
- Jenkins (CI/CD – planned)

## Test Coverage
- GET, POST API testing
- Status code and response time validation
- JSON response and schema validation
- Positive and negative scenarios
- Bearer token authentication
- Environment and collection variables
- Dynamic test data generation
- CSV and JSON data-driven testing
- Collection, folder and request-level scripts
- Newman CLI execution and HTML reporting

## Execution
Run the collection using Newman:

```bash
newman run "E-Commerce API Automation.postman_collection.json" -e "QA_Environment.postman_environment.json" -r cli,htmlextra --reporter-htmlextra-export "Newman_Report.html"
```

## Test Reports
Newman HTML Extra Reporter generates an HTML execution report containing request details, assertions, and failures.

## API Base URL
https://dummyjson.com

## Author
Swamy Dandu
