# SauceDemo Functional Testing Checklist

## Application Under Test

**Application:** SauceDemo

**URL:** https://www.saucedemo.com/

**Browser:** Google Chrome

**Operating System:** Windows

---

# 1. Login

| ID | Check | Status |
|---|---|---|
| CH-001 | Login page is accessible | PASS |
| CH-002 | Username field is displayed | PASS |
| CH-003 | Password field is displayed | PASS |
| CH-004 | Login button is displayed | PASS |
| CH-005 | User can log in with valid credentials | PASS |
| CH-006 | Login is rejected with invalid password | PASS |
| CH-007 | Login is rejected with invalid username | PASS |
| CH-008 | Login is rejected with empty username | PASS |
| CH-009 | Login is rejected with empty password | PASS |
| CH-010 | Appropriate validation/error message is displayed | PASS |

---

# 2. Products

| ID | Check | Status |
|---|---|---|
| CH-011 | Products page is displayed after successful login | PASS |
| CH-012 | Product names are displayed | PASS |
| CH-013 | Product images are displayed | PASS |
| CH-014 | Product prices are displayed | PASS |
| CH-015 | Add to cart buttons are displayed | PASS |
| CH-016 | Products can be sorted by price low to high | PASS |
| CH-017 | Products can be sorted by price high to low | PASS |
| CH-018 | Product details page can be opened | PASS |
| CH-019 | Product description is displayed | PASS |
| CH-020 | Product price is displayed on product details page | PASS |
| CH-021 | Product can be added to cart | PASS |
| CH-022 | Product can be removed from cart from Products page | PASS |

---

# 3. Shopping Cart

| ID | Check | Status |
|---|---|---|
| CH-023 | Shopping cart icon is displayed | PASS |
| CH-024 | Added product is displayed in the cart | PASS |
| CH-025 | Product name is displayed in the cart | PASS |
| CH-026 | Product price is displayed in the cart | PASS |
| CH-027 | Product quantity is displayed correctly | PASS |
| CH-028 | Product can be removed from the cart | PASS |
| CH-029 | Cart counter is updated after adding a product | PASS |
| CH-030 | Cart counter is updated after removing a product | PASS |
| CH-031 | Continue Shopping button works | PASS |
| CH-032 | Checkout button works | PASS |

---

# 4. Checkout

| ID | Check | Status |
|---|---|---|
| CH-033 | Checkout Information page is displayed | PASS |
| CH-034 | First Name field is displayed | PASS |
| CH-035 | Last Name field is displayed | PASS |
| CH-036 | Postal Code field is displayed | PASS |
| CH-037 | User can continue with valid checkout information | PASS |
| CH-038 | Checkout is blocked when First Name is empty | PASS |
| CH-039 | Checkout is blocked when Last Name is empty | PASS |
| CH-040 | Checkout is blocked when Postal Code is empty | PASS |
| CH-041 | Validation messages are displayed for required fields | PASS |
| CH-042 | Checkout Overview page is displayed | PASS |
| CH-043 | Selected product is displayed on Checkout Overview | PASS |
| CH-044 | Product price is displayed correctly | PASS |
| CH-045 | Item total is displayed | PASS |
| CH-046 | Tax is displayed | PASS |
| CH-047 | Total amount is displayed | PASS |
| CH-048 | Finish button is displayed | PASS |
| CH-049 | Order can be completed | PASS |
| CH-050 | Order confirmation page is displayed | PASS |

---

# 5. Navigation

| ID | Check | Status |
|---|---|---|
| CH-051 | User can navigate from Login to Products | PASS |
| CH-052 | User can navigate from Products to Cart | PASS |
| CH-053 | User can navigate from Cart to Checkout | PASS |
| CH-054 | User can navigate from Cart back to Products | PASS |
| CH-055 | User can navigate from Checkout Information to Checkout Overview | PASS |
| CH-056 | User can complete the checkout flow | PASS |

---

# 6. UI and Usability

| ID | Check | Status |
|---|---|---|
| CH-057 | Main buttons are visible | PASS |
| CH-058 | Form fields are clearly identifiable | PASS |
| CH-059 | Product information is readable | PASS |
| CH-060 | Error messages are visible to the user | PASS |
| CH-061 | Navigation elements are accessible | PASS |
| CH-062 | Page layout is displayed correctly | PASS |

---

# 7. Checklist Summary

| Category | Checks | Passed | Failed |
|---|---:|---:|---:|
| Login | 10 | 10 | 0 |
| Products | 12 | 12 | 0 |
| Shopping Cart | 10 | 10 | 0 |
| Checkout | 18 | 18 | 0 |
| Navigation | 6 | 6 | 0 |
| UI and Usability | 6 | 6 | 0 |
| **Total** | **62** | **62** | **0** |

---

# 8. Overall Result

**Total Checks:** 62

**Passed:** 62

**Failed:** 0

**Pass Rate:** 100%

**Overall Status:** PASS

---

# 9. Notes

The checklist was executed against the SauceDemo web application using Google Chrome on Windows.

No issues were identified during the checklist execution.
