# Cart Test Cases — SauceDemo

## Application Under Test

**Application:** SauceDemo  
**URL:** https://www.saucedemo.com/

---

## TC-013 — Added product is displayed in the cart

### Preconditions

- User is logged in.
- At least one product has been added to the cart.

### Steps

1. Click the shopping cart icon.
2. Observe the cart contents.

### Expected Result

The cart page is opened and the added product is displayed with the correct name, price and quantity.

### Priority

High

### Type

Positive

---

## TC-014 — Remove product from cart

### Preconditions

- User is logged in.
- At least one product is present in the cart.

### Steps

1. Open the shopping cart.
2. Click `Remove` for a product.

### Expected Result

The selected product is removed from the cart and the cart item count is updated.

### Priority

High

### Type

Positive

---

## TC-015 — Continue shopping from cart

### Preconditions

- User is logged in.
- User is on the Cart page.

### Steps

1. Click `Continue Shopping`.

### Expected Result

User is redirected back to the Products page.

### Priority

Medium

### Type

Positive

---

## TC-016 — Proceed to checkout from cart

### Preconditions

- User is logged in.
- At least one product is present in the cart.

### Steps

1. Open the Cart page.
2. Click `Checkout`.

### Expected Result

User is redirected to the Checkout Information page.

### Priority

High

### Type

Positive

---

## Test Coverage

The Cart test suite covers:

- Cart contents
- Product information
- Product removal
- Continue shopping
- Checkout navigation
