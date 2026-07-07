| TC ID | Scenario | Expected Result | Actual Result | Status |
|-------|----------|-----------------|---------------|--------|
| TC-001 | Valid Login | User is redirected to the Products page. | User was successfully redirected to the Products page. | PASS |
| TC-002 | Invalid Password | Error message should be displayed. | "Epic sadface: Username and password do not match any user in this service." | PASS |
| TC-003 | Invalid Username | Error message should be displayed. | "Epic sadface: Username and password do not match any user in this service." | PASS |
| TC-004 | Empty Username | "Username is required" should be displayed. | "Epic sadface: Username is required." | PASS |
| TC-005 | Empty Password | "Password is required" should be displayed. | "Epic sadface: Password is required." | PASS |
| TC-006 | Both Fields Empty | Validation error should be displayed. | "Epic sadface: Username is required." | PASS |
| TC-007 | View Products | All products should be displayed. | All products were displayed successfully. | PASS |
| TC-008 | Product Image | Clicking the product image should open the product details page. | Product details page opened successfully. | PASS |
| TC-009 | Product Name | Clicking the product name should open the product details page. | Product details page opened successfully. | PASS |
| TC-010 | Sort A-Z | Products should be sorted alphabetically. | Products were sorted correctly. | PASS |
| TC-011 | Sort Z-A | Products should be sorted in reverse alphabetical order. | Products were sorted correctly. | PASS |
| TC-012 | Sort Low-High | Products should be sorted by ascending price. | Products were sorted correctly. | PASS |
| TC-013 | Sort High-Low | Products should be sorted by descending price. | Products were sorted correctly. | PASS |
| TC-014 | Add to Cart | Selected product should be added to the cart. | Product was added successfully. | PASS |
| TC-015 | Remove Product | Selected product should be removed from the cart. | Product was removed successfully. | PASS |
| TC-016 | Cart Badge | Badge count should increase after adding a product. | Badge updated correctly. | PASS |
| TC-017 | Cart Badge | Badge count should decrease after removing a product. | Badge updated correctly. |  PASS |