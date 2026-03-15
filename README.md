# E-Commerce API Testing with Postman

API test collection for e-commerce endpoints using DummyJSON.

## Tech Stack
- Postman
- Newman
- newman-reporter-htmlextra

## Features
- Complete collection: Auth, Products, Cart, Users
- Environment management (prod & mock)
- Pre-request script for dynamic token management
- Positive & negative test scenarios
- Automated assertions: status code, response time, schema validation
- Newman HTML report

## How to Run
1. Install Newman
   npm install -g newman
   npm install -g newman-reporter-htmlextra

2. Run collection
   newman run "E-Commerce Mini.postman_collection.json" -e "DummyJSON.postman_environment.json" -r htmlextra

## Test Results
- Total Requests: 31
- Total Assertions: 40
- Failed: 0
