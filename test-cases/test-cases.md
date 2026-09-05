# Test Cases

**Application:** Sauce Demo Shopify
**URL:** https://sauce-demo.myshopify.com/

---

## 1. Customer Account / Login

| ID | Test Case | Preconditions | Test Steps | Expected Result | Priority |
|---|---|---|---|---|---|
| TC-001 | Login with valid customer credentials | User has a registered account | Enter valid email and password → Click Login | User is successfully logged in and redirected to the account page | High |
| TC-002 | Login with invalid email | User is on login page | Enter invalid email and valid password → Click Login | An error message is displayed | High |
| TC-003 | Login with invalid password | User has a registered account | Enter valid email and invalid password → Click Login | An error message is displayed | High |
| TC-004 | Login with empty fields | User is on login page | Leave email and password empty → Click Login | Validation error is displayed | Medium |
| TC-005 | Create customer account with valid information | User does not have an account | Open Create Account → Enter valid first name, last name, email and password → Submit | Customer account is created successfully | High |

---

## 2. Products

| ID | Test Case | Preconditions | Test Steps | Expected Result | Priority |
|---|---|---|---|---|---|
| TC-006 | Verify products are displayed | User is on Products page | Open Products/Catalog page | Available products are displayed with names and prices | High |
| TC-007 | View product details | User is on Products page | Click a product | Product details page is displayed with product information | Medium |
| TC-008 | Verify sold-out products | User is on Products page | Locate a sold-out product | Product is clearly marked as Sold Out and cannot be purchased | High |
| TC-009 | Verify product price | User is on Products page | Select a product and view its details | Product price is displayed correctly and matches the Products page | Medium |

---

## 3. Shopping Cart

| ID | Test Case | Preconditions | Test Steps | Expected Result | Priority |
|---|---|---|---|---|---|
| TC-010 | Add available product to cart | User is on a product page | Click Add to Cart | Product is added to the shopping cart | High |
| TC-011 | Verify cart item count | Product has been added to cart | Open/view cart | Cart displays the correct number of items | High |
| TC-012 | Verify product information in cart | Product exists in cart | Open cart | Product name and price match the selected product | High |
| TC-013 | Remove product from cart | Product exists in cart | Open cart → Click Remove | Product is removed and cart is updated correctly | High |
| TC-014 | Prevent adding sold-out product | User is viewing a sold-out product | Attempt to add the sold-out product to cart | Product cannot be added to the cart | High |

---

## 4. Checkout

| ID | Test Case | Preconditions | Test Steps | Expected Result | Priority |
|---|---|---|---|---|---|
| TC-015 | Proceed to checkout | Product exists in cart | Open cart → Click Checkout | User is taken to the checkout page | High |
| TC-016 | Checkout with valid information | User is on checkout page | Enter all required customer and shipping information → Continue | User proceeds to the next checkout step | High |
| TC-017 | Checkout with missing required information | User is on checkout page | Leave a required field empty → Continue | Validation error is displayed and checkout cannot continue | High |

---

## 5. Order Completion

| ID | Test Case | Preconditions | Test Steps | Expected Result | Priority |
|---|---|---|---|---|---|
| TC-018 | Verify order summary | User has completed required checkout information | Review order summary | Selected products, quantities, prices and total are displayed correctly | High |
| TC-019 | Complete valid order | User is on the final checkout step | Confirm order using valid information | Order is successfully placed | High |
| TC-020 | Verify order confirmation | Order has been successfully placed | View confirmation page | Order confirmation message/details are displayed | High |
