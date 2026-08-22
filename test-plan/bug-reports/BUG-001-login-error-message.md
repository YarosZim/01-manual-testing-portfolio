# BUG-001 — Login error message is displayed for invalid credentials

## Bug Information

**Bug ID:** BUG-001

**Title:** Login error message is displayed when invalid credentials are entered

**Severity:** Medium

**Priority:** Medium

**Status:** Open

**Type:** Functional

---

## Environment

**Application:** SauceDemo

**URL:** https://www.saucedemo.com/

**Browser:** Google Chrome

**Operating System:** Windows

---

## Preconditions

- SauceDemo application is available.
- User is on the Login page.

---

## Test Data

**Username:**

`invalid_user`

**Password:**

`InvalidPassword123`

---

## Steps to Reproduce

1. Open the SauceDemo Login page.
2. Enter `invalid_user` into the Username field.
3. Enter `InvalidPassword123` into the Password field.
4. Click the Login button.

---

## Expected Result

Login is rejected and an appropriate authentication error message is displayed.

---

## Actual Result

An authentication error message is displayed and the user remains on the Login page.

---

## Reproducibility

100%

---

## Attachments

No attachment available.

---

## Notes

This report is included as a demonstration of professional bug reporting structure.

The observed behavior does not prevent the user from being informed that authentication failed.
