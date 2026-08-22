# Login Test Cases — SauceDemo

## Application Under Test

**Application:** SauceDemo  
**URL:** https://www.saucedemo.com/

## Test Environment

- Platform: Web
- Browser: Chrome
- Test Type: Functional
- Test Level: UI

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

User is successfully authenticated and redirected to the Products page.

### Priority

High

### Type

Positive

### Status

Not Executed

---

## TC-002 — Login with valid username and invalid password

### Preconditions

- SauceDemo application is available.
- User is on the Login page.

### Test Data

- Username: `standard_user`
- Password: `InvalidPassword123`

### Steps

1. Enter `standard_user` in the Username field.
2. Enter `InvalidPassword123` in the Password field.
3. Click the Login button.

### Expected Result

Login is rejected and an appropriate error message is displayed. User remains on the Login page.

### Priority

High

### Type

Negative

### Status

Not Executed

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

Login is rejected and a validation message is displayed indicating that the Username field is required.

### Priority

High

### Type

Negative

### Status

Not Executed

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

Login is rejected and a validation message is displayed indicating that the Password field is required.

### Priority

High

### Type

Negative

### Status

Not Executed

---

## TC-005 — Login with unregistered username

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

Login is rejected and an appropriate authentication error message is displayed.

### Priority

High

### Type

Negative

### Status

Not Executed

---

## TC-006 — Login with unregistered username and invalid password

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

Login is rejected and an appropriate authentication error message is displayed.

### Priority

High

### Type

Negative

### Status

Not Executed

---

## Test Coverage

The login test suite covers:

- Successful authentication
- Invalid password
- Empty username
- Empty password
- Unregistered username
- Unregistered username with invalid password

### Test Design Techniques

The following techniques are applied:

- Equivalence Partitioning
- Negative Testing
- Decision Table Testing
