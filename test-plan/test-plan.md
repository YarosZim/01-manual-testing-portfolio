# Test Plan — SauceDemo

## 1. Introduction

This Test Plan describes the testing approach for the SauceDemo web application.

**Application Under Test:** SauceDemo  
**URL:** https://www.saucedemo.com/

SauceDemo is a demo e-commerce web application used for testing web application functionality.

---

## 2. Test Objective

The main objective is to verify that the core e-commerce functionality works as expected.

The testing focuses on:

- User authentication
- Product catalog
- Product sorting
- Product details
- Shopping cart
- Checkout
- Order completion

The goal is to identify functional defects and verify that the main user flows work correctly.

---

## 3. Scope

### 3.1 In Scope

#### Authentication

- Login with valid credentials
- Login with invalid credentials
- Login with empty username
- Login with empty password

#### Products

- Product visibility
- Product information
- Product sorting
- Product details
- Adding products to cart
- Removing products from cart

#### Shopping Cart

- Cart contents
- Product information in cart
- Removing products from cart
- Continue Shopping
- Navigation to Checkout

#### Checkout

- Checkout form validation
- Valid checkout information
- Checkout overview
- Product and price verification
- Order completion

---

### 3.2 Out of Scope

The following areas are outside the scope of this project:

- Performance testing
- Load testing
- Security testing
- Database testing
- API testing
- Real payment processing
- Cross-browser compatibility testing
- Mobile application testing

---

## 4. Test Types

### Functional Testing

Verify that application functionality behaves according to the expected requirements.

### Smoke Testing

Verify that the main application functionality is available and usable.

### Regression Testing

Verify that previously tested functionality continues to work after changes.

### Exploratory Testing

Explore the application to identify unexpected behavior and potential defects.

### Positive Testing

Verify that the application works correctly with valid input and expected user actions.

### Negative Testing

Verify that the application handles invalid input and unexpected user actions correctly.

### Usability Testing

Evaluate basic usability and clarity of the user interface.

---

## 5. Test Design Techniques

The following test design techniques are applied:

- Equivalence Partitioning
- Boundary Value Analysis
- Decision Table Testing

Detailed examples are documented in:

`test-cases/test-design-techniques.md`

The Login decision table is documented in:

`test-cases/decision-table-login.md`

---

## 6. Test Environment

### Application

SauceDemo

### URL

https://www.saucedemo.com/

### Application Type

Web application

### Browser

Google Chrome

### Operating System

Windows

---

## 7. Test Data

### Valid Credentials

Username:

`standard_user`

Password:

`secret_sauce`

### Invalid Credentials

Username:

`invalid_user`

Password:

`InvalidPassword123`

### Checkout Test Data

First Name:

`John`

Last Name:

`Smith`

Postal Code:

`12345`

---

## 8. Test Deliverables

The following QA artifacts are included in this project:

- Test Plan
- Test Cases
- Test Design Techniques
- Decision Table
- Checklist
- Bug Reports
- Test Execution Results
- Test Summary

---

## 9. Entry Criteria

Testing can start when:

- SauceDemo is accessible.
- The Login page is available.
- Test credentials are available.
- The application is sufficiently stable for testing.

---

## 10. Exit Criteria

Testing can be considered complete when:

- All planned test cases have been executed.
- Test results have been documented.
- Critical defects have been reported.
- Test coverage has been reviewed.
- A Test Summary has been prepared.

---

## 11. Risks and Assumptions

### Risks

- Application availability may change.
- Application behavior may change without notice.
- Test environment issues may affect test execution.
- Demo application data may be reset or modified.

### Assumptions

- SauceDemo is available during test execution.
- Provided test credentials are valid.
- The application can be accessed using Google Chrome.
- No production data is used during testing.

---

## 12. Test Execution

Test execution results will be documented separately after the test cases are executed.

### Test Statuses

**PASS** — Actual result matches the expected result.

**FAIL** — Actual result does not match the expected result.

**BLOCKED** — Test cannot be executed because of an external issue.

**NOT EXECUTED** — Test has not yet been executed.
