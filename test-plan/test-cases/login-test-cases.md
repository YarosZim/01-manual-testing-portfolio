# Login Test Cases — SauceDemo

## Application Under Test

**Application:** SauceDemo  
**URL:** https://www.saucedemo.com/

---

## TC-001 — Successful login with valid credentials

### Preconditions

- SauceDemo application is available.
- User is on the Login page.

### Test Data

- Username: `standard_user`
- Password: `secret_sauce`

### Steps

1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.

### Expected Result

User is successfully logged in and redirected to the Products page.

### Priority

High

### Type

Positive

---

## TC-002 — Login with invalid password

### Preconditions

- SauceDemo application is available.
- User is on the Login page.

### Test Data

- Username: `standard_user`
- Password: `InvalidPassword123`

### Steps

1. Enter `standard_user` in the Username field.
2. Enter an invalid password.
3. Click the Login button.

### Expected Result

Login is rejected and an error message is displayed. The user remains on the Login page.

### Priority

High

### Type

Negative

---

## TC-003 — Login with empty username

### Preconditions

- SauceDemo application is available.
- User is on the Login page.

### Test Data

- Username: Empty
- Password: `secret_sauce`

### Steps

1. Leave the Username field empty.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.

### Expected Result

Login is rejected and a validation error is displayed for the Username field.

### Priority

High

### Type

Negative

---

## TC-004 — Login with empty password

### Preconditions

- SauceDemo application is available.
- User is on the Login page.

### Test Data

- Username: `standard_user`
- Password: Empty

### Steps

1. Enter `standard_user` in the Username field.
2. Leave the Password field empty.
3. Click the Login button.

### Expected Result

Login is rejected and a validation error is displayed for the Password field.

### Priority

High

### Type

Negative

---

## TC-005 — Login with invalid username

### Preconditions

- SauceDemo application is available.
- User is on the Login page.

### Test Data

- Username: `invalid_user`
- Password: `secret_sauce`

### Steps

1. Enter `invalid_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the Login button.

### Expected Result

Login is rejected and an error message is displayed.

### Priority

High

### Type

Negative

---

## TC-006 — Login with invalid username and invalid password

### Preconditions

- SauceDemo application is available.
- User is on the Login page.

### Test Data

- Username: `invalid_user`
- Password: `InvalidPassword123`

### Steps

1. Enter `invalid_user` in the Username field.
2. Enter `InvalidPassword123` in the Password field.
3. Click the Login button.

### Expected Result

Login is rejected and an error message is displayed.

### Priority

High

### Type

Negative

---

## Test Coverage

The login test suite covers:

- Successful login
- Invalid username
- Invalid password
- Invalid username and password
- Empty username
- Empty password
