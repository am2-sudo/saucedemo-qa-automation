Test Cases
1. Login
 | ID     | Test Case                    | Preconditions         | Test Steps                                      | Expected Result                        | Priority |
| ------ | ---------------------------- | --------------------- | ----------------------------------------------- | -------------------------------------- | -------- |
| TC-001 | Login with valid credentials | User is on login page | Enter valid username and password → Click Login | User is redirected to Products page    | High     |
| TC-002 | Login with invalid username  | User is on login page | Enter invalid username + valid password → Login | Error message is displayed             | High     |
| TC-003 | Login with invalid password  | User is on login page | Enter valid username + invalid password → Login | Error message is displayed             | High     |
| TC-004 | Login with empty fields      | User is on login page | Leave fields empty → Login                      | Validation error is displayed          | Medium   |
| TC-005 | Login with locked user       | User is on login page | Enter locked-user credentials → Login           | Locked-user error message is displayed | High     |
2. Products
| ID     | Test Case                     | Preconditions            | Test Steps              | Expected Result                   | Priority |
| ------ | ----------------------------- | ------------------------ | ----------------------- | --------------------------------- | -------- |
| TC-006 | Verify products are displayed | User is logged in        | Open Products page      | Products are displayed correctly  | High     |
| TC-007 | View product details          | User is on Products page | Click a product         | Product details page is displayed | Medium   |
| TC-008 | Sort products                 | User is on Products page | Select a sorting option | Products are reordered correctly  | Medium   |
3. Shopping Cart
| ID     | Test Case                          | Preconditions          | Test Steps        | Expected Result                       | Priority |
| ------ | ---------------------------------- | ---------------------- | ----------------- | ------------------------------------- | -------- |
| TC-009 | Add product to cart                | User is logged in      | Click Add to Cart | Product is added to cart              | High     |
| TC-010 | Verify cart item count             | Product has been added | Open cart         | Correct number of items is displayed  | High     |
| TC-011 | Remove product from cart           | Product exists in cart | Click Remove      | Product is removed from cart          | High     |
| TC-012 | Verify product information in cart | Product exists in cart | Open cart         | Name and price match selected product | Medium   |
4. Checkout
| ID     | Test Case                        | Preconditions            | Test Steps                                  | Expected Result                        | Priority |
| ------ | -------------------------------- | ------------------------ | ------------------------------------------- | -------------------------------------- | -------- |
| TC-013 | Proceed to checkout              | Product exists in cart   | Open cart → Checkout                        | Checkout information page is displayed | High     |
| TC-014 | Checkout with valid information  | User is on checkout page | Enter First Name, Last Name, ZIP → Continue | User proceeds to order overview        | High     |
| TC-015 | Checkout with missing first name | User is on checkout page | Leave First Name empty → Continue           | Validation error is displayed          | High     |
| TC-016 | Checkout with missing last name  | User is on checkout page | Leave Last Name empty → Continue            | Validation error is displayed          | Medium   |
| TC-017 | Checkout with missing ZIP code   | User is on checkout page | Leave ZIP empty → Continue                  | Validation error is displayed          | Medium   |
5. Order Completion
| ID     | Test Case                 | Preconditions                       | Test Steps              | Expected Result                                    | Priority |
| ------ | ------------------------- | ----------------------------------- | ----------------------- | -------------------------------------------------- | -------- |
| TC-018 | Verify order overview     | User completed checkout information | Review order            | Products, prices and total are displayed correctly | High     |
| TC-019 | Complete valid order      | User is on order overview           | Click Finish            | Order is completed successfully                    | High     |
| TC-020 | Verify order confirmation | Order has been completed            | Check confirmation page | Order confirmation message is displayed            | High     |
