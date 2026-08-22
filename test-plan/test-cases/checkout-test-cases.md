# Checkout Test Cases — SauceDemo

## Application Under Test

**Application:** SauceDemo  
**URL:** https://www.saucedemo.com/

---

## TC-017 — Checkout with valid information

### Preconditions

- User is logged in.
- At least one product is present in the cart.
- User is on the Checkout Information page.

### Test Data

- First Name: John
- Last Name: Smith
- Postal Code: 12345

### Steps

1. Enter `John` in the First Name field.
2. Enter `Smith` in the Last Name field.
3. Enter `12345` in the Postal Code field.
4. Click `Continue`.

### Expected Result

User is redirected to the Checkout Overview page.

### Priority

High

### Type

Positive

---

## TC-018 — Checkout with empty first name

### Preconditions

- User is logged in.
- At least one product is present in the cart.
- User is on the Checkout Information page.

### Test Data

- First Name: Empty
- Last Name: Smith
- Postal Code: 12345

### Steps

1. Leave the First Name field empty.
2. Enter `Smith` in the Last Name field.
3. Enter `12345` in the Postal Code field.
4. Click `Continue`.

### Expected Result

Checkout cannot continue and a validation error is displayed for the First Name field.

### Priority

High

### Type

Negative

---

## TC-019 — Checkout with empty last name

### Preconditions

- User is logged in.
- At least one product is present in the cart.
- User is on the Checkout Information page.

### Test Data

- First Name: John
- Last Name: Empty
- Postal Code: 12345

### Steps

1. Enter `John` in the First Name field.
2. Leave the Last Name field empty.
3. Enter `12345` in the Postal Code field.
4. Click `Continue`.

### Expected Result

Checkout cannot continue and a validation error is displayed for the Last Name field.

### Priority

High

### Type

Negative

---

## TC-020 — Checkout with empty postal code

### Preconditions

- User is logged in.
- At least one product is present in the cart.
- User is on the Checkout Information page.

### Test Data

- First Name: John
- Last Name: Smith
- Postal Code: Empty

### Steps

1. Enter `John` in the First Name field.
2. Enter `Smith` in the Last Name field.
3. Leave the Postal Code field empty.
4. Click `Continue`.

### Expected Result

Checkout cannot continue and a validation error is displayed for the Postal Code field.

### Priority

High

### Type

Negative

---

## TC-021 — Verify checkout overview

### Preconditions

- User has entered valid checkout information.
- User is on the Checkout Overview page.

### Steps

1. Review the selected product.
2. Review the product price.
3. Review the item total.
4. Review the tax.
5. Review the total amount.

### Expected Result

The checkout overview displays correct product and pricing information.

### Priority

High

### Type

Positive

---

## TC-022 — Complete checkout

### Preconditions

- User is logged in.
- User has at least one product in the cart.
- Valid checkout information has been entered.
- User is on the Checkout Overview page.

### Steps

1. Review the order information.
2. Click `Finish`.

### Expected Result

The order is successfully completed and the checkout confirmation page is displayed.

### Priority

High

### Type

Positive

---

## Test Coverage

The Checkout test suite covers:

- Valid checkout information
- Required field validation
- Checkout overview
- Product and price verification
- Order completion
