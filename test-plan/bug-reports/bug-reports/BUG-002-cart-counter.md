# BUG-002 — Cart counter is not updated correctly

## Bug Information

**Bug ID:** BUG-002

**Title:** Cart item counter is not updated correctly after removing a product

**Severity:** Medium

**Priority:** Medium

**Status:** Demonstration

**Type:** Functional

---

## Environment

**Application:** SauceDemo

**URL:** https://www.saucedemo.com/

**Browser:** Google Chrome

**Operating System:** Windows

---

## Preconditions

- User is logged in as `standard_user`.
- Products page is displayed.

---

## Test Data

Product:

`Sauce Labs Backpack`

---

## Steps to Reproduce

1. Log in using valid credentials.
2. Add `Sauce Labs Backpack` to the cart.
3. Verify that the cart counter displays `1`.
4. Remove the product.
5. Observe the shopping cart counter.

---

## Expected Result

The product is removed from the cart and the cart counter is removed or updated to `0`.

---

## Actual Result

The actual result should be documented during test execution.

---

## Reproducibility

To be determined during execution.

---

## Attachments

Screenshot or screen recording can be attached after reproduction.

---

## Notes

This report is a demonstration template and must not be considered a confirmed production defect until the behavior has been reproduced and verified.
