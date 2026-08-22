# Test Execution Report — SauceDemo

## 1. Overview

This document contains the execution results of the manual test cases for the SauceDemo web application.

**Application:** SauceDemo

**URL:** https://www.saucedemo.com/

**Browser:** Google Chrome

**Operating System:** Windows

**Test Type:** Functional Testing

---

## 2. Test Execution Status

| Status | Description |
|---|---|
| PASS | Actual result matches the expected result |
| FAIL | Actual result does not match the expected result |
| BLOCKED | Test cannot be executed because of an external issue |
| NOT EXECUTED | Test has not yet been executed |

---

## 3. Test Execution Results

| ID | Test Case | Priority | Status | Actual Result |
|---|---|---|---|---|
| TC-001 | Successful login with valid credentials | High | PASS | User successfully logged in and was redirected to the Products page. |
| TC-002 | Login with valid username and invalid password | High | PASS | Login was rejected and an authentication error message was displayed. |
| TC-003 | Login with empty username | High | PASS | Login was rejected and a validation message was displayed for the Username field. |
| TC-004 | Login with empty password | High | PASS | Login was rejected and a validation message was displayed for the Password field. |
| TC-005 | Login with unregistered username | High | PASS | Login was rejected and an authentication error message was displayed. |
| TC-006 | Login with unregistered username and invalid password | High | PASS | Login was rejected and an authentication error message was displayed. |
| TC-007 | Products are displayed after successful login | High | PASS | Products were displayed with names, images, prices and Add to cart buttons. |
| TC-008 | Sort products by price from low to high | Medium | PASS | Products were sorted by price in ascending order. |
| TC-009 | Sort products by price from high to low | Medium | PASS | Products were sorted by price in descending order. |
| TC-010 | Open product details | Medium | PASS | Product details page was opened and product information was displayed. |
| TC-011 | Add product to cart from Products page | High | PASS | Selected product was added to the cart and the cart counter was updated. |
| TC-012 | Remove product from Products page | High | PASS | Selected product was removed and the cart counter was updated. |
| TC-013 | Added product is displayed in the cart | High | PASS | Added product was displayed in the cart with correct information. |
| TC-014 | Remove product from cart | High | PASS | Selected product was removed from the cart. |
| TC-015 | Continue shopping from cart | Medium | PASS | User was redirected back to the Products page. |
| TC-016 | Proceed to checkout from cart | High | PASS | User was redirected to the Checkout Information page. |
| TC-017 | Checkout with valid information | High | PASS | Valid checkout information was accepted and the Checkout Overview page was displayed. |
| TC-018 | Checkout with empty first name | High | PASS | Checkout was blocked and a validation message was displayed for the First Name field. |
| TC-019 | Checkout with empty last name | High | PASS | Checkout was blocked and a validation message was displayed for the Last Name field. |
| TC-020 | Checkout with empty postal code | High | PASS | Checkout was blocked and a validation message was displayed for the Postal Code field. |
| TC-021 | Verify checkout overview | High | PASS | Product, price, tax and total information were displayed correctly. |
| TC-022 | Complete checkout | High | PASS | Order was completed and the checkout confirmation page was displayed. |

---

## 4. Execution Summary

| Metric | Result |
|---|---:|
| Total Test Cases | 22 |
| Passed | 22 |
| Failed | 0 |
| Blocked | 0 |
| Not Executed | 0 |
| Pass Rate | 100% |

---

## 5. Test Coverage

The following application areas were covered:

- Authentication
- Product catalog
- Product sorting
- Product details
- Shopping cart
- Checkout
- Order completion

---

## 6. Checklist Execution

The Login Checklist was executed separately.

| Metric | Result |
|---|---:|
| Total Checklist Items | 27 |
| Passed | 27 |
| Failed | 0 |
| Pass Rate | 100% |

---

## 7. Defects

No confirmed functional defects were identified during the planned test execution.

Demonstration bug reports are maintained separately and are not counted as confirmed defects.

---

## 8. Test Environment

**Application:** SauceDemo

**Browser:** Google Chrome

**Operating System:** Windows

**Test Level:** UI

**Test Type:** Functional

---

## 9. Test Data

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

### Checkout Data

First Name:

`John`

Last Name:

`Smith`

Postal Code:

`12345`

---

## 10. Conclusion

All planned test cases were executed successfully.

The tested SauceDemo functionality behaved as expected during the test execution.

**Overall Result: PASS**

**Test Case Pass Rate: 100%**

**Checklist Pass Rate: 100%**

**Confirmed Defects: 0**
