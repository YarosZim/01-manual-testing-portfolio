# Login Test Cases

## TC-001 — Login with valid credentials

### Preconditions

- User is registered
- User is on the Login page

### Test Data

- Email: user@test.com
- Password: Password123

### Steps

1. Open the Login page.
2. Enter a valid username.
3. Enter a valid password.
4. Click the Login button.

### Expected Result

User is successfully logged in.

### Priority

High

### Type

Positive

---

## TC-002 — Login with invalid password

### Preconditions

User is registered and is on the Login page.

### Test Data

- Email: user@test.com
- Password: InvalidPassword123

### Steps

1. Enter a valid email address.
2. Enter an invalid password.
3. Click the Login button.

### Expected Result

The user remains on the Login page and an appropriate error message is displayed.

### Priority

High

### Type

Negative

---

## TC-003 — Login with empty email

### Preconditions

User is registered and is on the Login page.

### Test Data

- Email: Empty
- Password: Password123

### Steps

1. Leave the email field empty.
2. Enter a valid password.
3. Click the Login button.

### Expected Result

A validation message is displayed for the email field, and the user is not logged in.

### Priority

High

### Type

Negative

---

## TC-004 — Login with empty password

### Preconditions

User is registered and is on the Login page.

### Test Data

- Email: user@test.com
- Password: Empty

### Steps

1. Enter a valid email address.
2. Leave the password field empty.
3. Click the Login button.

### Expected Result

A validation message is displayed for the password field, and the user is not logged in.

### Priority

High

### Type

Negative

---

## TC-005 — Login with invalid email

### Preconditions

User is registered and is on the Login page.

### Test Data

* Email: invalid-email
* Password: Password123

### Steps

1. Enter an invalid email address.
2. Enter a valid password.
3. Click the Login button.

### Expected Result

A validation message is displayed for the email field, and the user is not logged in.

### Priority

High

### Type

Negative

---

