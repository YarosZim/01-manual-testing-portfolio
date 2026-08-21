# Login Test Cases

## TC-001 — Login with valid credentials

### Preconditions

User has a registered account.

### Test Data

Valid username and valid password.

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

User has a registered account.

### Test Data

Valid username and invalid password.

### Steps

1. Open the Login page.
2. Enter a valid username.
3. Enter an invalid password.
4. Click the Login button.

### Expected Result

The user remains on the Login page and an appropriate error message is displayed.

### Priority

High

### Type

Negative

---

## TC-003 — Login with empty username

### Steps

1. Open the Login page.
2. Leave the username field empty.
3. Enter a valid password.
4. Click the Login button.

### Expected Result

Validation message is displayed for the username field.

### Priority

High

### Type

Negative
