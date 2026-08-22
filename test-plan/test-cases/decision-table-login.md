# Login Decision Table

## Objective

Verify that the login functionality behaves correctly depending on whether the email and password are valid.

## Business Rule

A user can log in only when both the email and password are valid.

## Decision Table

| Condition / Rule  | Rule 1           | Rule 2         | Rule 3         | Rule 4         |
| ----------------- | ---------------- | -------------- | -------------- | -------------- |
| Email is valid    | Yes              | Yes            | No             | No             |
| Password is valid | Yes              | No             | Yes            | No             |
| Expected result   | Login successful | Login rejected | Login rejected | Login rejected |

## Rules Description

### Rule 1

* Email is valid.
* Password is valid.
* User should be successfully logged in.

### Rule 2

* Email is valid.
* Password is invalid.
* Login should be rejected.

### Rule 3

* Email is invalid.
* Password is valid.
* Login should be rejected.

### Rule 4

* Email is invalid.
* Password is invalid.
* Login should be rejected.

## Test Coverage

The decision table covers all possible combinations of the two conditions:

1. Valid email + valid password
2. Valid email + invalid password
3. Invalid email + valid password
4. Invalid email + invalid password
