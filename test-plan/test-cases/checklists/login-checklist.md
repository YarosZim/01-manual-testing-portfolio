# Login Checklist — SauceDemo

## Application Under Test

**Application:** SauceDemo

**URL:** https://www.saucedemo.com/

**Browser:** Google Chrome

**Operating System:** Windows

---

## 1. Login Page

| ID | Check | Status |
|---|---|---|
| CH-001 | Login page is accessible | PASS |
| CH-002 | Username field is displayed | PASS |
| CH-003 | Password field is displayed | PASS |
| CH-004 | Login button is displayed | PASS |
| CH-005 | Username field accepts text input | PASS |
| CH-006 | Password field accepts text input | PASS |
| CH-007 | Password input is masked | PASS |

---

## 2. Valid Login

| ID | Check | Status |
|---|---|---|
| CH-008 | User can log in with valid username and password | PASS |
| CH-009 | User is redirected to the Products page | PASS |
| CH-010 | Products page is displayed after successful login | PASS |

---

## 3. Invalid Login

| ID | Check | Status |
|---|---|---|
| CH-011 | Login is rejected with an invalid password | PASS |
| CH-012 | Login is rejected with an unregistered username | PASS |
| CH-013 | Login is rejected with an unregistered username and invalid password | PASS |
| CH-014 | Appropriate authentication error message is displayed | PASS |
| CH-015 | User remains on the Login page after failed authentication | PASS |

---

## 4. Empty Fields

| ID | Check | Status |
|---|---|---|
| CH-016 | Login is rejected when Username is empty | PASS |
| CH-017 | Validation message is displayed for empty Username | PASS |
| CH-018 | Login is rejected when Password is empty | PASS |
| CH-019 | Validation message is displayed for empty Password | PASS |
| CH-020 | Login is rejected when both fields are empty | PASS |

---

## 5. Error Message

| ID | Check | Status |
|---|---|---|
| CH-021 | Error message is visible to the user | PASS |
| CH-022 | Error message does not disappear immediately | PASS |
| CH-023 | Error message is displayed in the correct area | PASS |
| CH-024 | Error message does not allow successful authentication | PASS |

---

## 6. Login Navigation

| ID | Check | Status |
|---|---|---|
| CH-025 | Successful login opens the Products page | PASS |
| CH-026 | Failed login keeps the user on the Login page | PASS |
| CH-027 | Login page can be refreshed without unexpected behavior | PASS |

---

## 7. Checklist Summary

| Category | Checks | Passed | Failed |
|---|---:|---:|---:|
| Login Page | 7 | 7 | 0 |
| Valid Login | 3 | 3 | 0 |
| Invalid Login | 5 | 5 | 0 |
| Empty Fields | 5 | 5 | 0 |
| Error Message | 4 | 4 | 0 |
| Navigation | 3 | 3 | 0 |
| **Total** | **27** | **27** | **0** |

---

## 8. Overall Result

**Total Checks:** 27

**Passed:** 27

**Failed:** 0

**Pass Rate:** 100%

**Overall Status:** PASS

---

## 9. Notes

The Login functionality was checked using valid credentials, invalid credentials and empty input fields.

No issues were identified during the checklist execution.
