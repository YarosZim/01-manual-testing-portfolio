# Manual QA Testing Portfolio — SauceDemo

## About This Project

This repository demonstrates a practical manual testing approach for the SauceDemo web application.

The project covers the main stages of the software testing process:

- Test Planning
- Test Case Design
- Test Execution
- Checklist Testing
- Bug Reporting
- Test Summary
- Test Design Techniques

The goal of this project is to demonstrate practical QA skills using a real web application.

---

## Application Under Test

**Application:** SauceDemo

**URL:** https://www.saucedemo.com/

**Application Type:** Web E-commerce Application

---

## Testing Scope

The following functionality is covered by the project:

### Authentication

- Login with valid credentials
- Login with invalid credentials
- Login with empty username
- Login with empty password

### Products

- Product visibility
- Product information
- Product sorting
- Product details
- Add product to cart
- Remove product from cart

### Shopping Cart

- Cart contents
- Product information
- Remove product from cart
- Continue shopping
- Checkout navigation

### Checkout

- Checkout form validation
- Valid checkout information
- Checkout overview
- Product and price verification
- Order completion

---

## Test Artifacts

### Test Plan

The overall testing strategy, scope, environment, risks and entry/exit criteria are documented in:

[`test-plan.md`](test-plan/test-plan.md)

### Test Cases

The test cases are organized by application functionality:

- [Login Test Cases](test-plan/test-cases/login-test-cases.md)
- [Products Test Cases](test-plan/test-cases/products-test-cases.md)
- [Cart Test Cases](test-plan/test-cases/cart-test-cases.md)
- [Checkout Test Cases](test-plan/test-cases/checkout-test-cases.md)

### Test Design Techniques

The project demonstrates:

- Equivalence Partitioning
- Boundary Value Analysis
- Decision Table Testing

See:

[Test Design Techniques](test-plan/test-cases/test-design-techniques.md)

### Decision Table

A Login decision table is available here:

[Login Decision Table](test-plan/test-cases/decision-table-login.md)

---

## Test Types

The project includes:

- Functional Testing
- Smoke Testing
- Regression Testing
- Exploratory Testing
- Positive Testing
- Negative Testing
- Usability Testing

---

## Test Environment

| Parameter | Value |
|---|---|
| Application | SauceDemo |
| Application Type | Web |
| Browser | Google Chrome |
| Operating System | Windows |
| Test Level | UI |
| Test Type | Functional |

---

## Test Data

### Valid Credentials


Username: standard_user
Password: secret_sauce

### Invalid Credentials


Username: invalid_user
Password: InvalidPassword123

---

### Checkout Data

First Name: John
Last Name: Smith
Postal Code: 12345

---

Test Execution

| Status       | Description                                  |
| ------------ | -------------------------------------------- |
| PASS         | Actual result matches expected result        |
| FAIL         | Actual result does not match expected result |
| BLOCKED      | Test cannot be executed                      |
| NOT EXECUTED | Test has not yet been executed               |
