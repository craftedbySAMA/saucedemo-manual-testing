 Module 1 - Login

| TC ID | Test Case | Preconditions | Test Steps | Test Data | Expected Result |
|------|-----------|---------------|------------|-----------|-----------------|
| TC-001 | Verify login with valid credentials | User is on the Login page | 1. Enter valid username.<br>2. Enter valid password.<br>3. Click **Login**. | Username: standard_user<br>Password: secret_sauce | User is redirected to the Products page successfully. |
| TC-002 | Verify login with an invalid password | User is on the Login page | 1. Enter valid username.<br>2. Enter an invalid password.<br>3. Click **Login**. | Username: standard_user<br>Password: wrong_password | An error message is displayed and the user remains on the Login page. |
| TC-003 | Verify login with an invalid username | User is on the Login page | 1. Enter an invalid username.<br>2. Enter a valid password.<br>3. Click **Login**. | Username: invalid_user<br>Password: secret_sauce | An error message is displayed and the user remains on the Login page. |
| TC-004 | Verify login with an empty username | User is on the Login page | 1. Leave the Username field empty.<br>2. Enter a valid password.<br>3. Click **Login**. | Password: secret_sauce | "Epic sadface: Username is required" is displayed. |
| TC-005 | Verify login with an empty password | User is on the Login page | 1. Enter a valid username.<br>2. Leave the Password field empty.<br>3. Click **Login**. | Username: standard_user | "Epic sadface: Password is required" is displayed. |
| TC-006 | Verify login with both fields empty | User is on the Login page | 1. Leave Username empty.<br>2. Leave Password empty.<br>3. Click **Login**. | None | "Epic sadface: Username is required" is displayed. |
| TC-007 | Verify login with a locked user | User is on the Login page | 1. Enter locked_out_user.<br>2. Enter secret_sauce.<br>3. Click **Login**. | Username: locked_out_user<br>Password: secret_sauce | Locked user error message is displayed. |


 Module 2 - Products

| TC ID | Test Case | Preconditions | Test Steps | Test Data | Expected Result |
|------|-----------|---------------|------------|-----------|-----------------|
| TC-008 | Verify all products are displayed | User is logged in | 1. Log in successfully.<br>2. Observe the Products page. | Valid user | All available products are displayed. |
| TC-009 | Verify opening product details by clicking the image | User is logged in | 1. Click a product image. | Any product | Product Details page opens. |
| TC-010 | Verify opening product details by clicking the product name | User is logged in | 1. Click a product name. | Any product | Product Details page opens. |
| TC-011 | Verify Add to Cart functionality | User is logged in | 1. Click **Add to Cart**. | Any product | Product is added to the shopping cart and badge count increases. |
| TC-012 | Verify Remove functionality | User is logged in | 1. Add a product.<br>2. Click **Remove**. | Any product | Product is removed from the shopping cart and badge count decreases. |
| TC-013 | Verify sorting by Name (A to Z) | User is logged in | 1. Select **Name (A to Z)** from the sort dropdown. | None | Products are sorted alphabetically. |
| TC-014 | Verify sorting by Name (Z to A) | User is logged in | 1. Select **Name (Z to A)** from the sort dropdown. | None | Products are sorted in reverse alphabetical order. |
| TC-015 | Verify sorting by Price (Low to High) | User is logged in | 1. Select **Price (Low to High)**. | None | Products are sorted by ascending price. |
| TC-016 | Verify sorting by Price (High to Low) | User is logged in | 1. Select **Price (High to Low)**. | None | Products are sorted by descending price. |