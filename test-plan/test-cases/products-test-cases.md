# Products Test Cases — SauceDemo

## Application Under Test

**Application:** SauceDemo  
**URL:** https://www.saucedemo.com/

---

## TC-007 — Products are displayed after successful login

### Preconditions

- User is logged in as `standard_user`.
- User is on the Products page.

### Steps

1. Observe the Products page.
2. Check the product list.
3. Check the product names and prices.

### Expected Result

- Products are displayed.
- Each product has a name.
- Each product has a price.
- Each product has an Add to cart button.

### Priority

High

### Type

Positive

---

## TC-008 — Sort products by price from low to high

### Preconditions

- User is logged in.
- User is on the Products page.

### Steps

1. Open the sorting dropdown.
2. Select `Price (low to high)`.
3. Observe the product prices.

### Expected Result

Products are sorted by price in ascending order.

### Priority

Medium

### Type

Positive

---

## TC-009 — Sort products by price from high to low

### Preconditions

- User is logged in.
- User is on the Products page.

### Steps

1. Open the sorting dropdown.
2. Select `Price (high to low)`.
3. Observe the product prices.

### Expected Result

Products are sorted by price in descending order.

### Priority

Medium

### Type

Positive

---

## TC-010 — Open product details

### Preconditions

- User is logged in.
- User is on the Products page.

### Steps

1. Select any product.
2. Click the product name or product image.

### Expected Result

The product details page is opened and displays:

- Product name
- Product description
- Product price
- Product image
- Add to cart button

### Priority

Medium

### Type

Positive

---

## TC-011 — Add product to cart from Products page

### Preconditions

- User is logged in.
- User is on the Products page.
- Cart is empty.

### Steps

1. Select any product.
2. Click the `Add to cart` button.
3. Observe the shopping cart icon.

### Expected Result

- The selected product is added to the cart.
- The cart icon displays the number of added items.

### Priority

High

### Type

Positive

---

## TC-012 — Remove product from Products page

### Preconditions

- User is logged in.
- User is on the Products page.
- At least one product has been added to the cart.

### Steps

1. Click the `Remove` button for an added product.
2. Observe the shopping cart icon.

### Expected Result

- The product is removed from the cart.
- The cart item count is updated.

### Priority

High

### Type

Positive

---

## Test Coverage

The Products test suite covers:

- Product visibility
- Product information
- Product sorting
- Product details
- Adding products to cart
- Removing products from cart
