# Test Execution Report

**Application:** Sauce Demo Shopify  
**URL:** https://sauce-demo.myshopify.com/  
**Total Test Cases:** 20  
**Execution Result:** 20 Passed, 0 Failed, 0 Blocked

---

## Execution Summary

| Status | Count |
|---|---:|
| PASS | 20 |
| FAIL | 0 |
| BLOCKED | 0 |
| Total | 20 |

---

## Test Execution Results

| ID | Test Case | Actual Result | Status | Priority |
|---|---|---|---|---|
| TC-001 | Login with valid customer credentials | User successfully logged in and accessed the account | PASS | High |
| TC-002 | Login with invalid email | Error message was displayed | PASS | High |
| TC-003 | Login with invalid password | Error message was displayed | PASS | High |
| TC-004 | Login with empty fields | Validation error was displayed | PASS | Medium |
| TC-005 | Create customer account with valid information | Customer account was created successfully | PASS | High |
| TC-006 | Verify products are displayed | Products were displayed correctly with names and prices | PASS | High |
| TC-007 | View product details | Product details page was displayed successfully | PASS | Medium |
| TC-008 | Verify sold-out products | Sold-out products were clearly identified and could not be purchased | PASS | High |
| TC-009 | Verify product price | Product price matched the displayed product price | PASS | Medium |
| TC-010 | Add available product to cart | Product was successfully added to the cart | PASS | High |
| TC-011 | Verify cart item count | Cart displayed the correct number of items | PASS | High |
| TC-012 | Verify product information in cart | Product name and price matched the selected product | PASS | High |
| TC-013 | Remove product from cart | Product was successfully removed from the cart | PASS | High |
| TC-014 | Prevent adding sold-out product | Sold-out product could not be added to the cart | PASS | High |
| TC-015 | Proceed to checkout | User successfully proceeded to the checkout page | PASS | High |
| TC-016 | Checkout with valid information | User successfully proceeded to the next checkout step | PASS | High |
| TC-017 | Checkout with missing required information | Validation error was displayed and checkout could not continue | PASS | High |
| TC-018 | Verify order summary | Products, quantities, prices and total were displayed correctly | PASS | High |
| TC-019 | Complete valid order | Order was successfully placed | PASS | High |
| TC-020 | Verify order confirmation | Order confirmation message/details were displayed successfully | PASS | High |

---

## Conclusion

All 20 test cases were executed successfully.

- **20 test cases passed**
- **0 test cases failed**
- **0 test cases were blocked**
- **Pass Rate: 100%**
