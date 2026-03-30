| Test Case ID | Title | Preconditions | Steps | Test Data | Expected Result | Actual Result | Status | Priority | Notes |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| TC-41 | Verify user can proceed with valid checkout information | Checkout Page is open; <br>Product(s) added to cart | 1. Enter valid First Name, Last Name, Zip/Postal Code <br>2. Click "Continue" | John / Doe / 12345 | User is navigated to Checkout Overview Page |  |  |  |  |
| TC-42 | Verify error message for empty First Name | Checkout Page is open | 1. Leave First Name empty <br>2. Fill other fields <br>3. Click "Continue" | / Doe / 12345 | Error message displayed: “First Name is required” |  |  |  |  |
| TC-43 | Verify error message for empty Last Name | Checkout Page is open | 1. Fill First Name <br>2. Leave Last Name empty <br>3. Click "Continue" | John /  / 12345 | Error message displayed: “Last Name is required” |  |  |  |  |
| TC-44 | Verify error message for empty Zip/Postal Code | Checkout Page is open | 1. Fill First and Last Name <br>2. Leave Zip empty <br>3. Click "Continue" | John / Doe / | Error message displayed: “Postal Code is required” |  |  |  |  |
| TC-45 | Verify clicking “Continue” redirects to Overview Page | Checkout Page is open;<br>Valid checkout info filled | 1. Click Continue | John / Doe / 12345 | User is navigated to Checkout Overview Page |  |  |  |  |
| TC-46 | Verify clicking “Cancel” returns to Cart Page | Checkout Page is open | 1. Click Cancel | N/A | User is navigated back to Cart Page |  |  |  |  |
| TC-47 | Verify Overview Page opens successfully | User navigated from Checkout Page | 1. Open Overview Page | N/A | Page loads correctly |  |  |  |  |
| TC-48 | Verify selected products are listed with correct details | Overview Page is open | 1. Observe product names, prices, and quantities | Any products | All products match selection |  |  |  |  |
| TC-49 | Verify item total, tax, and final total are calculated correctly | Overview Page is open | 1. Check item totals, tax, and total | N/A | Values calculated correctly |  |  |  |  |
| TC-50 | Verify clicking “Finish” redirects to Order Completion page | Overview Page is open | 1. Click Finish | N/A | User navigated to Checkout Complete Page |  |  |  |  |
| TC-51 | Verify clicking “Cancel” redirects to Products Page | Overview Page is open | 1. Click Cancel | N/A | User navigated back to Products Page |  |  |  |  |
| TC-52 | Verify page loads correctly | Checkout Complete Page is open | 1. Observe page load | N/A | Page loads without errors |  |  |  |  |
| TC-53 | Verify confirmation message is displayed | Checkout Complete Page is open | 1. Observe page | N/A | Confirmation message visible |  |  |  |  |
| TC-54 | Verify clicking “Back Home” redirects to products page | Checkout Complete Page is open | 1. Click Back Home | N/A | User navigated to Products Page |  |  |  |  |
