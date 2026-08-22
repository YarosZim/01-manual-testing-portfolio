# Test Design Techniques

This document demonstrates basic test design techniques used in manual software testing.

## 1. Equivalence Partitioning

Equivalence Partitioning is a test design technique that divides input data into groups where the system is expected to behave in the same way.

### Example

Requirement:

> Age must be between 18 and 65 inclusive.

The possible input values can be divided into three equivalence classes:

| Equivalence Class | Values    | Example | Expected Result |
| ----------------- | --------- | ------: | --------------- |
| Invalid           | Age < 18  |      17 | Invalid         |
| Valid             | Age 18–65 |      30 | Valid           |
| Invalid           | Age > 65  |      66 | Invalid         |

Instead of testing every possible age, we can select representative values from each class.

---

## 2. Boundary Value Analysis

Boundary Value Analysis focuses on values at and around the boundaries of an input range.

For the requirement:

> Age must be between 18 and 65 inclusive.

The boundary values are:

| Test Value | Expected Result |
| ---------: | --------------- |
|         17 | Invalid         |
|         18 | Valid           |
|         19 | Valid           |
|         64 | Valid           |
|         65 | Valid           |
|         66 | Invalid         |

The values immediately before, at, and after the boundaries are tested because defects often occur at boundary conditions.

---

## 3. Decision Table Testing

Decision Table Testing is used when the system behavior depends on multiple conditions.

### Example

Requirement:

> A user can log in if the email and password are both valid.

| Email   | Password | Expected Result  |
| ------- | -------- | ---------------- |
| Valid   | Valid    | Login successful |
| Valid   | Invalid  | Login rejected   |
| Invalid | Valid    | Login rejected   |
| Invalid | Invalid  | Login rejected   |

The decision table helps ensure that all important combinations of conditions are covered.

---

## Summary

The main techniques covered in this document are:

* Equivalence Partitioning — divides input data into logical groups.
* Boundary Value Analysis — tests values around input boundaries.
* Decision Table Testing — tests combinations of multiple conditions.
